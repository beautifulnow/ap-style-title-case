# ap-style-title-case

Convert a string to title case using
[AP](https://en.wikipedia.org/wiki/AP_Stylebook)/[APA](https://en.wikipedia.org/wiki/APA_style)
style.

## The Rules

- Always capitalize the first word, even if it's a stopword
- Always capitalize the last word, even if it's a stopword
- Lowercase these words: a an and at but by for in nor of on or so the to up yet

> Many writers make the error of leaving “to be” verbs in lower case. Even though “is,” “are,” “was,” and “be,” are all short words, they should still be capitalized in a title because they are verbs.

## Usage

Install and save to your package.json dependencies:

```sh
npm install ap-style-title-case --save
```

Use it:

```js
const titleCase = require('ap-style-title-case')

titleCase('why sunless tanning is A hot trend')
// 'Why Sunless Tanning Is a Hot Trend'
```

## References

- https://www.bkacontent.com/how-to-correctly-use-apa-style-title-case/
- https://en.wikipedia.org/wiki/AP_Stylebook
- https://en.wikipedia.org/wiki/APA_style
- http://blog.apastyle.org/apastyle/2012/03/title-case-and-sentence-case-capitalization-in-apa-style.html

## Installation

```sh
npm install ap-style-title-case --save
```

## Tests

```sh
npm install
npm test
```

## Dependencies

None

## Dev Dependencies

- [tap-spec](https://github.com/scottcorgan/tap-spec): Formatted TAP output like Mocha&#39;s spec reporter
- [tape](https://github.com/substack/tape): tap-producing test harness for node and browsers


## License

MIT
