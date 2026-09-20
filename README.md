# Magic Sorting Quiz

一个适合手机端使用的魔法学院分院测试静态网页。用户需要先输入提取码，随后可完成 18 道情境题并查看学院结果与人格档案。

## 本地打开

直接双击 `index.html` 即可在浏览器中运行。为了获得与 GitHub Pages 更一致的效果，也可以使用任意静态文件服务器打开项目目录。

## 修改提取码

打开 `index.html`，找到脚本开头的 `ACCESS_CODES` 数组：

```js
const ACCESS_CODES = [
  "MAGIC0920"
];
```

在数组中增加或修改字符串即可。提取码验证不区分大小写；验证状态只保存在当前浏览器标签页的会话中。

## 部署到 GitHub Pages

1. 将本项目推送到 GitHub 的公开仓库。
2. 打开仓库的 **Settings** → **Pages**。
3. 在 **Build and deployment** 中将 **Source** 设为 **Deploy from a branch**。
4. 将分支设为 **main**，目录设为 **/ (root)**，然后点击 **Save**。
5. 等待部署完成后，在同一页面查看正式网址。

本项目是纯静态网页，不需要 Node.js、npm 或构建步骤。
