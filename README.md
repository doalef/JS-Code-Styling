JS Code Styling
===================

Let's bring some beauty to your messed up project :))

so most javascript developers know about jsint , jscs and eslint
but in case you live in a cave or something here's a summary:

##### JSHint

> - JSHint is a community-driven tool that detects errors and potential problems in JavaScript code.
> - JSHint is open source and it will stay that way according to their website.
> - It's easily adjustable (many people think otherwise tho)
> - You can costumize it for you own enviorment
> - It supports different Versions of EcmaScript such as es5 and es6

**Okay now how we install it**

first of all set up your working enviorment if you have VSC or some other ide's install `jshint` extension
it will make life much more easier.

okay now that you have installed the extension let's set up jshint , first run the command:

`npm i --save-dev jshint`

next step is to create a `.jshintrc` file with your own configuration or clone it from here and copy it to your project (recomended for fat and lazy or short on time programmers)

but before you start note that you should change the config to fit into your project otherwise it shits all over ide logs.

you can set your your es version in `esversion` incase your using it else set it to false.
checkout the official documentation [JSHint/docs](http://jshint.com/docs/)

##### JSCS
