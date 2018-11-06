## Admin v2.1 for AngularJS fans

This project is a port of the famous Free Admin Bootstrap Theme [SB Admin v2.0](http://startbootstrap.com/template-overviews/sb-admin-2/) to Angular Theme.

The original author recommends that you find out more [Free Angular Themes at StartAngular.com](http://www.startangular.com/).

## Installation
####1. Clone this project or Download that ZIP file
SB
```sh
$ git clone https://github.com/start-angular/sb-admin-angular.git
```

####2.  Make sure you have [bower](http://bower.io/), [grunt-cli](https://www.npmjs.com/package/grunt-cli) and  [npm](https://www.npmjs.org/) installed globally
 
 
```sh (for Ubuntu)
$ sudo apt-get install npm
$ sudo npm install -g grunt-cli
$ sudo npm install -g bower
```
####3. On the command prompt run the following commands

```sh
$ cd `project-directory`
```
- bower install is ran from the postinstall
```sh
$ npm install 
```
- Run
```sh
$ grunt serve
```
- Build and minify the files for deployment
```sh
$ grunt build 
```

**Note:**
If you get this following error, 
```text
Error: EACCES, permission denied '.config/configstore/insight-bower.yml'
You don't have access to this file.
```
changing ownner .config

```sh
sudo chown -R [user name] ~/.config
```
