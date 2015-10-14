# Json Viewer
A tool for make JSON view in browser.

# Usage

```js

<link rel="stylesheet" href="json-viewer/json-viewer.css">
<script src="path/to/jquery.js"></script>
<script src="json-viewer/json-viewer.js"></script>

<div id="json-container"></div>

<script>
    var json = {
        foo: "bar",
        number: 123,
    }

    $('#json-container').jsonview(json);
</script>
```

# License

MIT
