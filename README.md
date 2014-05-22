# so dank
![Leeloo](http://i.imgur.com/SJ6SydZ.jpg)
## [presidank.info](http://presidank.info)

<br>



#### To dev locally for the first time
Get homebrew
```bash
$ ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"
$ brew doctor
```
Get node and npm
```bash
$ brew install node
$ npm update -g npm
```
Get essential node packages (task runner, site generator, web frontend lib manager)
```bash
$ npm install -g grunt-cli yo bower
```
Checkout repository
```bash
$ git clone git@github.com:drewlustro/presidank.git presidank
```
Install site package libs
```bash
$ cd presidank
/presidank $ npm install
```
---
#### Develop locally (OS X)
```bash
/presidank $ grunt serve
```

#### Build site distribution to upload (OS X)
```bash
/presidank $ grunt build
```

#### Show folder to upload to server (OS X)
```bash
/presidank $ open dist
```
