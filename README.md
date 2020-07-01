# 基于[language-stylus](https://marketplace.visualstudio.com/items?itemName=sysoev.language-stylus)修改

![Stylus](assets/icon.png)

[![github-issues](https://img.shields.io/github/issues/d4rkr00t/language-stylus.svg)](https://github.com/d4rkr00t/language-stylus/issues)
[![commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cl)

Adds syntax highlighting and code completion to Stylus files in Visual Studio Code.

Syntax was stolen from here: https://github.com/matthojo/language-stylus.

### Features

* Syntax highlighting
* Symbols provider
* Completion for selectors, properties, values, variables, functions etc.
* Color preview
* 支持全局变量提示

![Completion in Action](assets/completion.gif)

![Symbols Provider in Action](assets/symbols.gif)

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
