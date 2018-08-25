# themable-css-tooltip
Fully customizable/themable tooltip written in pure CSS only.

## WARNING
Internet Explorer does not support the var() function. Consider using a polyfill.

### Overview
**themable-css-tooltip** is a pure CSS implementation of tooltip functionality for web apps/sites. This allows for easier configuration and theming.

It exposes a series of css classes to enable features and control positioning.

### Usage
```html
    <div class="tooltip north olive sticky fixed" alt="This example uses the:
    sticky and fixed features
    as well as
    north positioning
    and olive theme preset">
        A css tooltip will show up while hovering this element.
    </div>
```
### Features
**.fixed** - makes the tooltip width fixed (see --tooltip-multiline-width variable in configuration section)
**.sticky** - forces the tooltip to appear while hovered
**.mini** - smaller version of the tooltip

### Positioning
**.north** - positions the tooltip above the element
**.east** - positions the tooltip on the element`s right side
**.south** - positions the tooltip below the element
**.west** - positions the tooltip on the element`s left side

### Configuration
* --tooltip-spacing-base: 2px;
* --tooltip-multiline-width: 20em;
* --tooltip-font-size: 1em;
* --tooltip-font-family: Arial, 'Helvetica', sans-serif;
* --tooltip-background-color: black;
* --tooltip-border-color: red;
* --tooltip-border-width: var(--tooltip-spacing-base);
* --tooltip-border-style: solid;
* --tooltip-border-radius: calc(var(--tooltip-spacing-base) * 2);
* --tooltip-shadow-color: rgba(0,0,0,0.8);
* --tooltip-shadow-x: 0px;
* --tooltip-shadow-y: 0px;
* --tooltip-shadow-spread: 5px;
* --tooltip-shadow-size: 0px;
* --tooltip-color: white;
* --tooltip-triangle-size: 12px;