---
layout: single
title: "Welcome to the Web Mining Lab!"
paginate: true
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/unsplash-image-11.jpg
  cta_label: "Read More"
  cta_url: "/about/"
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "We’re a social science research lab of a modest size, housed inside the Department of Media and Communication, City University of Hong Kong. We started in 2000 as a survey project on use of the Internet (i.e., Web 1.0) in Hong Kong and mainland China and have since 2005 evolved into social media (Web 2.0) involving interdisciplinary collaboration. We welcome new collaboration in data sharing, joint projects, exchange visits, and etc."
author_profile: true
---

{% include toc title="Table" icon="file-text" %}


[Mine the web, mine the mind 🧬]({{ "/" | absolute_url }}){: .btn .btn--success .btn--large}

## Welcome to the Web Mining Lab!

We’re a social science research lab of a modest size, housed inside the Department of Media and Communication, City University of Hong Kong.
We started in 2000 as a survey project on use of the Internet (i.e., Web 1.0) in Hong Kong and mainland China and have since 2005 evolved into social media (Web 2.0) involving interdisciplinary collaboration. We welcome new collaboration in data sharing, joint projects, exchange visits, and etc.


![gif](https://webmininglab.github.io/assets/gif.gif)

## Members

<table style="table-layout: auto; width: 450px">
  <tr>
     <td style="text-align: center; vertical-align: middle; padding:10px">
        <div>
            <img src="https://webmininglab.github.io/assets/images/jzhu.png" width = 100px><br>
            <a href="https://webmininglab.github.io/">Jonathan ZHU</a><br>
            Professor
        </div>
    </td>

  </tr>
  
  <tr>
    <td style="text-align: center; vertical-align: middle; padding:10px">
        <div>
            <img src="https://chengjun.github.io/authors/admin/avatar_hucdc0c36df1d51621c381efb87a23e0c7_43703_270x270_fill_q75_lanczos_center.jpg" width = 100px height = 100px><br>
            <a href="http://chengjun.github.io/">Cheng-Jun Wang</a><br>
            Professor
        </div>
    </td>
    <td style="text-align: center; vertical-align: middle; padding:10px">
        <div>
            <img src="https://zhouyixin.xyz/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F7ea1fe81-6cef-4dac-952c-3807fe426b98%2FIMG_1196_.jpg?table=block&id=3cb2fb58-19e4-4d51-be13-fc8b6089b258&spaceId=949b0961-e586-4e70-926a-3778ff946257&width=250&userId=&cache=v2" width = 100px height = 100px><br>
            <a href="https://zhouyixin.xyz/">Yixin Zhou</a><br>
            Associate Professor
        </div>
    </td>
  </tr>
  

  
</table>


## Latest News

<ul>
{% for post in site.posts limit:10 %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <small>{{ post.date | date: "%Y-%m-%d" }}</small>
  </li>
{% endfor %}
</ul>

## Contact US

Dept. of Media & Communication
City University of Hong Kong
18 Tat Chee Avenue, Kowloon, Hong Kong S. A. R.

Email: weblabcityu [at] gmail.com

[🔥 Kindling the fire in your heart!](https://github.com/webmininglab/webmininglab.github.io/edit/master/_pages/home.md)
