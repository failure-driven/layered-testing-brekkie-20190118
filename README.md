# Layered Testing

as presented at [Culture Amp's Tech
Brekky](https://www.meetup.com/Tech-Brekky/events/257396915/) Fri Jan 18th
2019. Available as github pages https://failure-driven.github.io/layered-testing-brekky-20190118/

setup
```
npm i
npm start
open http://127.0.0.1:8080/
```

with speaker notes
* open 2 windows at http://127.0.0.1:8080/
* press `<option>+P` in one window
  * this will switch that window to presenter mode http://127.0.0.1:8080/?mode=presenter#0
  * arrows ⬅ and ➡ will move the slides
  * both windows will be on same slide

to publish to github pages
```
npm run build-github-pages
git commit -ma "publish update to github pages"
git push
```

which publishes assets to the `/docs` folder and makes them accessible at
https://failure-driven.github.io/layered-testing-brekky-20190118/




# mdx-deck basic template

This was generated with [mdx-deck][]'s `npm init deck` command.

## Development

To run the presentation deck in development mode:

```sh
npm start
```

Edit the [`deck.mdx`](deck.mdx) file to get started.

## Exporting

To build the presentation deck as static HTML:

```sh
npm run build
```

To export a PDF:

```sh
npm run pdf
```

To export an image of the title slide:

```sh
npm run image
```

For more documentation see the [mdx-deck][] repo.

[mdx-deck]: https://github.com/jxnblk/mdx-deck
