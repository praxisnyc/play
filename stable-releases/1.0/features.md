# praxis / play features

An ever-growing list of conditions and libraries to speed up your creative code: Want text not to be selectable? Want to prevent zoom? ml5? smooth scroll?

Features are per page so you only load what you need, to ensure performance. 


## Installation

- make sure **praxis / play** is on 
- on frontmatter, add `features: ` and then whatever feature you want to add (ie: `features: no-scroll, ml5`, etc)


## Feature list

| Name  | โฑ๏ธ | Description | Dependencies | Notes |
|:---- |:----------- |:----------- |:------------ |:----- |
| `p5js` | ๐ | installs [p5js library](https://p5js.org/) | - | - |
| `no-scroll` | ๐ | prevents scroll | - | - |
| `no-zoom` | ๐ | prevents zoom | - | - |
| `modernizr` | ๐ | installs [modernizr](https://modernizr.com/) and [detectizr](https://github.com/barisaydinoglu/Detectizr#detectizr) libraries | `jquery` |  - |
| `ml5js` | ๐ | installs [ml5js library](https://ml5js.org/) | - | - |
| `jquery` | ๐ | installs [jquery library](https://jquery.com/) | - | - |
| `no-text-select` | ๐ | prevents text selection (globally) | - | non-global version? |
| `revealjs` | ๐งช | installs [revealjs library](https://revealjs.com/) | - | - |
| `style` | โณ | loads main.css | - | hugo version needed |
| `bootstrap` | โณ | installs bootstrap CSS and JS, plus popper and tooltip/popover activation | `jquery` | hugo version needed |
| `redirect` | โณ | redirects page | - | maybe a shortcode? |
| `favicon` | โณ | adds favicon for all browsers and devices | - | hugo version needed |
|`open-graph` | โณ | adds all open-graph features (for facebook ,twitter, etc) | - | hugo version needed |
| `request-motion` | โณ | modal intercept requesting gyroscope permissions | - | should only appear if browser HAS this function |
| `smooth-scroll` | โณ | forces smooth scrolling when internal navigation | - | hugo version needed |
| `no-nav` | โณ | removes top browser navigation | - | maybe PWA is better? |
| `request-location` | โณ | modal intercept requesting location permissions | - | hugo version needed |
| `request-camera` | โณ | modal intercept requesting camera permissions | - | hugo version needed |
| `fullbleed` | โณ | moves canvas to bg, below HTML | - | hugo version needed |

- ๐: ready to use
- ๐งช: testing
- โณ: soon

## Get informed

Features keep growing, so make sure to:

- [Subscribe to our newsletter](https://tinyletter.com/praxis-play/) for updates
- Contact us for suggestions: [email](mailto:info@nicholasfrota.com?subject=praxis%20play%20feature%20suggestion), [twitter](https://twitter.com/nonlinear), [mastodon](https://mastodon.social/@nonlinear)
- [Join our telegram group](https://t.me/joinchat/IZcW2U4HflaCQj1G) for questions, troubleshooting, etc
