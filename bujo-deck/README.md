# Bullet Journaling Deck

Made with [mdx-deck][].

## Development

To run the presentation deck in development mode:

```sh
npm start
```

You definitely don't want to expose the dev server to the whole world:

```sh
npm start -- --host='::' --no-open
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

[mdx-deck]: https://github.com/jxnblk/mdx-deck
