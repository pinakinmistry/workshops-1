
# Writing an Open Source JavaScript Library

## August 9th, 2016

### 78th Frontend Masters Workshop

### Kent C Dodds

* @kentcdodds
* Github - https://github.com/kentcdodds
* https://kentcdodds.com/

## Tentative Schedule


* 8:30    Tech Check and Hello
* 9:00    Give overview of the course and the library we’re building
* 9:15    npm init the package.json
* 9:45    Exercises
* 10:15   Add unit tests with mocha & coverage with nyc
* 10:45   Exercises
* 11:30   Add transpiling with babel
* 12:00   Lunch and Exercises
* 1:00    Distribute a browser build with webpack
* 1:30    Exercises
* 2:00    Add CI with Travis CI
* 2:15    Exercises
* 3:00    Automate releases with semantic-release
* 3:30    Exercises
* 4:00    Wrap up, links, and resources 

## Links

* Slides - https://kcd.im/oss-workshop
* Workshop Page - https://frontendmasters.com/workshops/open-source/
* Livestream - https://livestream.com/accounts/4894689/events/6042268


## Livestream Video Links

* [Livestream Page](https://livestream.com/accounts/4894689/events/6042268)



* [1.]()

## Links / Resources

* https://opensource.org/osd
* https://opensource.org/licenses

## Setup Instructions

Hi everyone! I'm really excited about the Writing an Open Source JavaScript Library workshop next week! I've worked really hard on this to hopefully make it a good experience for you. If you would be so kind, it would really help me if you gave me 5 minutes on this pre-event survey: http://kcd.im/fem-oss-pre-survey

Also, if you have the time, you could also try to set up the project on your computer to make sure that it'll work for you. I will likely make some finishing tweaks so you'll probably have to do it over again on the day of, but this will help me catch any issues the project has ahead of time so the day of is smooth sailing.

To set up the project you'll need:

* Node version 6 (you can install it with nvm)
* npm version 3 (comes with Node 6)
* git
 
Then run these commands:
```
git clone https://github.com/kentcdodds/starwars-names.git
cd starwars-names
npm run setup:fem
```

If that finished without errors, you're good. Otherwise, please let me know in the issues here.
