## Getting started

The Hide module allows you to hide elements based a break point.

You can assign the Hide classes to anything and use as many as you like to toggle their visibility.

One example is to show a large and complex logo for desktop and tablet users also set to Hide for mobile. A smaller, simpler logo can be set to Hide for Desktop/Tablet views but will be revealed for mobile devices.

  - desktop-hide  = Hide on Desktops
  - tab-hide      = Hide on Landscape Tablets
  - tab-p-hide    = Hide on Portrait Tablets
  - mobile-hide   = Hide on Landscape Mobiles
  - mobile-p-hide = Hide on Portrait Mobiles

## Markup
```html
    <img src="big-logo.gif" class="mobile-hide mobile-p-hide"></div>
```
```html
    <img src="small-logo.gif" class="desktop-hide tab-hide tab-p-hide"></div>
```

## Files
  - Hide.less: Edit this file
  - Hide.css: Compiled version of this module