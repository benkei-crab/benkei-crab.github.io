---
layout: home
---

Scratchでプログラミングを楽しもう!
本ページでは簡単なプログラムを作りながらScratchを紹介します。主に、「音楽」や「ペン」拡張機能を使ったプログラムを予定しています。ご興味ある方はお付き合いください。



こんにちは。benkei-crabです。
私のScratch作品は[こちら]
(https://scratch.mit.edu/users/benkei_crab/)


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
