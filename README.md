# lzalles

#Pre-requisites
git, node|npm /bower /Grunt
- Install git: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
- Install Node: https://nodejs.org/
- Once you have npm, install bower:
```sh
$ npm install -g bower
```
- Install grunt-cli
```sh
$ npm install -g grunt-cli
```


#How to run
- Clone Repo
```sh
$ git clone https://github.com/davidseik/lzalles.git
``` 
- Go to directory
```sh
$ cd lzalles
``` 

- Install packages
```sh
$ sudo npm install
```

- Install bower components
```sh
$ bower install
``` 
- Run project
```sh
$ grunt serve
``` 
This will automatically open a tab in your default browser pointing to your page and will start watching the files.
Every time you modify a HTML, CSS or JS file it will automatically refresh the tab and show you the progress.

Once all the changes are done
- Get a build of your project
```sh
$ grunt build
```
This will create a 'dist' folder locally with minified/concatenated files and everything linked together ready for upload.

TODO:
Create automatic hook for grunt build to upload to server.
