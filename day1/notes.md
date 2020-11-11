## 1.初始包管理
关于包管理的总结：
    - 一个文件夹可以称为一个包。
    - 在文件夹(包)中可以创建多个文件。
    - 在同一个包下的每个为文件中必须制定 包名称且相同

重点：关于包的分类
    - main包，如果是main包，则必须写一个main函数，此函数就是项目的入口(main主函数)。编译生成的就是一个可执行的文件。
    - 非main包，用来将代码进行分类，分别放在不同的包和文件中。

## 2.输出
在终端将想要展示的数据显示出来，例如：欢迎登录、请输入用户名等。。。
- 内置函数
    - print
    - println
- fmt包(推荐)
    - fmt.Print
    - fmt.Println
    - fmt.Printf
        - %s，占位符 "文本"
        - %d，占位符 整数
        - %f，占位符 小数(浮点数)
        - %.2f 占位符 小数(保留小数点后2位，四舍五入)
扩展：进程里有stdin/stdout/stderr。

## 3.注释
- 单行注释，//
- 多行注释，/* */

## 4.初始数据类型
- 整型，整数
- 字符串，文本
- 布尔型，真假

## 5.变量
可以理解为昵称
    - 声明+赋值
    ```go
        var str string = "soleil"
    ```
    - 先声明后赋值
    ```go
        var str string
        str = "soleil"
    ```