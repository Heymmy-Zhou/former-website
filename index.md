---
layout: default
---

# 黑米粥工作室

---

**注意：本页面已停止更新。**  

---

## 我们是谁 | Who are we
黑米粥工作室（Heymmy-Zhou Studio）位于中国大陆，是一家以开发、设计为主的非盈利工作室。  
查看我们的[联系方式](#%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F--contact-us)

## 我们的产品 | Our Products

#### [圆计算](https://github.com/ZhouJiatai/CircleCal)
> 为方便大家计算有关圆的数据，告别复杂的圆周率计算，黑米粥工作室特推出圆计算程序，解决大家的圆计算难题。

#### [2048](https://github.com/ZhouJiatai/2048)
> 黑米粥工作室出品的 2048 PC端游戏正式上线啦！
该游戏支持经典的 2048 游戏玩法，一改 DOS 默认界面，游戏更出彩！

#### [加法器](https://github.com/ZhouJiatai/adder)
> 采用 HTML+JavaScript 编写，供大家学习观摩。

## 博客 | Blog
**请注意：如无特殊说明，本网页下的所有博文均采用【[知识共享 署名-非商业性使用-相同方式共享 4.0 国际 (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh)】许可协议授权**

### 为什么 github.io 域名无法打开？
**2020-07-22 08:36:20 星期三**  

现在网络上，使用 <a href="https://github.io" target="_blank">GitHub Pages</a> 创建个人主页的可谓是越来越多了。它完全免费，可惜服务器似乎有时会被“墙”。但还有一种情况，明明服务器正常，可是仍然无法打开网页。比如，大家试着打开这个网页：<a href="http://winpython.github.io/" target="_blank">http://winpython.github.io/</a>，网页多半会提示：
> **嗯… 无法访问此页面**  
已重置连接。
请尝试:
> - 正在检查连接
> - 检查代理和防火墙
> - 运行 Windows 网络诊断  
> ERR_CONNECTION_RESET

如果你的浏览器没有提示，那可要恭喜了，说明你的浏览器自动纠错功能启动了，把http改成了https。但是，对于那些出现了这种状况的，又该怎么办呢？网络上的方法没几个有用，几经试验，我终于误打误撞地找到了解决方案：在网址前加上或把 ***http://*** 改成 ***https://*** 就可以了。这是为什么呢？我查阅了GitHub的<a href="https://docs.github.com/cn/github/working-with-github-pages/securing-your-github-pages-site-with-https" target="_blank">官方文档</a>，发现里面有这样一段话：
> 对于使用 2016 年 1 月 15 日后创建的 github.io 域的 GitHub Pages 站点，需要**强制**实施 HTTPS。 如果您在 2016 年 6 月 15 日之前创建了站点，则可以手动启用实施 HTTPS。

也就是说，GitHub必须让我们用HTTPS！我又查看了我的个人网页存储库设置，发现里面也有：
> - [x] Enforce HTTPS  
— Required for your site because you are using the default domain (heymmy-zhou.github.io)  
HTTPS provides a layer of encryption that prevents others from snooping on or tampering with traffic to your site.  
When HTTPS is enforced, your site will only be served over HTTPS. Learn more.

最前面那个勾是无法取消的。翻译过来，大致就是：
> - [x] 强制 HTTPS  
—您的站点需要，因为您使用的是默认域名（heymmy-zhou.github.io)  
HTTPS提供了一个加密层，防止其他人窥探或篡改您站点的流量。  
当HTTPS被强制执行时，您的站点将只通过HTTPS提供服务。了解更多。

所以，呜呜呜呜……既然GitHub抢制执行，我们也只好跟着干吧……

### 优秀图片编辑软件——paint.net 推荐
**2020-07-20 19:58:02 星期一**

不知道大家是否会有这样的感觉：
> 选个图片编辑软件太难了！
- **画图**，功能就那么几个；
- **PS**，根本买不起；
- **GIMP**，简直不是给 Windows 用的……

本人也会有这样的烦恼……一次偶然的机会，我看到了[MDN](https://developer.mozilla.org/zh-CN/)（注意不是MSDN）上的[优秀软件推荐](https://developer.mozilla.org/zh-CN/docs/Learn/Getting_started_with_the_web/Installing_basic_software)，才豁然开朗：
> 图像编辑器，像 GIMP、Paint.NET、Photoshop 或者 XD，用来编辑网页中的图形图像。

Photoshop的名气不必说了，那可是响当当的；GIMP倒也小有名气，被誉为“Linux下的PS”；至于XD，虽说是Adobe少有的良心免费软件，但还是略显生疏。而这里，居然把一个我从来没听说过的Paint.NET跟它们相提并论！这个Paint.NET究竟是何方神圣呢？于是，我进入它的官网<https://www.getpaint.net/>，来一探究竟。

具体的请大家自己去实验，我也不多说了。经过一番摸索，我终于找到了它的下载页面：<https://www.dotpdn.com/downloads/pdn.html>
不要担心，它是有简体中文的（要是安装后不是，那么启动后点击右上角的小齿轮（设置）-》Language-》中文（中国）-》重启即可）。
打开软件，我怀疑这是否是一个简化的PS——甚至许多快捷键都一模一样。可惜文字工具过为简单，没有高级特效（滤镜），没有高级颜色调整。图层、历史记录、基础工具这些都在。作为一个免费软件的它已经不错了，完全可以应付日常，另外，它设计出来本来就是为了代替“画图”软件……

总体来看，Paint.NET的初体验还是挺让人满意的，有空下次再深入探究。

## 联系方式 | Contact Us
- GitHub：<a href="https://github.com/Heymmy-Zhou" target="_blank">@Heymmy-Zhou</a>

------------

Copyright © 2020 - 2021 黑米粥工作室  
**请注意：如无特殊说明，本网页下的所有博文均采用【[CC BY-NC-SA 3.0 CN](https://creativecommons.org/licenses/by-nc-sa/3.0/cn)】许可协议授权**
