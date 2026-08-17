# ramzpat.github.io

My personal page, plus a few toy projects I host here.

The landing page is a hand-written static page — `index.html` and `styles.css`, no
build step and no JavaScript framework. Edit the files and push; GitHub Pages serves
them directly. (It used to be a Create React App build generated from
[`pwa-profile`](https://github.com/ramzpat/pwa-profile); that repo is no longer used.)

## Projects

- **Pokemon SV Sandwich Finder** — search Scarlet & Violet recipes by the effects you want.
  - Live: https://ramzpat.github.io/pkm-sandwich-finder/
  - Source: https://github.com/ramzpat/pkm-sandwich-recipe
  - Built with `TypeScript`, because I wanted to learn how to build a client-side web app
    and `TypeScript` seems good for maintenance.

## Planned

- Pokedex web app, inspired by [pokedex.org](https://pokedex.org)

## Layout

```
index.html              landing page
styles.css              landing page styles
avatar.webp             portrait used on the landing page
web_icon.*, favicon.ico icons
manifest.json           PWA manifest
pkm-sandwich-finder/    deployed build, from pkm-sandwich-recipe
pkm-sandwich-simulator/ deployed build of the third-party
                        cecilbowen/pokemon-sandwich-simulator; not linked from
                        the landing page
```
