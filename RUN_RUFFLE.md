Quick test instructions for `ruffle.js`

1. Put your Scratch 2.0 SWF (or any SWF) next to `test.html` and name it `scratch.swf`.
2. Serve the folder over HTTP (browsers block some features for `file://`). Example:

```bash
python3 -m http.server 8000
```

3. Open `http://localhost:8000/test.html` in a browser.

Notes:
- `ruffle.js` (the nightly build you mentioned) must be in the same folder as `test.html`.
- If you want the full Scratch 2.0 editor experience, be aware some features may not be implemented in Ruffle yet.
- To test exported Scratch project `.sb2` files, unzip the `.sb2` (it's a ZIP) to get the embedded SWF or export an SWF from Scratch 2.0 if possible.
