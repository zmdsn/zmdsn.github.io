# 改动记录

# CDN替换



cloudflare.com  替换为 loli.net

因为墙的缘由，cloudflare.com 不够流畅。



/layouts/slides/baseof.toml 文件中修改：

cloudflare.com  替换为 loli.net

  {{ $cdn_url_reveal := "https://cdnjs.loli.net/ajax/libs/reveal.js/3.8.0" }}



/thermes/academic/data/assets.toml 文件中修改：

  url = "https://cdn.bootcss.com/mathjax/3.0.5/es5/tex-chtml.js"

  

#url = "https://cdnjs.loli.net/ajax/libs/lazysizes/%s/lazysizes.min.js"
  url = "https://cdn.bootcdn.net/ajax/libs/lazysizes/5.3.2/lazysizes.min.js"



./layouts/partials/site_js.html

        <script src="https://unpkg.com/ajax/libs/highlight.js/{{ $v }}/languages/{{ . }}.min.js"></script>

        <script src="https://unpkg.com/ajax/libs/highlight.js/{{ $v }}/languages/{{ . }}.min.js"></script>



mysite/layouts/partials/site_head.html 文件中

​        {{ printf "<script src=\"%s\" integrity=\"%s\" crossorigin=\"anonymsous\" async></script>" (printf v.url v.version) $v.sri | safeHTML }}

  改为

 {{ printf "<script src=\"%s\" integrity=\"%s\" crossorigin=\"anonymsous\" async></script>" (printf  v.url ) v.sri | safeHTML }}









查找所有文件中是否存在字符串

find .|xargs grep -ri "jsdelivr"



