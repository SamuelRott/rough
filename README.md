# Rough boilerplate

Opinionated structure for new projects. Closely follows the Yeoman generator-webapp which builds on Grunt.


Base
- sass
- grids (susy)
- breakpoints
- autoprefixer
- compass (why?)
- normalize

Styled base
Components/modules/patterns

The purpose of this HTML is to help determine what default settings are with Bitters and to make sure that all possible HTML Elements are included in this HTML so as to not miss any possible Elements when designing a site.


## Features

- Everything from generator-webapp (server, testing, build etc)
- Navigation toggles
- jQuery waypoints integration
- Scroll nav
- Manual styleguide
- Responsive and fluid Masonry setup
- Jade templating (including 'active' navigation and pages)

## Install

You need to install Bower, Compass (alpha), Sass (alpha) and Susy.
`npm install -g bower`
`gem install compass --pre`
`gem install sass --pre`
`gem install susy`

## Structure

- bower_components
- images
- scripts (own scripts go here)
- scripts/vendor (third party scripts that are not available through a package manager (e.g. bower) go here)
- styles

## Naming convention

The naming convention is the same found in [Suit CSS](https://github.com/suitcss/suit/blob/master/doc/components.md#naming-conventions).
```
[<ns>-]<ComponentName>[--modifierName|-childName]
.ComponentName
.ComponentName--modifierName
.ComponentName-childName
.is-stateOfComponent```
