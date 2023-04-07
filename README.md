# webpack-useless-file-plugin

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
