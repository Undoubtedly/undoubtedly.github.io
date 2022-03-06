---
layout: page
title: 소개
image: 'http://24.media.tumblr.com/90c89b46856381850d8c90509a023320/tumblr_mq3m2bYU7V1su3s6uo1_1280.gif'
---

# 제목에 대한 간단한 기본 스타일
## 제목에 대한 간단한 기본 스타일
### 제목에 대한 간단한 기본 스타일
#### 제목에 대한 간단한 기본 스타일
##### 제목에 대한 간단한 기본 스타일
###### 제목에 대한 간단한 기본 스타일

***

* 그냥 그래
* 그냥 그래
* 그냥 그래

***

1. 그냥 그래
2. 그냥 그래
3. 그냥 그래

***

> 디자인은 개성, 기이함, 이단, 이상, 취미, 유머의 천국입니다. — 황원영

***

    'use strict';
    var markdown = require('markdown').markdown;
    function Editor(input, preview) {   
    this.update = function() {
        preview.innerHTML = markdown.toHTML(input.value);
    };
    input.editor = this;
    this.update();
    }

***

<script src="https://gist.github.com/ahmadajmi/dbb4f713317721668bcbc39420562afc.js"></script>

***

<iframe width="560" height="315" src="https://www.youtube.com/embed/NF2HpikZGz4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

***

<iframe width="100%" height="300" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/678838419&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe><div style="font-size: 10px; color: #cccccc;line-break: anywhere;word-break: normal;overflow: hidden;white-space: nowrap;text-overflow: ellipsis; font-family: Interstate,Lucida Grande,Lucida Sans Unicode,Lucida Sans,Garuda,Verdana,Tahoma,sans-serif;font-weight: 100;"><a href="https://soundcloud.com/droeloemusic" title="DROELOE" target="_blank" style="color: #cccccc; text-decoration: none;">DROELOE</a> · <a href="https://soundcloud.com/droeloemusic/written-maze-feat-iris-penning" title="Written Maze (feat. Iris Penning)" target="_blank" style="color: #cccccc; text-decoration: none;">Written Maze (feat. Iris Penning)</a></div>

***

<iframe height="300" style="width: 100%;" scrolling="no" title="The Last Experience" src="https://codepen.io/ge1doot/embed/LZdOwj?default-tab=html%2Cresult" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href="https://codepen.io/ge1doot/pen/LZdOwj">
  The Last Experience</a> by Gerard Ferrandez (<a href="https://codepen.io/ge1doot">@ge1doot</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>

***

![DROELOE](https://droeloe.com/wp-content/uploads/cropped-DR_2019_PRESSPIC-scaled-1.jpg)

***

<input type="text" placeholder="입력 필드">

***

<button class="c-btn c-btn--small">버튼</button>

<button class="c-btn">버튼</button>

<button class="c-btn c-btn--full">버튼</button>

***