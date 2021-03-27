# gFontInput

A simple google font picker for use with input controls. Has a simple font style preview. Lazy loads fonts only when needed. Minimal implementation.

7.15KB gzipped (14.25KB uncompressed)

## Usage

Define your input element somewhere:

    <label>Choose a font: <input type="text" size="40" id="fontInput"></label>

Include the `gfontinput.js` in your html and then create the instance (accepts the id or element node)

    document.addEventListener('DOMContentLoaded', function() {
      gFontInput.create('fontInput');
    });

Click on the input. The picker appears. Click a font to enter its text name as the input value, or click off the input to hide the picker.

## Licence

MIT
