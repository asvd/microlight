microlight.js
=============

*microlight.js* is a micro-library (2.2k minified) which improves
 readability of code snippets by highlighting, for any programming
 language, yet without attaching additional language packages or
 styles:

![preview]
(http://asvd.github.io/microlight/microlight-preview-big.png)

For demos and usage guide, refer to https://asvd.github.io/microlight

--

Follow me on twitter: https://twitter.com/asvd0

## CSS

The following are the css rules to target the elements within microlight

```css
.microlight span[data_microlight_type="not-formatted"] {
    opacity: 1;
}

.microlight span[data_microlight_type="keywords"] {
    opacity: 0.9;
}

.microlight span[data_microlight_type="punctuation"] {
    opacity: 0.5;
}

.microlight span[data_microlight_type="strings-regex"] {
    opacity: 0.7;
}

.microlight span[data_microlight_type="comments"] {
    opacity: 0.4;
}
```