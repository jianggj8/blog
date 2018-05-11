# jianggj

A simple two-column jekyll theme delicated to wrting.


## Preview

#### Desktop
![](/images/desktop.png)

#### Mobile
![](https://i.loli.net/2018/05/11/5af5442510981.jpg)

## Features

1. pagination
2. comments
3. google analytics

## Install

1. create a repository named "username.github.io"
2. fork this reporsity to repo in step1, you should see the blog at 'http://username.github.io'
3. configure more below

Similar process with detailed page with gif can be seen [here](https://github.com/barryclark/jekyll-now/blob/master/README.md)


## Configure

In `_config.yml` file

```
title: xxxx   # your title
author: xxxx # your name
description: Just have some fun here # your description
avatar: /images/avatar.png # change avatar

```

You can uncomment to set disqus and google analytics.

```
# Comments
# disqus:
#   shortname: xxxx-xxxxx-xxx   # your disqus shortname

# Google Analytics
# google_analytics: xx-xxxxxxxx-1  # your google analytics
```

If you want to do any customization, take a look at the code, I've tried to make it as simple as possible. 

## Writing Blogs

Now you're all set, write articles and add to _posts folder, remember to name it as 'yyyy-mm-dd-your-article-title.md' and always add these lines to the begining your blog file.

```
---
layout: post 
---
```


## Thanks

[Farbtle](https://github.com/YCF/Farbtle) from [YCF](https://github.com/YCF), I steal a lot from him.
