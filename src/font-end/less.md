# less-plugin-functions
[github](https://github.com/seven-phases-max/less-plugin-functions)
---
可以直接在Less本身定义自定义函数，并像常规的内置函数一样使用它们
---
Define foo function:
```
.function {
    .foo(@x) {
        return: @x * 2;
    }
}
```
Use it:
```
div {
    width: foo(21em); // -> 42em
}
```

