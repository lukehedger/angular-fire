# angular-fire

*Probably not ready for production*

## What?

An [Angular-Firebase](https://www.firebase.com/docs/web/libraries/angular/quickstart.html) project starter, injected with [Gulp](http://gulpjs.com/), [Browserify](http://browserify.org/), [CoffeeScript](http://coffeescript.org/), [Stylus](http://learnboost.github.io/stylus/) (with [Jeet](http://jeet.gs/) & [Rupture](https://github.com/jenius/rupture)), [Divshot](https://divshot.com/) and [Travis](https://travis-ci.org).

## Setup

- Create a [Firebase account](https://www.firebase.com/signup/)
- Install Firebase CLI: `npm install -g firebase-tools`
- Setup Firebase: `firebase init`
- Create a [Divshot account](https://auth.divshot.com/register)
- Install Divshot CLI: `npm install -g divshot-cli`
- Setup Divshot: `divshot init`
- Install Gulp: `npm install -g gulp`
- Install dependencies: `npm install && bower install`
- Then run `gulp` to compile and serve. The rest is up to you.

## Deployment

- Run `gulp release` to build  your `public/` folder.
- To set up Travis (to allow you to auto-deploy when pushing to GitHub) [see the instructions](http://docs.divshot.com/integrations/travis)
- Push to Divshot manually: divshot push <env>
- Promote to environment: divshot promote <from_env> <to_env>

## Status

- Add your Travis status here, like:
```
[![Build Status](http://img.shields.io/travis/lukehedger/angular-fire/master.svg?style=flat)](https://travis-ci.org/lukehedger/angular-fire)
```
