# Hello world

## External scripts

Script files are attached to HTML with the `src` attribute:

```html
<script src="/path/to/script.js"></script>

<script src="https://cdnjs.cloudflare.com/ajax/libs/lodash.js/4.17.11/lodash.js"></script>
```

The benefit of a separate file is that the browser will download it and store it in its cache. Other pages that reference the same script will take it from the cache instead of downloading it, so the file is actually downloaded only once.

⚠️If `src` is set, the script content is ignored. A single `<script>` tag can’t have both the src attribute and code inside.*
