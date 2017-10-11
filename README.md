# Gulp-Kirby-Starter-Kit
**You heard about Kirby and want to use it on your next project? You're' also excited about Gulp v4, but want to harness its power today? Then THIS is for you!**

Here's my very personal (thus very opinionated) Gulp+Kirby boilerplate, starring:
- [Kirby CMS](https://getkirby.com/) - a file‑based CMS that's 'easy to setup, easy to use & flexible as hell'
- [Gulp v4](http://gulpjs.com/) - the streaming build system

If you just want to have a look, feel free to do so with `php -S localhost:8000`.


## Features
This boilerplate is growing fastly and already provides a solid starting point that you can build upon. For now, just check gulpfile.js or package.json to find out about all the included / planned features!

Workflow:
- Sass / node-sass / libsass
- Webpack
- Bourbon / Bitters
- Image optimization
- Minification (styles & scripts)
- ...

Pre-installed Kirby plugins:
- Fingerprinting via [kirby-fingerprint](https://github.com/iksi/KirbyFingerprint)
- HTML Minification via [kirby-compress](https://github.com/iksi/kirby-compress)
- SEO & SERP preview & edit via [kirby-seo](https://github.com/jenstornell/kirby-seo)
- User-friendly text formatting via [kirby-enhanced-textarea](https://github.com/medienbaecker/kirby-enhanced-textarea)
- Content organisation & overview via [kirby-tabs-field](https://github.com/afbora/Kirby-Tabs-Field)
- More flexible select field via [kirby-quickselect](https://github.com/medienbaecker/kirby-quickselect)
- ...

Optionally:
- [kirby-imageset](https://github.com/fabianmichael/kirby-imageset)
- [kirby-focus](https://github.com/flokosiol/kirby-focus)
- [kirby-translations](https://github.com/flokosiol/kirby-translations)
- [kirbytranslations](https://github.com/rasteiner/kirbytranslations)
- [KirbyComments](https://github.com/Addpixel/KirbyComments)


_to be continued_


## Getting started
Make sure [Node.js](http://nodejs.org/) is installed on your system, then clone this repository (and all included submodules) and install its dependencies via [NPM](https://npmjs.org/):

```bash
$ git clone --recursive https://github.com/S1SYPHOS/Gulp-Kirby-Starter-Kit.git your-project
$ cd your-project
$ npm install
```

If you want to update all included submodules later on, it's just these two lines:

```bash
 $ git submodule foreach --recursive git checkout master
 $ git submodule foreach --recursive git pull
```

**Note: Before publishing your project, be sure to add your production `config.php` (eg `config.example.com.php`) to .gitignore!**


## Special Thanks
I'd like to thank everybody that's making great software - you people are awesome. Also I'm always thankful for feedback and bug reports :)
