[![Build status][travis-image]][travis-url]
[![Published on webcomponents.org][webcomponents-image]][webcomponents-url]

## \<device-orientation\>

Polymer elements to detecting device orientation and motion.

Example:
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="device-orientation.html">
    <link rel="import" href="device-motion.html">
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
<device-orientation
    api-supported="{{orientationApiSupported}}"
    sensors-available="{{orientationSensorsAvailable}}"
    orientation="{{orientation}}">
</device-orientation>

<ul>
  <li>API supported: [[orientationApiSupported]]</li>
  <li>Sensors available: [[orientationSensorsAvailable]]</li>
  <li>Absolute: [[orientation.absolute]]</li>
  <li>Alpha: [[orientation.alpha]]</li>
  <li>Beta: [[orientation.beta]]</li>
  <li>Gamma: [[orientation.gamma]]</li>
</ul>

<device-motion
    api-supported="{{motionApiSupported}}"
    sensors-available="{{motionSensorsAvailable}}"
    motion="{{motion}}">
</device-motion>

<ul>
  <li>API supported: [[motionApiSupported]]</li>
  <li>Sensors available: [[motionSensorsAvailable]]</li>
  <li>Acceleration on x: [[motion.acceleration.x]]</li>
  <li>Acceleration on y: [[motion.acceleration.y]]</li>
  <li>Acceleration on z: [[motion.acceleration.z]]</li>
  <li>Acceleration with gravity on x: [[motion.accelerationIncludingGravity.x]]</li>
  <li>Acceleration with gravity on y: [[motion.accelerationIncludingGravity.y]]</li>
  <li>Acceleration with gravity on z: [[motion.accelerationIncludingGravity.z]]</li>
  <li>Rotation rate on &alpha;: [[motion.rotationRate.alpha]]</li>
  <li>Rotation rate on &beta;: [[motion.rotationRate.beta]]</li>
  <li>Rotation rate on &gamma;: [[motion.rotationRate.gamma]]</li>
  <li>Interval: [[motion.interval]]</li>
</ul>
```

[travis-image]: https://travis-ci.org/abdonrd/device-orientation.svg?branch=master
[travis-url]: https://travis-ci.org/abdonrd/device-orientation
[webcomponents-image]: https://img.shields.io/badge/webcomponents.org-published-blue.svg
[webcomponents-url]: https://webcomponents.org/element/abdonrd/device-orientation
