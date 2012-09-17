# FRONTUP

## What is Frontup?

It is a kind of bootstrap for front end Projects based on Modular CSS techniques.
It's a collections of other libs and tools I do use to design websites. As I usually use Rails and Railsyard, I have love to develop in Rails, I'm using here the tree of Rails's assets (Rails 3.2 or higher)

### In Frontup you'll find:

HIVE - a responsive grid
SPLEEN SCSS - a collection of @mixins reset, form, tables and typography collection
application.scss - thge main css file that includes oll sections and modules
_hive_config.scss - it's a symlink to configuration file for the HIVE responsive grid (@media queries breaks, gaps ect)

REMIND: I suggest to avoid to change files within libs folder. All libs are collected from github from their own repos.

You can find every source in scss or a css compiled version "almost ready to use"

## Using Sass

Be sure to use the right Gem (to compile variables into media queries strings)

 Sass 3.2.0.alpha.244

and generate the static css if you need'em

 cd [assets or frontup directory]
 sass -C -t compact -g --watch ./stylesheets/:./stylesheets

## Using the css

Every module, section or third parties libs might be @imported inside the application.scss file
After that you can put into your html head the link

 <link rel="stylesheet" href=".stylesheets/application.css">



