# themable-css-tooltip - Pure CSS tooltip!
Fully customizable/themable tooltip written in pure CSS.

## WARNING
Internet Explorer does not support the var() function. Consider using a polyfill.

### Overview
**themable-css-tooltip** is a pure CSS implementation of tooltip functionality for web apps/sites.
This allows for easier configuration and theming.
The text shown in the tooltip is placed in the **alt** attribute of the html element in order to automatically expose it to screenreaders/narrators and alternative image content.

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

**.east** - positions the tooltip on the right side

**.south** - positions the tooltip below the element

**.west** - positions the tooltip on the left side

### Configuration
* **--tooltip-spacing-base** - the common multiplier for all spacing values
* **--tooltip-multiline-width** - fixed width value for multiline tooltips
* **--tooltip-font-size** - the tooltip`s font size
* **--tooltip-font-family** - the tooltip`s font family
* **--tooltip-background-color** - the background color
* **--tooltip-border-color** - border color
* **--tooltip-border-width** - border width
* **--tooltip-border-style** - border style
* **--tooltip-border-radius** - border radius
* **--tooltip-shadow-color** - shadow color
* **--tooltip-shadow-x** - shadow horizontal offset
* **--tooltip-shadow-y** - shadow vertical offset
* **--tooltip-shadow-spread** - shadow spread
* **--tooltip-shadow-size** - shadow size
* **--tooltip-color** - the text color
* **--tooltip-triangle-size** - triangle size