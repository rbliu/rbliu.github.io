---
layout: default
---

<body>
  <div class="index-wrapper">
    <div class="aside">
      <div class="info-card">
        <h1>Robert Liu</h1>
        <h2>Brown University</h2>
        <a href="http://weibo.com/byliu" target="_blank"><img src="http://www.weibo.com/favicon.ico" alt="" width="25"/></a>
        <a href="https://github.com/rbliu" target="_blank"><img src="https://github.com/favicon.ico" alt="" width="25"/></a>
        <a href="https://www.zhihu.com/people/byliu1990" target="_blank"><img src="https://www.zhihu.com/favicon.ico" alt="" width="25"/></a>
      </div>
      <div id="particles-js"></div>
    </div>

    <div class="index-content">
      <ul class="artical-list">
        {% for post in site.categories.blog %}
        <li>
          <a href="{{ post.url }}" class="title">{{ post.title }}</a>
          <div class="title-desc">{{ post.description }}</div>
        </li>
        {% endfor %}
      </ul>
    </div>
  </div>
</body>
