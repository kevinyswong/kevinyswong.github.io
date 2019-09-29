---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

<div style="width: 200px; height:1000px;float: left; padding-right: 50px;">
  <img src="photo.jpeg" style="padding-bottom: 20px;">
  <ul class="social-media-list">

  <img src="location-pin.png" width=20px style="padding-bottom: 9px; padding-left: 0px; opacity: 0.6;"> Notre Dame, IN
  {%- if site.github_username -%}<li><a href="https://github.com/{{ site.github_username| cgi_escape | escape }}"><svg class="svg-icon"><use xlink:href="{{ '/assets/minima-social-icons.svg#github' | relative_url }}"></use></svg> <span class="username">GitHub</span></a></li>{%- endif -%}
  {%- if site.linkedin_username -%}<li><a href="https://www.linkedin.com/in/{{ site.linkedin_username| cgi_escape | escape }}"><svg class="svg-icon"><use xlink:href="{{ '/assets/minima-social-icons.svg#linkedin' | relative_url }}"></use></svg> <span class="username">LinkedIn</span></a></li>{%- endif -%}
</ul>
</div>

<div>
  I am a first year PhD student at the University of Notre Dame, where I am
  working with <a href="https://www3.nd.edu/~nchawla/">Nitesh Chawla</a> in
  the <a href="https://www3.nd.edu/~dial/home/">DIAL lab</a>. Prior to
  graduate school, I spent several years in industry. Before that, I did my
  undergraduate studies at NYU. My research interests are in machine learning
  and natural language processing.
</div>

