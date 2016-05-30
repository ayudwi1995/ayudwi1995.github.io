---
layout: post
title: "Tentang saya di UIN SUSKA"
author: ayudwi1995
modified:
excerpt: "Saya seorang mahasiswa semester 6 jurusan sistem informasi di fakultas Sains dan Teknologi."
tags: []
---

For those of you who may have content written by multiple authors on your site you can now assign different authors to each post if desired.

Previously the theme used a global author for the entire site and those attributes would be used in all bylines, social networking links, Twitter Card attribution, and Google Authorship. These `owner` variables were defined in `config.yml`

Start by modifying or creating a new `authors.yml` file in the `_data` folder and add your authors using the following format.

{% highlight yaml %}
# Authors

billy_rick:
  name: Ayu Dwi Septiana
  web: 
  email: ayuarta1995@gmail.com
  bio: "Love your self"
  avatar: bio-photo-2.jpg
  twitter: ayudwi95
  google:
    plus: vlorybieber16

cornelius_fiddlebone:
  name: Cornelius Fiddlebone
  email: cornelius@thewhip.com
  bio: "I ordered what?"
  avatar: bio-photo.jpg
  twitter: rhymeswithsackit
  google:
    plus: CorneliusFiddlebone
{% endhighlight %}

To assign Billy Rick as an author for our post. You'd add the following YAML front matter to a post:

{% highlight yaml %}
author: billy_rick
{% endhighlight %}
