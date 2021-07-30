
* test rb文件基本格式
  + `require 'test_helper'`
  + `class XXXTest < XXX::XXXCase`
    * `test "" do`
      * `code`
      * `assert_***  * *`
      * end
    * end


---
## 注释
 * 怎样查看test测试错误
   * 可以在浏览器localhost:3000/+测试目录中找到并查看其错误
---
 * 如何进行项目的测试
   * 进入项目主目录rails_auth/下运行 
   * `bin/rails test 测试文件夹目录|文件名±：行数`
---
 * 怎样查看路由
   * 进入项目主目录 rails_auth/下运行
   * `rails routes | grep test名字`
---
 * 测试时要注意的小bug
   * 写代码时要注意格式如‘，’后加空格
   * 在进行git提交时使用`Git status`
   * 查看是否多出来一些文件，污染了git项目
   * ps:可能存在缺失文件
---

 * mvc概念
   * view视图
   * models模型
   * controllers控制器






[隐藏内容](file:///Users/qmy/dong/dong/trask/error.txt)

##错误：
```bin/vite出现错误：No such file or directory @ rb_sysopen - log/not_found.log```
  * cd rails_com/test/dummy/node_modules/viter/
  * yarn install
  * cd rails_com/test/dummy/node_modules/postcss-discard-overridden/
  * yarn install

#markdown语法
**加粗**
*倾斜*
> 段落
1. ordered list
2. ordered list
- unordered list
- unordered list
- unordered list
`code`
* ![图片文件](image.jpg)
~~~

{
  "error1": "1"
  "error2": "2"
}
```dad```
~~ termerror ~~ 
~~ : definition~~ 
~~ wait a error note. [^1]~~
~~~[^1]: the is note~~~

|表标题1|表标题2|
|-------|-------|
|内容1|内容2|
|内容3|内容4|

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
~~删除框~~
 - [] 选择框

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



