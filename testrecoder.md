# 创建项目：
## rails_auth项目
---
## 下载项目:
### git clone https://github.com/work-design/rails_auth.git
---
## 初始化
---
### 进入项目主目录
### cd rails_auth/
---
### 安装bundle
### bundle install
---
### 安装yarn
### yarn install
---
### 下载项目子模块
### git submodule update --init
---
### 进入测试文件夹下的dummy目录
### cd test/dummy/
---
### 安装yarn
### yarn install
---
### 安装bundle
### bundle install
---
### 复制`重要`文件至指定目录下
### 复制文件development.yml.enc和test.yml.enc 到 test/dummy/config/credentials目录下
---
## 迁移数据库
---
### rake db:migrate
## 测试启动
### cd rails_auth
### bin/vite [^error]
[^error]:bin/vite遇到如下错误时：error when starting dev server: Error: The following dependencies are imported but could not be resolved:   cd /Users/qmy/.rbenv/versions/3.0.2/lib/ruby/gems/3.0.0/bundler/gems/rails_ui-bd2433c8d9a2      yarn install
### bin/rails s
---













## 怎样查看错误
### 在浏览器查看错误
---
## 如何测试文件
### 命令行内运行bin/rails test test文件
---
## 怎样查看路由
### cd rails_auth/
### rails routes | grep test
---

## 测试时要注意的小bug
### 写代码时要注意格式如‘，’后加空格
### 在进行git提交时使用Git status
### 查看是否多出来一些文件，污染了git项目
### ps:
---

## mvc概念
### view视图+models模型+controllers控制器

---
## rails_auth项目
---
## 下载项目:
---
### git clone https://github.com/work-design/rails_auth.git
---
## 初始化
---
### 进入项目主目录
### cd rails_auth/
---
### 安装bundle
### bundle install
---
### 安装yarn
### yarn install
---
### 下载项目子模块
### git submodule update --init
---
### 进入测试文件夹下的dummy目录
### cd test/dummy/
---
### 安装yarn
### yarn install
---
### 复制`重要`文件至指定目录下
### 复制文件development.yml.enc和test.yml.enc 到 test/dummy/config/credentials目录下
---
## 迁移数据库
---
### rake db:migrate
## 测试启动
### cd rails_auth
### bin/vite
### bin/rails s
---

[隐藏内容](file:///Users/qmy/dong/dong/trask/error.txt)


### markdown 学习
# h1
## h2
### h3
#### h4
##### h5
###### h6

## 水平线
---
***
___

**文本样式**
__22222222__
*1111111111*
_1111111111_
~~12345678~~

* 123
+ 123
- 123无序列表

1. 123
2. 123
3. 123有序列表

Include `代码`

   //some code
   line 1
   line 2

```
some text
```
