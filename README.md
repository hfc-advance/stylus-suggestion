# 基于[language-stylus](https://marketplace.visualstudio.com/items?itemName=sysoev.language-stylus)修改

Adds syntax highlighting and code completion to Stylus files in Visual Studio Code.

Syntax was stolen from here: https://github.com/matthojo/language-stylus.

### Features

* Syntax highlighting
* Symbols provider
* Completion for selectors, properties, values, variables, functions etc.
* Color preview
* 支持全局变量提示

### Configuration
```js
{
  // Use ':' as separator between property and value
  "languageStylus.useSeparator": true, // default value
  // Toggle matches for Stylus Builtin Functions on autocomplete
  "languageStylus.useBuiltinFunctions": true, // default value
  // Toggle colors preview
  "editor.colorDecorators": true // default value
  // 用于搜索变量的文件目录
  "languageStylus.files": []
}
```

### TODO
* Tags completion
* SVG properties completion
