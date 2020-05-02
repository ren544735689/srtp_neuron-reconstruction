# css过渡

写在style里

```css
p{
    width:100px;
    height:100px;
    background-color: antiqurwhite;
}
p:hover{
    //鼠标移动至时触发
    width:200px;
    height:200px;
    transition-delay:150ms;//动画延迟时间
    transition-durantion:500ms;//动画持续时间
    transition-property：width或background-color;
    		//放进去的属性才会慢慢变化，其余的属性会瞬间变化
    transition-timing-function: linear;
    		//设置f(t)模型
    		//linear为默认
    		//ease-in（开始变化慢，后面变化快，淡入）
    		//ease-out（开始变化快，后面变化慢，淡出）
    		//ease-in-out（淡入淡出）
}
```

# css动画

```css
p:hover{
	animation-duration: 500ms;
    animation-delay: 500ms;
    animation-name: test1;
    animation-iteration-count: infinite 或 数字123;
    	//动画重复
    animation-direction：alternate；
    	//正方向动画-反方向动画-***-***-。。。
}
@keyframes test1{
    from{
        
    }
    50%{
    }
    75%{
    }
    to{
        width: 200px;
        height: 200px;
        background-color: ;
    }
}
```

