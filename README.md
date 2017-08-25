# bulma-tooltip
Bulma's extension to display tooltip on desktop layout

You can easily decide on which side tooltip will be displayed: top, right, bottom or left.

(find all my bulma's extensions [here](https://wikiki.github.io/bulma-extensions))

Preview
---
![Tooltip extension](https://img15.hostingpics.net/pics/824111ScreenShot20170719at120642.png)


Usage
---

```html
<div class="columns text-center">
  <div class="column">
    <button class="button is-primary tooltip" data-tooltip="Tooltip Text">top tooltip</button>
  </div>
  <div class="column">
    <button class="button is-primary tooltip is-tooltip-right" data-tooltip="Tooltip Text">right tooltip</button>
  </div>
  <div class="column">
    <button class="button is-primary tooltip is-tooltip-bottom" data-tooltip="Tooltip Text">bottom tooltip</button>
  </div>
  <div class="column">
    <button class="button is-primary tooltip is-tooltip-left" data-tooltip="Tooltip Text">left tooltip</button>
  </div>
</div>
```

Integration
---
- Clone the [bulma repo](https://github.com/jgthms/bulma)
- Under the `sass` folder, create a new folder called `extensions`
- In this new folder, create a new file `tooltip.sass`
- Copy the code form the `bulma-tooltip repo`'s [tooltip.sass](https://github.com/Wikiki/bulma-tooltip/blob/master/tooltip.sass) file into your new file
- In the same folder create a new file `_all.sass` (this is not required, but will help when you add more extensions)
- In this file add this code:
```
@charset "utf-8"
@import "tooltip.sass"
```
At the end of the `bulma.sass` file, add this line: `@import "sass/extensions/_all"`

Now, you can just build the bulma project with `npm run build`, and the output will be available in the `css folder`.
