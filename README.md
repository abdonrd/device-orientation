[![Build status][travis-image]][travis-url]

## \<device-orientation\>

Polymer element to detecting device orientation.

Example:
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="device-orientation.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<template is="dom-bind">
  <device-orientation orientation="{{orientation}}"></device-orientation>
  <ul>
    <li>Alpha: [[orientation.alpha]]</li>
    <li>Beta: [[orientation.beta]]</li>
    <li>Gamma: [[orientation.gamma]]</li>
  </ul>
</template>
```

[travis-image]: https://travis-ci.org/abdonrd/device-orientation.svg?branch=master
[travis-url]: https://travis-ci.org/abdonrd/device-orientation
