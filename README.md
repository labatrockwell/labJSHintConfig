#labJSHintConfig
This is our configuration file for [JSHint](http://www.jshint.com/)

We don't want to impose an excessive amount of restrictions on people's code, but there are some things like variable naming conventions and tab vs. space that we want to normalize.

A great part of using a linter is that it does a quick sanity-check on your code before you waste time trying to run it.

We decided to use JSHint instead of other options because of it's promise of configurability. A linter becomes much less useful if you have to 'tune out' various warnings that you don't really care about.


##Setup
1. Clone this repo `git clone https://github.com/labatrockwell/labJSHintConfig.git`
2. Copy jshintrc to your home driectory `cp jshintrc ~/.jshintrc`
3. Install JSHint `npm install jshint -g`
4. Sanity-check your code! `jshint myfile.js`

###Updating
1. Pull the latest changes `git pull`
2. Copy jshintrc to your home directory `cp jshintrc ~/.jshintrc`

