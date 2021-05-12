# emoji-picker
An advanced JavaScript emoji picker

## Use
You will need jQuert for this emoji picker. Make sure you include jQuery BEFORE including this emoji picker. You can use github as the CDN or download from here:
```html
<script src="https://raw.githubusercontent.com/nbbcsf/emoji-picker/main/emoji.js"></script>
```
To use, call the function when the document is ready:
```javascript
$(function() {
  emoji(bottom); // Bottom is the CSS unit for the bottom of the emoji picker
});
```
When using it, you will need 2 elements with IDs:
+ `writeMessage`: this is the input where you want the emojis to be inserted
+ `openEmoji`: the button that toggles the emojis to show/hide

And it should work!
