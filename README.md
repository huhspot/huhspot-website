huhspot-website
===============

Website for Huh? &amp; Huhspot made with Middleman

## Dependencies
* Git, obviously
* Ruby (install with [rbenv](https://github.com/sstephenson/rbenv))
* Rubygems
* Bundler (`gem install bundler`)
* [Middleman](middlemanapp.com)
 
### Open Source libraries used
* [Middleman Deploy GEM](https://github.com/tvaughan/middleman-deploy) to deploy, currently to Github Pages
* [Bourbon](http://bourbon.io/)
* [Bitters](https://github.com/thoughtbot/bitters)
* [Neat](http://neat.bourbon.io/)

## Getting it to work 
1. clone this repository (`git clone git@github.com:huhspot/huhspot-website.git`)
2. run `bundle install`
3. run `bundle exec middleman`
4. go to localhost:4567
5. ask me why it's not working

## Deploying
*Warning: do __not__ merge `development` to `master`*
This prototype is configured to deploy to Github pages through the __master__ branch of this repository. 
Run the following to deploy to http://huhspot.github.io/

```
$ middleman build 
$ middleman deploy 
```
