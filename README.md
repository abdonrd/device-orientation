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
    <div>
      <template is="dom-bind">
        <next-code-block></next-code-block>
      </template>
    </div>
  </template>
</custom-element-demo>
```
-->
```html
<device-orientation orientation="{{orientation}}"></device-orientation>
<ul>
  <li>Alpha: [[orientation.alpha]]</li>
  <li>Beta: [[orientation.beta]]</li>
  <li>Gamma: [[orientation.gamma]]</li>
</ul>
```

[travis-image]: https://travis-ci.org/abdonrd/device-orientation.svg?branch=master
[travis-url]: https://travis-ci.org/abdonrd/device-orientation
