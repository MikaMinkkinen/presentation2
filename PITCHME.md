How to be good?
# accesspoint.fi


---

### Mitä me teemme?
1. Tekniikka
nopeus, tietoturva ja jatkokehitys
2. Visuaalinen analyysi
Katsaus sivustoon ja kehityskohteisiin
3. Data-analyysi
Analytiikan katselmointi ja tavoitteet
4. Roadmap
Ehdotuksia ja ideoita jatkokehitykseen

---

### 1. Tekniikka

Työvaiheet
1. Nopeusoptimointi     -> Käyttömukavuutta, hakukone-etua
2. Validoidut lisäosat  -> Tietoturvaa, kehitysnopeutta
3. Sertifiointi         -> Tietoturvaa, hakukone-etua
4. Automaattitestit     -> Kehitysnopeutta, tietoturvaa

---

### 2. Visuaalinen analyysi

Asiantuntija-arvio
1. Tavoitteet           -> Strategia
2. Käyttäjäpolut        -> Kohdennus
3. Kampanjat            -> Konversio

+++

![Acesspoint CTA:s in page](/img/accespoin-page.png)

+++

![Acesspoint CTA:s in homepage](/img/accespoin-frontpage.png)

+++
---

### 3. Data-analyysi

Google Analytics, HotJar
1. Datan analysointi    -> Tulkitaan nykyistä dataa
2. Tavoittet            -> Luodaan tarkka raportointi

---

### 4. Roadmap

Muistilista ja arkinen viestintä
1. Trello               -> Projektinhallinta
2. Slack                -> Arkinen viestintä

---


---
+++

Install Ruby
```
brew install ruby
```

+++

Install RubyGems
Read notes from [Rubygems.org](https://rubygems.org/pages/download#formats)

+++

Install Jekyll and Bunlder trought RubyGems
```
gem install jekyll bundler
```

+++

Check that you have [GCC](https://gcc.gnu.org/install/) and [Make](https://www.gnu.org/software/make/)

```
$ gcc -v
$ make -v
```

---

###### 2.1 Jekyll

Getting started:

```

# Create a new Jekyll site at ./myblog
~ $ jekyll new myblog

# Change into your new directory
~ $ cd myblog

# Build the site on the preview server
~/myblog $ bundle exec jekyll serve

# Now browse to http://localhost:4000
```

+++

![Vanilla blog](/img/vanilla-site.png)


---

###### What the hell happend?

1. Jekyll site is now build
2. Default theme Minima is in use
3. Config.yml is generated

![Vanilla blog](/img/vanilla-site.png)

+++

### How to change theme?
```
bundle update jekyll-athena
```


+++

### How to override theme?

First find what is original theme location using:
```
bundle show minima
```






+++

Minima directory structure

```
.
├── _config.yml
├── _data
|   └── members.yml
├── _drafts
|   ├── begin-with-the-crazy-ideas.md
|   └── on-simplicity-in-technology.md
├── _includes
|   ├── footer.html
|   └── header.html
├── _layouts
|   ├── default.html
|   └── post.html
├── _posts
|   ├── 2007-10-29-why-every-programmer-should-play-nethack.md
|   └── 2009-04-26-barcamp-boston-4-roundup.md
├── _sass
|   ├── _base.scss
|   └── _layout.scss
├── _site
├── .jekyll-metadata
└── index.html # can also be an 'index.md' with valid YAML Frontmatter

```

+++

clone only nessessary files in new destination

my directory structure

```
.
├── _config.yml
├── _data
|   └── members.yml
├── _drafts
|   ├── begin-with-the-crazy-ideas.md
|   └── on-simplicity-in-technology.md
├── _includes
|   ├── footer.html
|   └── header.html
├── _layouts
|   ├── default.html
|   └── post.html
├── _posts
|   ├── 2007-10-29-why-every-programmer-should-play-nethack.md
|   └── 2009-04-26-barcamp-boston-4-roundup.md
├── _sass
|   ├── _base.scss
|   └── _layout.scss
├── _site
├── .jekyll-metadata
└── index.html # can also be an 'index.md' with valid YAML Frontmatter
```

---


---

### 3. Gulp

Implement Gulp

Detailed instruction from [Aaron Lasseigne](https://aaronlasseigne.com/2016/02/03/using-gulp-with-jekyll/)

---

### Go for it.
### Just add <span style="color: #e49436; text-transform: none">PITCHME.md</span> ;)
