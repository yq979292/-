## bable入门文档

官方地址 [ babel文档链接地址](https://www.babeljs.cn/docs/usage)

##### babel是什么？

Babel 是一个工具链，主要用于将 ECMAScript 2015+ 版本的代码转换为向后兼容的 JavaScript 语法

下面列出的是 Babel 能为你做的事情：

- 语法转换
- 通过 Polyfill 方式在目标环境中添加缺失的特性 (通过 [@babel/polyfill](https://www.babeljs.cn/docs/babel-polyfill) 模块)
- 源码转换 (codemods)
- 更多！ (查看这些 [视频](https://www.babeljs.cn/videos.html) 获得启发)

以下为babel 可以转移的内容：

- Babel 能够转换 JSX 语法！查看 [React preset](https://www.babeljs.cn/docs/babel-preset-react) 了解更多信息
- Babel 可以删除类型注释！查看 [Flow preset](https://www.babeljs.cn/docs/babel-preset-flow) 或 [TypeScript preset](https://www.babeljs.cn/docs/babel-preset-typescript) 了解如何使用。务必牢记 **Babel 不做类型检查**，你仍然需要安装 Flow 或 TypeScript 来执行类型检查的工作。
- 可以 将es5 以上版本内容转化为es5

### ES5 以及其他版本

Babel 通过语法转换器来支持新版本的 JavaScript 语法。

入门可以查看 [使用指南](https://www.babeljs.cn/docs/usage)