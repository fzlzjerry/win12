# 翻译贡献指南
暂时只需英语，其他语言待完善后再吧。

## 条件
1. 有中文基础
2. 有一定的所要翻译的语言的基础
3. 有代码基础
## 方法
项目使用 i18n 库实现多语言，可上网查阅，或自行研究已有翻译的部分

### 已有成果
0. 务必理解 `desktop.js` 开头语言处理部分，熟悉原理
1. 此目录下 `trans.py`，有 Python 基础者自行研究
2. `desktop.js` 中有 `lang(txt,id)`，详见注释

### 注意
部分代码形如
```html
<a class="btn">
    <i class="bi"></i> 文本
</a>
```
可能不便于设置属性，可对纯文本部分添加 `<span>` 标签，例可改为

```html
<a class="btn">
    <i class="bi"></i>
    <span data-i18n="sth">Text</span>
</a>
```

## 酬劳
有且仅有 Github 贡献点