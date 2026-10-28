# Cheng Su — Personal Website

Website: https://back2-thebasic.github.io/

A static academic homepage based on [Jon Barron’s website template](https://github.com/jonbarron/jonbarron.github.io).

## 修改网站

- `index.html`：姓名、个人介绍、研究兴趣、链接和页面样式。
- `assets/img/`：头像、favicon 等图片。当前 favicon 为 `usc-seal.svg`。
- `.github/workflows/deploy.yml`：自动发布流程。

修改后提交到 `main`。GitHub Actions 会把网站发布到 `gh-pages` 分支，GitHub Pages 随后自动更新。

## 本地预览

在仓库根目录运行：

```sh
python3 -m http.server 8000
```

然后打开 http://localhost:8000/。

## 图片来源

USC 校徽 SVG 来自 [Wikimedia Commons](<https://commons.wikimedia.org/wiki/File:University_of_Southern_California_(USC)_seal.svg>)。

旧 al-folio 模板已从当前版本移除，仍可从 Git 提交历史恢复。
