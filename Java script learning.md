# Java script learning

- 解释型语言
- 类似c和java的语法结构
- 动态语言
- 基于原型的面向对象

> html 模板

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />
    <meta name="renderer" content="webkit" />
    <title>Document</title>
<!--[if lt IE 9]>
    <script src="//cdn.staticfile.org/html5shiv/r29/html5.min.js"></script>
    <script src="//cdn.staticfile.org/respond.js/1.4.2/respond.min.js"></script>
    <script src="//cdn.staticfile.org/es5-shim/4.5.9/es5-shim.min.js"></script>
    <script src="//cdn.staticfile.org/es5-shim/4.5.9/es5-sham.min.js"></script>
<![endif]-->
    <link rel="stylesheet" href="//cdn.staticfile.org/normalize/6.0.0/normalize.min.css">
</head>
<body>
</body>
</html>
```

- script 标签一旦用于引入外部文件，就不能在编写代码了。

- 注意

  - JS中严格区分大小写

  - 在js中使用var关键字来声明一个变量

    - ``` js 
      var a = 123
      ```



- 标识符

  - 标识符不能以数字开头
  - 标识符不能以es中的关键字

- 数据类型(6种)

  - String

    - 双/单引号引起来

      - ```js
        var str = "hello"
        ```

      - 转义符：斜杠

      - ![image-20220708114202860](C:\Users\Xinwei\AppData\Roaming\Typora\typora-user-images\image-20220708114202860.png)

  - Number

    - typeof a (检查a变量的数据类型)
      - Number.MAX_VALUE

  - Boolean

  - Null 

    - 使用type of 返回 object

    - ```js
      var a;
      ```

  - Undefined

  - Object (引用数据类型)

- 