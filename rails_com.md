### 项目rails_com
---
* 初始化
---
  + 下载rails_com项目
    * `git clone git@github.com:work-design/rails_com.git`
---
  + 安装配置文件
---
  + 进入项目主目录
    * `cd rails_com/`
---
  + 安装bundle
    * `bundle install`
---
  + 安装yarn
    * `yarn install`
---
  + 安装子模块
    * `git submodule update --init`
---
  * 进入项目测试文件夹下的dummy目录
    + `cd rails_com/test/dummy/`
    * 执行命令 `find . -name '*.lock'`
    + 具有Gemfile.lock的目录执行 `bundle install`
    + 具有yarn.lock的目录执行`yarn install`
---
  + 复制文件
    * 复制`重要`文件至指定目录下
    * 注意:development.key   development.yml.enc都是rails_auth下的
    * 复制文件development.yml.enc和test.yml.enc 到 test/dummy/config/credentials目录下
    * 在rails_com/下执行`bin/rails credentials:show --environment development`
    * ps:若文件移动错了,改后需要执行`bin/rails credentials:show --environment development`
    
    * `cd rails_com/test/dummy/bin`
    * 执行命令`bundle exec rake db:migrate`
    * `rake db:migrate`
    
* 测试
  + 1shell
    * `cd rails_com/`
    * `bin/rails s`
  + 2shell
    * `cd rails_com/test/dummy/`
    * `bin/vite`





* 打开谷歌浏览器
  + 地址栏输入localhost:3000
  + 出现非404页面即可成功


测试模块：
bin/rails routes

n行
name get /auth/board/:id  /auth/board#new
     协议       路径               控制器


