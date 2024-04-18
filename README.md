```
yarn create next-app .

Would you like to use TypeScript? No
Would you like to use ESLint? Yes
Would you like to use Tailwind CSS?  Yes
Would you like to use `src/` directory?  Yes
Would you like to use App Router? (recommended) No
Would you like to customize the default import alias (@/*)? No

 yarn add --dev prettier

 前端组件库
 https://web3ui.github.io/web3uikit/?path=/story/1-web3-parse-blockie--custom-seed

 css组件
 //按步骤
https://tailwindcss.com/docs/installation

 yarn add --dev tailwindcss postcss autoprefixer
 yarn tailwindcss init -p

 安装PostCSS Language Support、Tailwind CSS IntelliSense插件

 一直没有前端显示的原因是没有在app.js文件引入主css文件。
 import "../styles/globals.css"


```

```
在ipfs服务器上执行文件
1.yarn build
2.yarn next export(可能出错时在next.config.mjg/js文件中添加“
 .mjs:
  images: {
        unoptimized: true,
    },

.js:
module.exports = {
    images: {
        unoptimized: true
    }
}
 )

3.导出后将out文件夹上传到ipfs上，设置固定-固定在本地节点-导出CID
ipfs://CID
可以在ipfs服务器上运行

在fleek.co上执行
1.需要先把文件上传到github
2.按要求操作
```
