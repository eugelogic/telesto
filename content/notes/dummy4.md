---
title: "Dummy Four"
draft: false
---

- [Sticky Notes](#sticky-notes)
  - To Do
- [Anatomy](#anatomy)
- [Atlas](#atlas)

---
## <a name="sticky-notes">Sticky Notes</a> <a href="#top">&uarr;</a>
- Static Site Generator !!!
- The world’s fastest framework for building websites https://gohugo.io/
- Quick Start https://gohugo.io/getting-started/quick-start/
- Forum at https://stackoverflow.com/questions/tagged/hugo
- Other Hugo Community Projects https://gohugo.io/tools/other/
- Written in Go programming language https://golang.org/ which uses multithreading

---
##### To Do
- [ ] Finish setup of https://github.com/eugelogic/ristretto
- [X] See the Ideas section below
- [ ] ...

---
### <a name="anatomy">Anatomy</a> <a href="#top">&uarr;</a>

#### Top level anatomy
```
site-name
    ├── archetypes
    │   └── default.md
    ├── config.toml
    ├── content
    ├── data
    ├── layouts
    ├── static
    └── themes
```
[https://gohugo.io/getting-started/directory-structure/](https://gohugo.io/getting-started/directory-structure/)

The `default.md` file inside the `archetypes` folder contains pieces of content that are common to all the content of the website!? It allows you to define metadata about your content.

The `config.toml` file is the main settings file of your website.

---
### <a name="atlas">Atlas</a> <a href="#top">&uarr;</a>
- Atlas (https://github.com/indigotree/atlas) is not a theme but a site framework. There is no themes folder, because you have no theme (same for config.toml). It gives you sass/js stuff mostly, if you want to use a theme, then just use Hugo without atlas. Atlas compares to these https://gohugo.io/tools/starter-kits/
- Atlas is just Hugo with Gulp, SASS & Netlify deployment configuration already done for you.
- Atlas automatically prefixes stuff with `-webkit-` `-moz-` etc if needed

---
### <a name="boilerplates">Boilerplates</a> <a href="#top">&uarr;</a>
A boilerplate is like a starter theme, here are a few good one to start off with.
- Atlas https://github.com/indigotree/atlas
- Victor Hugo https://github.com/netlify/victor-hugo

---
### <a name="commands">Commands</a> <a href="#top">&uarr;</a>
- `$ hugo new site [name of the site]` create new website.
- `$ hugo server` "compile" the site and starts the server . If you stop the server in your command line ( <kbd>CTRL + C</kbd> ), you won't be able to see the website in your browser anymore :wink:
- `$ hugo server -D`, same as the `hugo server` but it also makes sure it renders the draft pages
- `$ hugo server --ignoreCache` to run hugo with no cache
- ...

---
### <a name="videos">Videos</a> <a href="#top">&uarr;</a>
<a href="https://www.youtube.com/watch?v=qtIqKaDlqXo&list=PLLAZ4kZ9dFpOnyRlyS-liKL5ReHDcj4G3" ><img src="http://img.youtube.com/vi/qtIqKaDlqXo/0.jpg"
alt="Introduction to Hugo" width="240" height="180" /></a>

- \#1 Introduction to Hugo | Hugo - Static Site Generator
[https://youtu.be/qtIqKaDlqXo](https://youtu.be/qtIqKaDlqXo)

---
### <a name="tba">tba</a> <a href="#top">&uarr;</a>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
