## 说明

这是 onedrive 云盘程序[OneManager](https://github.com/qkqpttgf/OneManager-php)的一个 CSS 美化 主题。

## 使用

- OneManager 程序已内置本主题，后台启用 onemoe 主题即可。

- 本主题可以自定义背景渐近色，在后台 customStyle 添加下面的代码即可，代码中的渐近色可以自行替换。

```css
body {
  background-color: #8ec5fc;
  background-image: linear-gradient(62deg, #8ec5fc 0%, #e0c3fc 100%);
}
```

> 什么？你不会渐近色代码？放心，我也不会，只需要从类似下面的一些渐近色配色网站 copy css 然后粘贴过来即可。  
> 配色网站 1：https://www.grabient.com/  
> 配色网站 2：https://gradient.shapefactory.co/

- 隐藏语言选项和全部下载按钮的方法：在 customStyle 中添加以下内容。

```css
.file button {
  display: none;
}
.changelanguage {
  display: none;
}
```

- 更多细节请访问 [我的博客](https://www.2bboy.com/archives/154.html)。

## 预览

> [在线预览](https://pan.2bboy.com/Public)

![](./preview/screen1.png)

![](./preview/phone1.png)

![](./preview/screen2.png)

![](./preview/screen3.png)

![](./preview/screen4.png)

![](./preview/phone2.png)
