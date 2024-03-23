# magick.css
> 神奇的可玩性，但简单的样式。全部在一个文件中。

<br>
<img alt="一个巫师" src="../wizard.webp" width="240" height="240">

## 什么是magick.css？
magick.css是一个极简主义的，（主要）无类CSS框架，设计得易于使用和理解。它包含在一个文件中，每一个选择都有注释。目标是实现优雅，但神奇的嬉戏外观，同时最大化可读性和传达信息的能力；*有点像巫师的笔记*。

该框架在所有设备和屏幕尺寸上保持其美观和功能，并完全不需要JavaScript。它受到[LaTeX](https://www.latex-project.org/)，旧学校TTRPG规则书，CSS框架如[concrete.css](https://concrete.style/)和[Tufte CSS](https://edwardtufte.github.io/tufte-css/)以及"可用性作为设计"的残酷主义的启发。

## 它看起来像什么？
你可以在我的[网站](https://css.winterveil.net)上找到一个使用magick.css的实例！

> 点击网站上的语言图标切换为中文

## 我如何使用magick.css？
> magick.css是用[normalize.css](https://necolas.github.io/normalize.css/)构建的。虽然没有它看起来也有90%的正确，但建议使用normalize.css。

### CDN
检查magick.css是否适合你的项目的最简单方法是从CDN添加它。只需将这两行添加到你的html `<head>`：

```html
<link rel="stylesheet" href="https://unpkg.com/normalize.css">
<link rel="stylesheet" href="https://unpkg.com/magick.css">
```

### 本地文件
你也可以直接从这个仓库下载`magick.css`文件，并像你通常那样将它包含到你的html `<head>`中：

```html
<link rel="stylesheet" href="path/to/magick.css">
```

### JS/NPM
你也可以像这样将`magick.css`添加到你的JS项目中:

```bash
npm install normalize.css magick.css
```

然后在你的代码中导入它们：
```js
import 'normalize.css'
import 'magick.css'
```

