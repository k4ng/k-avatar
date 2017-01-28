# \<digital-clock\>

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/telecomsante/digital-clock)

A simple clock component, displaying the current date and time into the local format.

## Quick example

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="digital-clock.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<digital-clock></digital-clock>
<audio src="demo/Zen_Temple_Bell.mp3" id="alarm"></audio>
<script>
const clock = document.querySelector('digital-clock');
let now = new Date();
now.setMinutes(now.getMinutes() + 1);
now.setSeconds(0);

clock.alarm = now.toISOString();
clock.addEventListener('clock-alarm', () => {
  document.getElementById("alarm").play();
});
</script>
```

The component is licensed under the [ISC License](LICENSE.md)

Demo and doc are available on https://telecomsante.github.io/digital-clock/
