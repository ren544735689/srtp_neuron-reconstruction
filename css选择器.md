# css选择器

首先，你需要新建一个.css文件，包含以下内容

```css
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>mycss</title>
    <style type="text/css">
		<!-- 使用文档内嵌样式表 -->
		
    </style>
</head>
<body>

</body>
```

## 使用css基本选择器

1. 选择所有元素

   - 将2中方法的a改为*即为全选，或者使用文档外嵌样式表

2. 根据类型选择元素

   - 类型包括<a><p><h1>等等，

   - 使用方法：在style中加入

     ```css
     a{
     frot-size: 40px;//字的大小
     color: #345fff;
     }
     将a改为p、h1等即可选择对应类型
     ```

3. 根据类选择元素

   - 在类型标签中加一个属性class

   - 使用方法：在style中加入

     ```css
     .class1{
     }
     然后对应的类型增加属性：<a class="class1"></a>
     ```

4. 根据ID选择元素

   - 在标签中加一个id属性
   - 使用方法：#id1
   - 注意：id为一个特有的属性，最好不要设重复，id与class同时定义时，id优先级更高

5. 根据属性选择元素

   - 标签中有属性的可以以属性进行加工

   - 使用方法：[]

     ```css
     [herf]{
         ...
     }
     <a herf="test.html">this is a herf</a>
     ```

   - []中的属性若只想对该属性某一特定值加工时，可加赋值语句。eg：[herd="test.html"]

6. 其他选择器

## ：选择器(动作选择器)

```
a{
font-size: 40px
color: blue;
}
a:hover{
font-size: 80px
color: #132456;
}
```

这时，我们对a标签加了一个动作，hover表示鼠标经过该处时触发。