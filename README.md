Hermes
===
Starter project for phonegap that uses [middleman](http://middlemanapp.com) as a build system
for compiling preprocessed HTML, CSS, and JS.

###### Preprocessing
- [Slim](http://slim-lang.com) *[for html]*
- [SASS](http://sass-lang.com) *[for css]*
- [CoffeeScript](http://coffeescript.org) *[for js]*

###### Tools
- [Bower](http://bower.io) *[js package management]*
- [Compass](http://compass-style.org) *[sass helpers/mixins]*

## Getting Started

1. Clone or fork the repository
2. `bundle`
3. `middleman server`
4. Make changes in the src directory
5. `middleman build`
6. `phonegap run [platform]`

## Using Bower

1. Find and install the packages you need...

  ```
  $ bower search PACKAGE_NAME
  $ bower install ACTUAL_PACKAGE_NAME -S
  ```

2. Include the assets in your js/css files (paths relative to the root 'bower' directory )

  `#=require 'folder/file'` - *for js files*
  `@import 'folder/file'` - *for css files*
