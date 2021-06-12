こんにちは。benkei-crabです。
趣味でプログラミングを楽しんでいます。
https://scratch.mit.edu/users/benkei_crab/

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
