# Windows

## 常见浏览器对 Windows 系统的支持情况

### IE & Edge

- Windows XP 最高可升级到 IE 8
- Windows Vista 最高可升级到 IE 9
- Windows 7/8/8.1 最高可升级到 IE 11
- Windows 10 Microsoft Edge

### 谷歌浏览器内嵌框架（Google Chrome Frame）

Google Chrome Frame 是 Google 推出的一款 IE 插件，可以让 IE 浏览器使用 Chrome 的内核进行渲染，支持 IE 6/7/8/9。

2014年，Google Chrome Frame 发布了最后一个版本，版本号为 32。

注：Chrome Frame 插件虽然可以让 IE 支持 Chrome 浏览器特性，但并不保证所有功能可用。
比如 `<a>` 的 `download` 属性，虽然 Chrome Frame 支持（`'download' in document.createElement('a')` 为 `true`），但是触发点击事件后不会下载文件。

#### 相关链接

- [Rendering HTML5 in older browsers with Google Chrome Frame](https://webplatform.github.io/docs/tutorials/google_chrome_frame/)

### Google Chrome

- Chrome 支持 Windows 10/8.1/8/7

### Mozilla Firefox

- Firefox 支持 Windows 10/8.1/8/7

## 开源项目、网站对浏览器的支持情况

- 2015 年 8 月 19 日，Bootstrap 4.0 Alpha 放弃对 IE8 的支持。  
- 2016 年 1 月 12 日，**微软放弃对 IE8/IE9/IE10 的支持**。  
- 2016 年 1 月 14 日，jQuery 3.0 Beta 放弃对 IE8 的支持。  
- 2016 年 4 月 13 日，淘宝和天猫停止对 IE6/IE7 的支持。  

## IE & Edge 对 Web 标准的支持情况

- HTML4: IE6 开始支持
- CSS2.1: IE6 开始支持
- ES3: IE6 开始支持
- HTML5: IE9 开始支持
- CSS3: IE9 开始支持
- ES5: IE9 开始支持
- ES2015: MS Edge 开始支持  

IE8 之前的 IE 版本和 W3C 标准实现不一致，即怪异模式（Quirks Mode）和标准模式（Standards Mode）。
从 IE8 开始，IE 会默认使用标准模式渲染页面，同时支持用户使用兼容性视图（在兼容性视图中显示 Intranet 站点），来打开那些仅能在 IE6/7 中正常显示的页面。

正常的 `userAgent`:

- `Mozilla/5.0 (Windows NT 10.0; WOW64; Trident/7.0; rv:11.0) like Gecko`
- `Mozilla/5.0 (Windows NT 10.0; WOW64; Trident/7.0; .NET4.0C; .NET4.0E; InfoPath.3; .NET CLR 2.0.50727; .NET CLR 3.0.30729; .NET CLR 3.5.30729; rv:11.0) like Gecko`

兼容模式下的 `userAgent`:

- `Mozilla/4.0 (compatible; MSIE 7.0; Windows NT 10.0; WOW64; Trident/7.0; .NET4.0C; .NET4.0E; InfoPath.3; .NET CLR 2.0.50727; .NET CLR 3.0.30729; .NET CLR 3.5.30729)`

## IE & Edge 版本历史

- IE6，2001 年发布（伴随 Windows XP 发行）  
- IE7，2007 年发布（伴随 Windows Vista 发行）  
- IE8，2008 年发布（支持 Windows 7、Windows Vista 和 Windows XP），同年 Chrome 开始公测  
- IE9，2011 年发布（支持 Windows 7 和 Windows Vista）  
- IE10，2012 年发布（伴随 Windows 8 发行，支持 Windows 7）  
- IE11，2013 年发布（伴随 Windows 8.1 发行，支持 Windows 10、Windows 8 和 Windows 7），最后一版 IE  
- Microsoft Edge，2015 年发布（伴随 Windows 10 发行）  
