[![NPM](https://nodei.co/npm/commentsjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/commentsjs)
[![npm version](https://badge.fury.io/js/commentsjs.svg)](https://www.npmjs.com/package/commentsjs)
<a href="https://www.npmjs.com/package/commentsjs">
    <img src="https://img.shields.io/travis/badges/shields.svg"
         alt="build status">
</a>
[![npm downloads](https://img.shields.io/npm/dm/commentsjs.svg?style=flat)](https://www.npmjs.com/package/commentsjs)
<a href="http://bower.io/search/?q=commentsjs">
<img src="http://benschwarz.github.io/bower-badges/badge@2x.png" width="130" height="30">
</a>       

Comments for your html page
=======================================

Easy addition of comments to your html page! [**DEMO** - http://rnjailamba.github.io/CommentsJS/demo] 

## Requirements

Just any html page and commentsjs will add a comments system! 

## Installation

```shell
  npm install commentsjs --save
```

## After Installation

You will find the comments.js file in node_modules/commentsjs/dist/comments.js.      
You will find the comments.css file in node_modules/commentsjs/dist/comments.css.      
Please include the comments.js file after including **jQuery**.     
Please check node_modules/commentsjs/demo/index.html for a very easy example.    
Or just copy stuff from here -> https://goo.gl/hhMTfZ
  
## Usage - Example 1

Just include the following script tag on your HTML page.( after jquery and comments.js and comments.css)        

```
<script>
	$(document).ready( function() {
		$( "#element" ).comments();
	} );
</script>

```


## Tests

```shell
   npm test
```

## Contributing

In lieu of a formal styleguide, take care to maintain the existing coding style.
Add unit tests for any new or changed functionality. Lint and test your code.

## Release History

* 0.0.0 Initial release
* 0.0.1 Initial release
* 0.0.2 Initial release
* 0.0.3 Initial release
* 0.0.4 Initial release
* 0.0.5 Initial release
* 0.0.6 Initial release
* 0.0.7 Initial release
* 0.0.8 Initial release
