# Reactive Angular 2

### 64th Workshop

## Friday, March 18, 2016

* [D1S01 Intro Reactive Applications, Pre-Challenge Setup](https://livestream.com/accounts/4894689/events/4998207/videos/116140065)
* [D1S02 - Pre-Challenge Solution](https://livestream.com/accounts/4894689/events/4998207/videos/116142434)
* [D1S03 - Reactive Big Picture](https://livestream.com/accounts/4894689/events/4998207/videos/116144870)
* [D1S04 - Project Structure Walkthrough, Observables and RxJS](https://livestream.com/accounts/4894689/events/4998207/videos/116148966)
    * [fem-learn-rxjs repo](https://github.com/onehungrymind/fem-learn-rxjs)
* [D1S05 - RxJS Live Coding, Challenge Setup ](https://livestream.com/accounts/4894689/events/4998207/videos/116162240)
* [D1S06 - Challenge Solution, Immutable Operations](https://livestream.com/accounts/4894689/events/4998207/videos/116164594)
* [D1S07 - ]()

## Referenced Workshops (Pre-reqs / Further Learning) 

* [Asynchronous Programming in JavaScript (with Rx.js Observables)](https://frontendmasters.com/courses/asynchronous-javascript/)
* [Functional-Lite JavaScript](https://frontendmasters.com/courses/functional-js-lite/)

## Links from Chat

* [immutable example at babeljs.io](https://babeljs.io/repl/#?evaluate=true&presets=es2015%2Creact%2Cstage-0%2Cstage-1%2Cstage-2%2Cstage-3&experimental=true&loose=false&spec=false&playground=true&code=let%20items%20%3D%20%5B1%2C2%2C3%5D%3B%0A%0A%2F%2F%20add%0Avar%20newItems%20%3D%20%5B...items%2C%2030%5D%0A%0A%2F%2Fremove%0Avar%20filtered%20%3D%20newItems.filter(item%20%3D%3E%20item%20!%3D%3D%202)%3B%0A%0A%2F%2F%20udpate%0Avar%20things%20%3D%20%5B1%2C2%2C3%2C4%2C5%5D.map(num%20%3D%3E%20(%7Bid%3A%20num%7D))%3B%0Avar%20i%20%3D%20things.findIndex(item%20%3D%3E%20item.id%20%3D%3D%3D%202)%3B%0A%0Avar%20updated%20%3D%20%5B%0A%20%20...things.slice(0%2C%20i)%2C%0A%20%20%7Bid%3A%202%2C%20name%3A%20'sadfj'%7D%2C%0A%20%20...things.slice(i%20%2B%201)%0A%5D%3B%0A%0Avar%20state%20%3D%20%7Bapp%3A%20%7B%7D%2C%20items%3A%20%5B1%5D%7D%0A%0A%2F%2F%20add%0Avar%20newState%20%3D%20Object.assign(%7B%7D%2C%20state%2C%20%7Bthings%3A2%7D)%0A%0A%2F%2F%20udpate%0Avar%20newState%20%3D%20%7B%0A%20%20...state%2C%0A%20%20app%3A%202%0A%7D%3B%0A)
* [ngrx devtools](https://github.com/ngrx/devtools)
* [batarangle](https://github.com/rangle/batarangle)
* [falcor](https://netflix.github.io/falcor/)
* [graphQL](https://facebook.github.io/react/blog/2015/05/01/graphql-introduction.html)
* [CHANGE DETECTION IN ANGULAR 2](http://victorsavkin.com/post/110170125256/change-detection-in-angular-2)
* [Building Awesome Apps with Firebase and Angular 2](https://www.youtube.com/watch?v=A1dpvZqoM_w)
* [AngularFire2](https://github.com/angular/angularfire2)

## Workshop Links


* [Video and Chat](https://frontendmasters.com/live-event/reactive-angular-2/)
* [Livestream](https://livestream.com/accounts/4894689/events/4998207)
* [Workshop Links](https://github.com/mrkd/frontend-masters-workshops/blob/master/frontend-masters-reactive-angular-2.md#reactive-angular-2)
* [Github Repo](https://github.com/onehungrymind/fem-ng2-ngrx-app)
* [Slides](https://frontendmasters.com/assets/resources/lukasruebbelke/reactive-angular-2.pdf)
