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
    &lt;img src=&quot;big-logo.gif&quot; class=&quot;mobile-hide mobile-p-hide&quot;&gt;&lt;/div&gt;
```
```html
    &lt;img src=&quot;small-logo.gif&quot; class=&quot;desktop-hide tab-hide tab-p-hide&quot;&gt;&lt;/div&gt;
```

## Files
  - Hide.less: Edit this file
  - Hide.css: Compiled version of this module