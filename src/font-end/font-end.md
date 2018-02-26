# autoprefixer 
[github](https://github.com/postcss/autoprefixer)
---
根据最新的W3C规范，忘记浏览器引擎前缀并编写普通的CSS。你不需要特殊的语言（比如Sass）或者记住你必须使用mixins的地方。由于Autoprefixer是CSS的后处理器，因此您还可以将其与预处理器（如Sass，Stylus或LESS）一起使用
```
a {
    display: flex;
}
```
compiles to:
```
a {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
}
```

