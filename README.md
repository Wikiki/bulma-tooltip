# bulma-tooltip
Bulma's extension to display tooltip on desktop layout

You can easily decide on which side tooltip will be displayed: top, right, bottom or left.

Preview
---
![Tooltip extension](https://img15.hostingpics.net/pics/824111ScreenShot20170719at120642.png)


Usage
---

```
<div class="columns text-center">
  <div class="column">
    <button class="button is-primary tooltip" data-tooltip="Tooltip Text">top tooltip</button>
  </div>
  <div class="column">
    <button class="button is-primary tooltip tooltip-right" data-tooltip="Tooltip Text">right tooltip</button>
  </div>
  <div class="column">
    <button class="button is-primary tooltip tooltip-bottom" data-tooltip="Tooltip Text">bottom tooltip</button>
  </div>
  <div class="column">
    <button class="button is-primary tooltip tooltip-left" data-tooltip="Tooltip Text">left tooltip</button>
  </div>
</div>
