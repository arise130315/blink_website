# blinkwork.cn 官网源文件

Blink 官方网站的静态源文件。线上地址:https://blinkwork.cn

> 纯静态站,没有构建步骤。所有样式和脚本都内联或同目录,直接用浏览器打开 `index.html` 即可预览。

---

## 文件

| 文件 | 说明 |
|---|---|
| `index.html` | 首页 |
| `download.html` | 下载页 |
| `privacy.html` | 隐私政策 |
| `assets/home-preview.png` | 首页产品截图(2160×1440) |
| `hero.jpg` | 首屏背景兜底海报 |
| `bg-base64.js` | 背景图数据 |
| `three.min.js` | 首页水波背景所用的 three.js |

## 部署

把上述文件原样放到 Web 服务器的站点目录即可,无需编译。

## 注意

源文件在 Blink 应用的项目工作区里编辑,同步到本仓库时**只带页面文件**——工作区里还有内部记录文件,不应进入公开仓库。`.gitignore` 已对此做了兜底。

## 许可

站点内容 © 2026 Blink。
