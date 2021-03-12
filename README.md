# nonlinear play

A [hugo](https://gohugo.io/) theme environment for  stand-alone creative code experiments, reducing the learning curve so you can enjoy being in the zone.

Our goal to curate best practices (integrating, testing, documenting) to play with:

- processing
- p5js
- ml5js
- PWA (so it works well on mobile browsers)


## Features

An ever-growing list of conditions and libraries to speed up your creative code: Want text not to be selectable? Want to prevent zoom? ml5? smooth scroll?

Features are per page so you only load what you need, to ensure performance. 

Features keep growing, so make sure to:

1. [View all features](features.md#features)
2. [Subscribe to our newsletter](https://tinyletter.com/nonlinear-play/) for updates
3. Contact us for suggestions: [email](mailto:info@nicholasfrota.com?subject=nonlinear play feature suggestion), [twitter](https://mastodon.social/@nonlinear), [mastodon](https://twitter.com/nonlinear)

## Requirements

1. Hugo
2. Git

## Installation

1. [Install hugo](https://gohugo.io/getting-started/installing/)
1. Create a hugo site
1. Create a [git repository](https://docs.github.com/en/github/getting-started-with-github/create-a-repo) for it
1. Install `play` as a theme submodule
	1. Go to `themes/` folder
	1. Run `git submodule add https://github.com/nonlinear/play.git play`
1. On `config.toml` add `theme = "play"`


## Creating a new post

1. Make sure post is `.html`
1. On frontmatter, add:
	1. `layout: play` to activate
	1. add the features you need with `features: feature1, feature2` ([View all features](features.md#features))


## Updating Theme

1. go to your hugo project folder
1. go to the theme with `cd themes/play`
1. `git pull`


## Publishing

> *pending*

<!-- https://docs.github.com/en/github/working-with-github-pages/creating-a-github-pages-site
	1. ensure `baseURL` has proper URL on it (learn how to publish your site on github)
Troubleshoot: submodule + githubpages

Github generates flat blogs server-side, so submodule breaks because it renames folder with commit. flat blogs are meant to be client-side, so there's a way to prevent github from rebuilding it server-side:

1. force hugo to generate flat blog on `docs/` folder, instead of default `site/` 
1. add `publishDir = "docs"` on `config.toml`
1. on github settings, tell githubpages to point to `docs/` folder instead

1. build hugo with `hugo`
1. push changes -->


## Get informed

- [Subscribe to our newsletter](https://tinyletter.com/nonlinear-play/) for updates
- Contact us for suggestions: [email](mailto:info@nicholasfrota.com?subject=nonlinear%20play%20feature%20suggestion), [twitter](https://twitter.com/nonlinear), [mastodon](https://mastodon.social/@nonlinear)
- [Join our telegram group](https://t.me/joinchat/IZcW2U4HflaCQj1G) for questions, troubleshooting, etc