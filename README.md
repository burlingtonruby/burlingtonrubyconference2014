# The 2014 Burlington Ruby Conference

August 1st-3rd, 2014

[http://burlingtonrubyconference.com](http://burlingtonrubyconference.com)

## Contributing

The conference website is powered by [jekyll](http://jekyllrb.com).

### Server

Install jekyll

```
gem install jekyll
```

Boot up the jekyll server (and watch for changes)

```
jekyll serve -w
```

Change the source and view the changes in your browser

[http://localhost:4000/](http://localhost:4000/)

### Styles

We're using [Foundation Compass Template](https://github.com/zurb/foundation-compass-template/) to compile and watch SCSS file changes.

Install:

1. Node from [http://nodejs.org/](http://nodejs.org/).
1. Compass: `gem install compass`.
1. Bower: `npm install bower -g`.

Run compass to watch for style changes:

```
compass watch
```
