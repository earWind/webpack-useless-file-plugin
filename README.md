# webpack-useless-file-plugin

自动找出项目中没有用的文件

```js
 plugins: [
    new UselessFilePlugin({
        root: path.resolve(__dirname, './src'), // 项目目录
        out: './fileList.json', // 输出文件列表
        clean: false, // 是否删除文件
        exclude: /node_modules/ // 排除文件列表
    })
 ]
```
