# IdealClub
The first attempt at a website for the IdealClub band. Rebuilt with Hugo and an improved build system and was simpler to create a new repo than replace the old one.

## Building from a clean install
The website uses the gulp build tool so you'll first need to install Node.js and npm (Node Package Manager).

Next run the below instructions at a command line.

###1. Install Gulp and babel dependancies
```
$ npm install gulp --global
$ npm install babel --global
```

###2. Install build dependant packages
```
$ npm install
```

###3. Build the website and start a local server running
```
$ gulp
```

###4. Open a browser to localhost:4000

## Publishing changes to live
If you can succesfully run a clean install as above and the website looks as it should you can publish your changes with:

```
gulp publish
``` 
