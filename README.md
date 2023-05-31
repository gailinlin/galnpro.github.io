# [Gai Blog](https://jade-caramel-e0bdbd.netlify.app/)

> Start and end.

## [User Manual 👉](_doc/Manual.md)

### Getting Started

1.  You will need [Ruby](https://www.ruby-lang.org/en/) and [Bundler](https://bundler.io/) to use [Jekyll](https://jekyllrb.com/). Following [Using Jekyll with Bundler](https://jekyllrb.com/tutorials/using-jekyll-with-bundler/) to fullfill the enviromental requirement.

2.  Installed dependencies in the `Gemfile`:

``` sh
$ bundle install 
```

3.  Serve the website (`localhost:4000` by default):

``` sh
$ bundle exec jekyll serve  # alternatively, npm start
```

### Development (Build From Source)

To modify the theme, you will need [Grunt](https://gruntjs.com/). There are numbers of tasks you can find in the `Gruntfile.js`, includes minifing JavaScript, compiling `.less` to `.css`, adding banners to keep the Apache 2.0 license intact, watching for changes, etc.

Yes, they were inherited and are extremely old-fashioned. There is no modularization and transpilation, etc.

Critical Jekyll-related code are located in `_include/` and `_layouts/`. Most of them are [Liquid](https://github.com/Shopify/liquid/wiki) templates.

This theme uses the default code syntax highlighter of jekyll, [Rouge](http://rouge.jneen.net/), which is compatible with Pygments theme so just pick any pygments theme css (e.g. from [here](http://jwarby.github.io/jekyll-pygments-themes/languages/javascript.html) and replace the content of `highlight.less`.

### Interesting to know more? Checkout the [full user manual](_doc/Manual.md)!

## Other Resources

Ports - [**Hexo**](https://github.com/Kaijun/hexo-theme-huxblog) by @kaijun - [**React-SSR**](https://github.com/LucasIcarus/huxpro.github.io/tree/ssr) by @LucasIcarus

[Starter/Boilerplate](https://github.com/huxpro/huxblog-boilerplate) - Out of date. Helps wanted for updating it on par with the main repo

Translation - [🇨🇳 中文文档（有点过时）](https://github.com/Huxpro/huxpro.github.io/blob/master/_doc/README.zh.md)

## License

Hux Blog is derived from [Clean Blog Jekyll Theme (MIT License)](https://github.com/BlackrockDigital/startbootstrap-clean-blog-jekyll/) Copyright (c) 2013-2016 Blackrock Digital LLC.

## 最近更新

-   React Native 0.64 with Hermes for iOS · [The RN Show Podcast Ep #5](https://www.callstack.com/podcast-react-native-show) · 2021
-   [Service Worker 101](//huangxuan.me/2016/11/20/sw-101-gdgdf/) · GDG DevFest 北京 2016
-   [Progressive Web App，复兴序章](//huangxuan.me/2016/10/20/pwa-qcon2016/) · [QCon 上海 2016](http://2016.qconshanghai.com/presentation/3111)
-   [CSS Still Sucks 2015](//huangxuan.me/2015/12/28/css-sucks-2015/) · 2015
-   [如何锻炼解决问题的能力](//huangxuan.me/2023/05/26/more-possibility/) · 2023
