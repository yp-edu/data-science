# TME1 Notes

## Scraping 101

- Get the data anywhere
- Parse and select what you need
- Export and store it into a suitable format

## APIs

Whenever possible, use the API provided by the website. If not you might be able to parse the data out of the HTML pages.

## Parsing HTML

Web pages are made of HTML, which, depending on the rendering method can be pretty messy especially when using javascript or minified code.

You might still be able to parse the data using html tags, attributes, hierarchy or classes.

## Advanced

Modern websites tend to block bots, you might need advanced packages like `scrapy` or full browser emulation using `playwright` or `selenium` using "humanizer" plugins.
