# css控制边框与背景

## *边框

1. 我们用class，即类选择器来做示范(写在style里！文档内嵌样式表！)

2. ```css
   .class1{
       border-width:5px;
       border-color: red;
       border-style: *****;
       border-top-style: ;
       //最后一行是一个示范，当你只想改变某一个上下左右的边框时，可以这样子写，颜色、宽度、样式
   }
   ```

3. 可以简写

```
.class1{
    border:5px（宽度） solid（样式） red（颜色） ；
    border-top:同上，修改某一方向
    border-radius:20px/15px 设置圆角边框，第一个参数是距离左右边距离，第二个是上下距离，即可以是椭圆而不一定是圆形
}
```



## *背景

1. 我们用class，即类选择器来做示范(写在style里！文档内嵌样式表！)

2. ```css
   .class1{
       width: 50px;
       height: 80px;
       background-color：#123456;
       background-image: url（E:\\TEST.JPG);
       background-repeat:no-repeat;
       		//背景重复方式。当你不设置时，随着你手动拖动页面的大小，图片会以复制粘贴多个的形					//式填充整个网页
       backgroung-size:***;
       		//auto时同上默认，cover时是以缩放方式填充
       background-attachment:fixed;
       		//保持图片不随滚动而移动位置，保持在显示器的同一位置
   }
   ```

3. 
