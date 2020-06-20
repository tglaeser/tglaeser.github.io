# tglaeser.github.io
A personal site intended for an audience of one.

#### Prerequisites
Install [Ruby](https://www.ruby-lang.org/en/) and then run the following command to get RubyGems [Bundler](https://bundler.io/) and [Jekyll](https://jekyllrb.com/).
```
$ gem install bundler jekyll
```

#### Get the sources
```
$ git clone https://github.com/tglaeser/tglaeser.github.io.git
$ cd ./tglaeser.github.io
```


#### Modifications to the Minima theme
In file [_config.yml](_config.yml) Jekyll's Mimima theme is configured consisting of the following files as of version `2.5.1`. 
```
$ tree /lib/ruby/gems/2.7.0/gems/minima-2.5.1
/lib/ruby/gems/2.7.0/gems/minima-2.5.1
├── _includes
│   ├── disqus_comments.html
│   ├── footer.html
│   ├── google-analytics.html
│   ├── head.html
│   ├── header.html
│   ├── icon-github.html
│   ├── icon-github.svg
│   ├── icon-twitter.html
│   ├── icon-twitter.svg
│   └── social.html
├── _layouts
│   ├── default.html
│   ├── home.html
│   ├── page.html
│   └── post.html
├── _sass
│   ├── minima
│   │   ├── _base.scss
│   │   ├── _layout.scss
│   │   └── _syntax-highlighting.scss
│   └── minima.scss
├── assets
│   ├── main.scss
│   └── minima-social-icons.svg
├── LICENSE.txt
└── README.md

5 directories, 22 files
```
Note that any file from this repository matching a leaf node from that tree is overriding the default layout.

#### Update dependencies
```
$ bundle update
```

#### Launch test web server
```
$ bundle exec jekyll serve
```