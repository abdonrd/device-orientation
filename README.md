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
      <dom-bind>
        <template is="dom-bind">
          <next-code-block></next-code-block>
        </template>
      </dom-bind>
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
      <dom-bind>
        <template is="dom-bind">
          <next-code-block></next-code-block>
        </template>
      </dom-bind>
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
  <li>Acceleration
    <ul>
      <li>x: [[motion.acceleration.x]]</li>
      <li>y: [[motion.acceleration.y]]</li>
      <li>z: [[motion.acceleration.z]]</li>
    </ul>
  </li>
  <li>Acceleration with gravity
    <ul>
      <li>x: [[motion.accelerationIncludingGravity.x]]</li>
      <li>y: [[motion.accelerationIncludingGravity.y]]</li>
      <li>z: [[motion.accelerationIncludingGravity.z]]</li>
    </ul>
  </li>
  <li>Rotation rate
    <ul>
      <li>α: [[motion.rotationRate.alpha]]</li>
      <li>β: [[motion.rotationRate.beta]]</li>
      <li>γ: [[motion.rotationRate.gamma]]</li>
    </ul>
  </li>
  <li>Interval: [[motion.interval]]</li>
</ul>
```
