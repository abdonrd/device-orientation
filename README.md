[![Build status](https://travis-ci.org/abdonrd/device-orientation.svg?branch=master)](https://travis-ci.org/abdonrd/device-orientation)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/abdonrd/device-orientation)

## \<device-orientation\> & \<device-motion\>

Web Components (with Polymer) to detecting device orientation and motion.

### \<device-orientation\>

Detecting device orientation.

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
<device-orientation
    api-supported="{{apiSupported}}"
    sensors-available="{{sensorsAvailable}}"
    orientation="{{orientation}}">
</device-orientation>

<ul>
  <li>API supported: [[apiSupported]]</li>
  <li>Sensors available: [[sensorsAvailable]]</li>
  <li>Absolute: [[orientation.absolute]]</li>
  <li>Alpha: [[orientation.alpha]]</li>
  <li>Beta: [[orientation.beta]]</li>
  <li>Gamma: [[orientation.gamma]]</li>
</ul>
```

### \<device-motion\>

Detecting device motion.

Example:
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
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
<device-motion
    api-supported="{{apiSupported}}"
    sensors-available="{{sensorsAvailable}}"
    motion="{{motion}}">
</device-motion>

<ul>
  <li>API supported: [[apiSupported]]</li>
  <li>Sensors available: [[sensorsAvailable]]</li>
  <li>Acceleration on x: [[motion.acceleration.x]]</li>
  <li>Acceleration on y: [[motion.acceleration.y]]</li>
  <li>Acceleration on z: [[motion.acceleration.z]]</li>
  <li>Acceleration with gravity on x: [[motion.accelerationIncludingGravity.x]]</li>
  <li>Acceleration with gravity on y: [[motion.accelerationIncludingGravity.y]]</li>
  <li>Acceleration with gravity on z: [[motion.accelerationIncludingGravity.z]]</li>
  <li>Rotation rate on α: [[motion.rotationRate.alpha]]</li>
  <li>Rotation rate on β: [[motion.rotationRate.beta]]</li>
  <li>Rotation rate on γ: [[motion.rotationRate.gamma]]</li>
  <li>Interval: [[motion.interval]]</li>
</ul>
```
