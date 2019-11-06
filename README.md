# Intro
After the tweet of @adamwathan, (design a mailbox in 2 hours)[https://twitter.com/adamwathan/status/1191807064223469568] i motivated myself to try doing the same without any experience in tailwindcss. (i already configure it with phoenix one time ...)

## GOAL
design a mailbox in 2 hours with tailwindcss.
Start from scratch in a svelte project with (webpack template)[https://github.com/sveltejs/template-webpack]

1 hours = 4 pomodoro of 25 minutes

1st pomodoro = install and configure tailwindcss with svelte and rollup (postcss ?)
2nd pomodoro = read docs and design markups - read grid docs or doing with css grid quickly
3rd pomodoro = design utilities for container
4th pomodoro = design details for box / icons etc

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
- install with method this (link)[https://dev.to/muhajirdev/using-tailwindcss-with-sveltejs-2098]

### POMODORO 2 & 3
- define html & grid & class in figma (see images in drafts/)
- define base html markups 

### PAUSE

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

### pomodoro 3
- made navuser and navmenu (css grid or flex nav..)

### pomodoro 4
- made search (without fontawesome)
- made navfilters (without icons & hover)
==========================================================================================================================================

*Psst — looking for a shareable component template? Go here --> [sveltejs/component-template](https://github.com/sveltejs/component-template)*

---

# svelte app

This is a project template for [Svelte](https://svelte.dev) apps. It lives at https://github.com/sveltejs/template.

To create a new project based on this template using [degit](https://github.com/Rich-Harris/degit):

```bash
npx degit sveltejs/template svelte-app
cd svelte-app
```

*Note that you will need to have [Node.js](https://nodejs.org) installed.*


## Get started

Install the dependencies...

```bash
cd svelte-app
npm install
```

...then start [Rollup](https://rollupjs.org):

```bash
npm run dev
```

Navigate to [localhost:5000](http://localhost:5000). You should see your app running. Edit a component file in `src`, save it, and reload the page to see your changes.

By default, the server will only respond to requests from localhost. To allow connections from other computers, edit the `sirv` commands in package.json to include the option `--host 0.0.0.0`.


## Deploying to the web

### With [now](https://zeit.co/now)

Install `now` if you haven't already:

```bash
npm install -g now
```

Then, from within your project folder:

```bash
cd public
now
```

As an alternative, use the [Now desktop client](https://zeit.co/download) and simply drag the unzipped project folder to the taskbar icon.

### With [surge](https://surge.sh/)

Install `surge` if you haven't already:

```bash
npm install -g surge
```

Then, from within your project folder:

```bash
npm run build
surge public
```
