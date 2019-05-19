---
# YAML Front Matter

layout: default 

---

<script src="//adm.shinobi.jp/s/866d547b0b4324617e6920c3bac0a34c"></script>


## Hello world

### Minecraft関係はのんびりここに書いていく
spigot関係も含めてGCPのことも追記していく予定  
※当サーバーは広告費で運営しております。一人一人の広告クリックで成り立っています。一日一クリック、ご協力をよろしくお願い致します。

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | prepend:site.baseurl }}">{{ post.title }} [{{post.date | date: "%Y-%m-%d"}}]</a>
    </li>
  {% endfor %}
</ul>

<script src="//adm.shinobi.jp/s/866d547b0b4324617e6920c3bac0a34c"></script>