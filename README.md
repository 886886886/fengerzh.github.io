# 日新亭模板

日新亭模板是一套基于`Jekyll`框架的模板，目前运行在[日新亭](https://www.fengerzh.com)网站上。日新亭网站基于[Github Pages](https://pages.github.com/)自动发布，`https`技术采用[CloudFlare](http://cloudflare.com/)方案，图床采用[Cloudinary](https://cloudinary.com/)自动压缩方案。

此模板的基础是[Jekflix](https://github.com/thiagorossener/jekflix-template)，在此基础上做了大量定制改造，包括添加`Google`渐进式Web应用(`Progressive Web Apps`)功能等，以使其更加适合中文环境和对移动端友好。

所有文章的`Markdown`源代码在`_posts`文件夹之下，供参考。如果利用此模板建设自己的网站，可以直接删除`_posts`下的所有文件。

此模板还在持续更新中，随时添加新的功能和新的内容。

## 下载

可直接通过`Github`下载本模板：

```
git clone git@github.com:fengerzh/fengerzh.github.io.git
```

## 安装

### 安装Jekyll

```
brew install ruby
gem install bundler
gem install jekyll
```

## 运行

```
bundle exec jekyll serve
```
