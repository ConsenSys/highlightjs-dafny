# highlightjs-dafny

[Dafny](https://github.com/dafny-lang/dafny) language grammar definition for [highlight.js](https://highlightjs.org/).

## Usage
Adapted from the ["Usage" section of highlightjs-cypher](https://github.com/highlightjs/highlightjs-cypher#usage).


Simply include the Highlight.js library in your webpage or Node app, then load this module.

### Static website or simple usage

Simply load the module after loading Highlight.js. You'll use the minified version found in the `dist` directory. This module is just a CDN build of the language, so it will register itself as the Javascript is loaded.

```html
<script type="text/javascript" src="/path/to/highlight.min.js"></script>
<script type="text/javascript" src="/path/to/highlightjs-dfny/dist/dafny.min.js"></script>
<script>hljs.highlightAll();</script>
```

This will find and highlight code inside of `<pre><code>` tags; it tries to detect the language automatically. If automatic detection doesn’t work for you, or you simply prefer to be explicit, you can specify the language manually in the using the class attribute:

```html
<pre><code class="language-dafny">...</code></pre>
```

### Using jsDelivr CDN

```html
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/ConsenSys/highlightjs-dafny/dist/dafny.min.js"></script>
```

<!-- - More info: <https://unpkg.com>

### With Node or another build system

If you're using Node / Webpack / Rollup / Browserify, etc, simply require the language module, then register it with Highlight.js.

```javascript
var hljs = require('highlightjs');
var hljsDafny = require('highlightjs-dafny');

hljs.registerLanguage("dafny", hljsDafny);
hljs.initHighlightingOnLoad();
``` -->

### Other usages

For other usages see the [official highlight.js documentation](https://highlightjs.org/usage/).

## License

highlight-dafny is released under the Apache 2.0 license. See [LICENSE][1] file
for details.

### Author

Roberto Saltini

### Maintainer

Roberto Saltini

## Links

- The official site for the Highlight.js library is <https://highlightjs.org/>.
- The Highlight.js GitHub project: <https://github.com/highlightjs/highlight.js>
- Dafny GitHub repo: <https://github.com/dafny-lang/dafny>

[1]: https://github.com/ConsenSys/highlightjs-dafny/blob/main/LICENSE