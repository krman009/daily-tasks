## [Daily-Task](http://krman009.github.io/Daily-Task/)

##### 2014 by [Kaushalya Mandaliya](https://twitter.com/kmandalwala "@kmandalwala") | http://seebeetee.com
---
+ Live Server:
  + To fireup a live server you've to open your **terminal/command prompt/command line.**
  + Navigate to the **Daily-Task directory.**
  + *Type `npm install` to install `devDependencies`.
  + *Then type `gulp` and press `Enter` and wait for some seconds.
  + And There should be a live server at [http://localhost:9090](http://localhost:9090).

> *Note: Make sure that you have installed the [node.js](http://nodejs.org) and [gulpjs](http://gulpjs.com/)  on your machine. (If you've not, don't worry I've written little guide below. :))

---

Installing `node.js`:

+ To install [node.js](http://nodejs.org):
  + Just download it from [nodejs.org](http://nodejs.org) and install it.

Installing `gulpjs`: [when you hit `npm install`, gulp will be installed in present directory]

+ To install [gulpjs](http://gulpjs.com) globally: [First, Make sure you've installed `nodejs`.]
  + Type below command in your `command line` and press `Enter`
    + `npm install --global gulp`

+ \*\*To install [gulpjs](http://gulpjs.com) in your Project devDependencies: [First, Make sure you've installed `nodejs`.]
  + Type below command in your `command line` and press `Enter`
    + `npm install --save-dev gulp`

\*\* If you only install `gulp` in Project `devDependencies` then It will not <sup>\[1\]</sup> work in your `Command line`. Thus You've to install it globally first, to run the command `gulp`.

<sup>\[1\]</sup> As tested in Windows 8, The `gulp` command isn't working without installing it globally.

---
## [LICENSE](https://github.com/krman009/Daily-Task/blob/master/LICENSE)
MIT (c) Kaushalya Mandaliya
