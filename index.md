---
# YAML Front Matter

layout: default 

---


<div class="container">
    <header class="blog-header py-3">
    <div class="row">
    <div class="col-3 pt-1"></div>
    <div class="col-6 text-center">
        <p class="h3">minecraft開発日誌</p>
    </div>
    <div class="col-3"></div>
    </div>
    </header>

<div class="jumbotron p-4 p-md-5 text-white rounded bg-dark">
    <div class="col-md-8 px-0">
    <h4>Minecraft関係はのんびりここに書いていく</h4>
    <h5>
    spigot関係も含めてGCPのことも追記していく予定<br>
    <small>
    ※当サーバーは広告費で運営しております。<br>
    一人一人の広告クリックで成り立っています。<br>  
    一日一クリック、ご協力をよろしくお願い致します。
    </small>
    </h5>
    </div>
</div>

<div class="row mb-2">
<ul class="list-group">
  {% for post in site.posts %}
    <li class="list-group-item">
      <a href="{{ post.url | prepend:site.baseurl }}">{{ post.title }} [{{post.date | date: "%Y-%m-%d"}}]</a>
    </li>
  {% endfor %}
</ul>
</div>
</div>
