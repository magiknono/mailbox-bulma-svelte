# Intro
After the tweet of @adamwathan, [design a mailbox in 2 hours](https://twitter.com/adamwathan/status/1191807064223469568) i motivated myself to try doing the same without any experience in tailwindcss. (i already configure it with phoenix one time ...)

I lost 4 pomodoro before going back with bulma


the finish looks like a wireframe not a finish frontend ![image](https://raw.github.com/magiknono/mailbox-bulma-svelte/master/drafts/v1-static.png)

## GOAL
 - design a mailbox in 2 hours with tailwindcss.
 - Start from scratch in a svelte project with [webpack template](https://github.com/sveltejs/template-webpack)

1 hours = 4 pomodoro of 25 minutes

* 1st pomodoro = install and configure tailwindcss with svelte and rollup (postcss ?)
* 2nd pomodoro = read docs and design markups - read grid docs or doing with css grid quickly
* 3rd pomodoro = design utilities for container
* 4th pomodoro = design details for box / icons etc

Let's go!

### resource

- https://developer.mozilla.org/fr/docs/Web/HTML
- https://developer.mozilla.org/fr/docs/Web/css
- https://svelte.dev/docs
- https://github.com/sveltejs/template
- https://tailwindcss.com/docs/installation/
- https://dev.to/muhajirdev/using-tailwindcss-with-sveltejs-2098
- awesome svelte resource on github have already premade template

### POMODORO 1 & 2

- read & test install options (some failed, i may have used a ready template)
- install with method this [link](https://dev.to/muhajirdev/using-tailwindcss-with-sveltejs-2098)

### POMODORO 2 & 3
- define html & grid & class in figma (see images in drafts/)
- define base html markups 

## PAUSE

### POMODORO 3 & 4

- lessons learned !
need to tweak svelte bundler to use style tag but after tailwind not working
- tailwind use normalize
- too much classes !

### lessons learned
- retry tailwind last shot only with pure html & no css grid ...
- resisting to the call of bulma
- css utilities or not, that's the question
- tailwind customization was all about tailwind.config.js
- maybe i dont know enough tailbox

## remove tailwindcss & config && restart from scratch ->

### Pomodoro 1
Install & configure bulma with svelte:
- install bulma & postcss for svelte -> svelma -> test OK
Doing base html & layout
- add css grid with html markups = OK

### Pomodoro 2
Separate each grid area in svelte blocks and import it in main App

### Pomodoro 3
- made navuser and navmenu (css grid or flex nav..)

### Pomodoro 4
- made search (without fontawesome)
- made navfilters (without icons & hover)

PAUSE
Pomodoro 1 & 2 & 3 & 4 = 1h30 :-(

### Pomodoro 5
- made Listmail (maybe a media object will be better or message with media because of close button)

### Pomodoro 6
- made ContentMail base
- remove svelma and keep bulma only css


#### LUNCH PAUSE = 
6 pomodoro from scratch with bulma = 3h
it's not like tailwind style but basic is here

TO SEE if nav headers need wil be better with flex to center & align or levels..
add capture figma mailbox-proto-1 in drafts/

# Pomodoro 7
quick fix:
-add sticky tabs to ListMail
-add minimal size for responsive css grid navuser
- make navmenu and nav search in only one component navmenu and use level class of bulma (left right)
- change buttons send mail in dark for wireframe theming..

PAUSE

# Pomodoro 8 & 9
- search contacts with randomuser api
BAD: position fixed css
to do: img in select
it's not a search it"s a random call

BACK to svelte learning
