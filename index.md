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

    <div class="index-content blog">
    <div class="section">
        <ul class="artical-cate">
            <li class="on"><a href="/"><span>Blog</span></a></li>
            <li style="text-align:center"><a href="/dump"><span>Project</span></a></li>
            <li style="text-align:right"><a href="/project"><span>About</span></a></li>
        </ul>

        <div class="cate-bar"><span id="cateBar"></span></div>

        <ul class="artical-list">
        {% for post in site.categories.blog %}
            <li>
                <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
                <div class="title-desc">{{ post.description }}</div>
            </li>
        {% endfor %}
        </ul>
    </div>
    <div class="aside">
    </div>
    </div>
  </div>
</body>
