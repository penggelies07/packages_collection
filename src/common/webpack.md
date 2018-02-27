# extract-text-webpack-plugin
[github](https://github.com/webpack-contrib/extract-text-webpack-plugin)
---
它将*.css输入块中的所有必需模块移动到单独的CSS文件中。所以你的样式不再被内联到JS包中，而是在一个单独的CSS文件（styles.css）中。如果您的样式表总量很大，那么它会更快，因为CSS包与JS包并行加载
```
const ExtractTextPlugin = require('extract-text-webpack-plugin')
```

# html-webpack-plugin
[github](https://github.com/jantimon/html-webpack-plugin)
---
该插件将为您生成一个HTML5文件，其中包含webpack 使用script标记的正文中的所有包。并添加引入到该html文件

# uglifyjs-webpack-plugin
[github](https://github.com/webpack-contrib/uglifyjs-webpack-plugin)
---
这个插件使用UglifyJS v3 (`uglify-es`)来缩小你的JavaScript
