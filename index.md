---
# YAML Front Matter

layout: default 

---

<script src="//adm.shinobi.jp/s/866d547b0b4324617e6920c3bac0a34c"></script>


## Hello world

### Minecraft関係はのんびりここに書いていく
spigot関係も含めてGCPのことも追記していく予定

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ page.url | prepend:site.baseurl }}">{{ post.title }} [{{post.date | date: "%Y-%m-%d %H:%M"}}]</a>
    </li>
  {% endfor %}
</ul>

<script src="//adm.shinobi.jp/s/866d547b0b4324617e6920c3bac0a34c"></script>