# json-formatter

Using js and html to display a formatted json list for debugging purposes. This can be run on your local system so you don`t have to worry about security breaches on your json data.

## Usage

Run json.html on your browser and simply enter your json string into the textarea box. Click "format!" (or press Ctrl/Cmd+Enter) to see the formatted JSON.

Input is validated with the browser's built-in `JSON.parse`, then re-indented from the original text, so big integers, key order and duplicate keys are shown exactly as pasted. Invisible and bidi characters inside strings are shown as `\uXXXX` escapes.

No libraries and no network requests: the page is a single self-contained file.

## License

Released under MIT license:
http://www.opensource.org/licenses/mit-license.php
