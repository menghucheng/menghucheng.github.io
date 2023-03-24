~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
A Jekyll port of the Spectral theme by HTML5 UP.
Find the original non-jekyll theme at: http://html5up.net/
Note: @arkadianriver is in no way associated with @n33co
      other than I really like his _style_! get it?
Below is @n33co's readme from the original pure HTML theme
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


Spectral by HTML5 UP
html5up.net | @n33co
Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)


A big, modern, blocky affair with a mobile-style menu, fully responsive styling,
and an assortment of pre-styled elements. So, pretty much what you were expecting
-- except, of course, for how it's put together, specifically:

- It's built on Skel 3*, a leaner, more modular rewrite of my responsive framework.

  (* = still in development as of this writing)

- It uses flexbox*, which eliminates all kinds of terrible hacks and clunky layout
  stopgaps (like CSS grid systems).

  (* = not supported on IE8/9, but non-flexbox fallbacks are included)

- It uses Sass* a lot more intelligently, thanks in part to several new mixins
  and functions I've been working on (as well as a few by @HugoGiraudel).

  (* = still entirely optional if you prefer vanilla CSS :)

- A ton of other stuff.

In short, Spectral's the culmination of several new things I'm working on/trying out,
so please, let me know what you think :)

Demo images* courtesy of Unsplash, a radtastic collection of CC0 (public domain) images
you can use for pretty much whatever.

(* = not included)

AJ
n33.co @n33co dribbble.com/n33


Credits:

	Demo Images:
		Unsplash (unsplash.com)

	Icons:
		Font Awesome (fortawesome.github.com/Font-Awesome)

	Other:
		jQuery (jquery.com)
		html5shiv.js (@afarkas @jdalton @jon_neal @rem)
		background-size polyfill (github.com/louisremi)
		Misc. Sass functions (@HugoGiraudel)
		Respond.js (j.mp/respondjs)
		Skel (skel.io)



### 主题修改分析
1. _includes 定义一些模版，比如通用的header，footer,在_layouts里面的
default.html 被引用，将模版注入生成html。被模板包含的HTML片段，可在_config.yml中修改位置
2. _layout 网页排版模板，存放layout布局信息，在具体页面的配置layout:上引用，然后页面下面的详细内容
会被传为content传入添加道layout中{/{content}/}里面
3. assets 存放css,js,image等，辅助资源 css布局 js脚本 图片等
4. _posts 博客内容
5. _pages 其他需要生成的网页，如About页
6. _data 动态数据
7. _sites 最终生成的静态网页
8. _config.yml 网站的一些配置信息
9. index.html 网站的入口



### 本地启动
- bundle exec jekyll serve
- visit : http://localhost:4000

### Refer
- Liquid Api : https://huang-qing.github.io/github/2017/10/19/GitHub-Jekyll-Liquid-API/
- Jekyll ：https://www.jianshu.com/p/9f71e260925d
- Creating and Hosting a Personal Site on GitHub ： https://jmcglone.com/guides/github-pages/
