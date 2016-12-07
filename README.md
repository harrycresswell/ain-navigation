# AIN Navigation

Version 1.0

A new navigation prototype made for AIN built on top of [Hugo](https://gohugo.io/).

## Getting started
If you want to grab a copy follow the below setup.

### Install pre-requisites

- Xcode command line utilities `xcode-select --install`
- [Homebrew](http://brew.sh/)
- [Node.js](http://nodejs.org/) `brew install node`
- [Gulp](http://gulpjs.com/) `npm install -g gulp`
- [Hugo](https://gohugo.io/) `brew install hugo`

## Usage

```
git clone https://github.com/harrycresswell/hugo-gulp.git
cd ain-navigation
```
- Then run `npm install` to install node dependencies

### Compile the site
- In a new shell tab run `hugo --verbose`

### Start the server
- run `hugo server --watch --verbose` or `hugo server -wv` to start the server, then navigate to http://localhost:1313/

### Compile assets
- open a second tab on the CL and run `gulp`

### production ready build for deployment
```
rm -rf public
hugo
gulp
```
