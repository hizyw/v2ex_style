# V2EX自用美化css

## 直接食用：

  `@import "https://cdn.jsdelivr.net/gh/hizyw/v2ex_style@main/wechat.css";`

## 自行食用：

>   编辑wechat.css，Ctrl+C，Ctrl+V

## 可换字体：

  

```
@font-face{font-family:NewFont;font-style:normal;font-display:swap;
src:url(//cdn.jsdelivr.net/gh/hizyw/fonts@master/LXGWZhenKai.woff2) format('woff2')}
* {font-family:NewFont}
```

替换*为下面的字体名称

//cdn.jsdelivr.net/gh/hizyw/web-fonts@master/<font color=red>*<red>.woff2

- LXGWZhenKai.woff2
- LXGWWenKai-Regular.subset.woff2
- HarmonyOS_Sans_SC_Medium.subset.woff2
- AlibabaPuHuiTi-2-65-Medium.subset.woff2
- SourceHanSerifCN-Medium.subset.woff2
