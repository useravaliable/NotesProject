## 创建项目：
### rails_auth项目
---
* 下载项目:
   * `git clone https://github.com/work-design/rails_auth.git`
---
* 初始化
---
* 进入项目主目录
  + `cd rails_auth/`
---
* 安装bundle
  + `bundle install`
---
* 安装yarn
  + `yarn install`
---
* 下载项目子模块
  + `git submodule update --init`
---
* 进入项目测试文件夹下的dummy目录
  + `cd rails_auth/test/dummy/`
  * 执行命令 `find . -name '*.lock'`
  + 具有Gemfile.lock的目录执行 `bundle install`
  + 具有yarn.lock的目录执行`yarn install`
---

* 复制`重要文件`至指定目录下
  + 注意:所有的development.key、development.yml.enc来自rails_auth下
  + 复制文件development.yml.enc和test.yml.enc到 rails_auth/test/dummy/config/credentials目录下
  + 在rails_com/目录下执行命令`bin/rails credentials:show --environment development`
    + ps:若文件移动错目录了,改后重新执行`bin/rails credentials:show --environment development`
---
* 迁移数据库
  + `rake db:migrate`
    * 报错 则 `bundle exec rake db:migrate` 再次执行 `rake db:migrate`
---
* 测试启动
  * 1shell
    + `cd rails_auth/test/dummy`
    + `bin/vite`

  * 2shell
    + `cd rails_auth/`
    + `bin/rails s`

* 打开谷歌浏览器
  + 地址栏输入localhost:3000
  + 出现非404页面即可成功
---
