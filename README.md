# FRONTUP

## What is Frontup?

It is a kind of bootstrap for front end Projects based on Modular CSS techniques.
As I usually use Rails, I'm using here the file tree of Rails's assets (Rails 3.2 or higher)

### In Frontup you'll find:

_config.scss - a configuration file for several parts
_base.scss - a collection of @mixins reset, form, tables and typography collection
libs/_hive.scss - a responsive grid
application.scss - the main css file that includes oll sections and modules as a bridge

You can find every source in scss or a css compiled version "almost ready to use"

## Using Sass
Be sure to use the right Gem (to compile variables into media queries strings)

 Sass 3.2.0.alpha.244

and generate the static css if you need'em

 cd [assets or frontup directory]
 sass -C -t compact -g --watch ./stylesheets/:./css
