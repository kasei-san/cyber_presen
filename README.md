
## make working copy

```
$ git clone git@github.com:hakimel/reveal.js
$ mv reveal.js cyber_presen
$ cd cyber_presen
$ rm -Rf .git
$ git init
$ git add -A
$ git commit -m "First commit"
```

## setup

```
$ npm install grunt-cli -g
$ npm install
$ grunt serve
``

see http://localhost:8000


## markdown to html

```
$ vim index.html
```

change under div class="reveal"

```
 41    <div class="reveal">
 42       <div class="slides">
 43         <section data-markdown="./slide.md"__
 44           data-separator="^\n\n\n"__
 45           data-vertical="^\n\n"__
 46           data-notes="^Note:"__
 47           data-charset="utf-8">
 48         </section>
 49       </div>
 50     </div>
```

write slide.md

```
$ vim slide.md
```

## references


- https://github.com/hakimel/reveal.js#full-setup
- [Deploy reveal.js slideshow on github-pages | Tikal](http://tikalk.com/alm/deploy-revealjs-slideshow-github-pages)
- 






















