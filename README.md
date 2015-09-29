# TinyMCE-Ace-Editor-Plugin
Ace Editor plugin for TinyMCE 4.0

How to use:

* Install and load [Ace Editor](https://github.com/ajaxorg/ace-builds/)
* Copy ace (or ace_beautify) folder to TinyMCE plugins
* Add to list of plugins where tinymce is called

Example usage:

```javascript
tinymce.init({
    selector: "textarea",
    plugins: [
        "advlist autolink lists link image charmap print preview anchor",
        "searchreplace visualblocks code fullscreen",
        "insertdatetime media table contextmenu paste code ace"
    ],
    toolbar: "insertfile undo redo | styleselect | bold italic | alignleft aligncenter alignright alignjustify | bullist numlist outdent indent | link image ace"
```

Non-minified version included with some comments. Edit this to alter the Ace Editor options and save to plugin.min.js.

I have inclued a version that works with the fantastic [JS Beautifier](https://github.com/beautify-web/js-beautify), just use ace_beautify instead.
