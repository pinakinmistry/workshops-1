# Webpack Deep Dive

## August 8th, 2016

### 77th Frontend Masters Workshop

### Kent C Dodds

* @kentcdodds
* Github - https://github.com/kentcdodds
* https://kentcdodds.com/

## Tentative Schedule


* 8:30    Tech Check and Hello
* 9:00    Setup baseline webpack understanding (quick intro to fundamentals)
* 9:30    Exercises
* 10:00   Setting up a test environment with Karma
* 10:30   Exercises
* 11:15   Adding code coverage to test setup
* 11:30   Lunch and Exercises
* 12:30   Tree-shaking
* 12:45   Exercises
* 1:00    Code splitting
* 1:20    Exercises
* 2:00    Caching
* 2:30    Exercises
* 3:15    CommonsChunkPlugin
* 3:30    Exercises
* 4:00    Wrap up, links, and resources* 

## Links

* Slides - https://kcd.im/webpack-workshop
* Workshop Page - https://frontendmasters.com/workshops/webpack/
* Livestream - https://livestream.com/accounts/4894689/events/6042257
* 


## Livestream Video Links

* [Livestream Page](https://livestream.com/accounts/4894689/events/6042257)


* [1. Webpack Deep Dive](https://livestream.com/accounts/4894689/events/6042257/videos/132274400)
* [2. Webpack Deep Dive](https://livestream.com/accounts/4894689/events/6042257/videos/132278220)
* [3. Webpack Deep Dive](https://livestream.com/accounts/4894689/events/6042257/videos/132282471)


## Setup Instructions

Hi everyone! I'm really excited about the Webpack Deep Dive workshop next week! I've worked really hard on this to hopefully make it a good experience for you. If you would be so kind, it would really help me if you gave me 5 minutes on this pre-event survey:
http://kcd.im/fem-webpack-pre-survey

Also, if you have the time, you could also try to set up the project on your computer to make sure that it'll work for you. I will likely make some finishing tweaks so you'll probably have to do it over again on the day of, but this will help me catch any issues the project has ahead of time so the day of is smooth sailing.

To set up the project you'll need:

* Node version 6 (you can install it with nvm)
* npm version 3 (comes with Node 6)
* git

Then run these commands:

```
git clone https://github.com/kentcdodds/es6-todomvc.git
cd es6-todomvc
npm run setup:fem
npm start
```


Now, open your browser to http://localhost:8080 and you should be looking at a Todo app. If that happens without any issues, then you're good to go. If not, please report them here!
