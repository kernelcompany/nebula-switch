# \<nebula-switch\>

`<nebula-switch>` is a web component to display a configurable switch control.

## Import

```html
<link rel="import" href="/bower_components/nebula-switch/nebula-switch.html"> 
```

## Usage

Add the element. The following demonstrates common properties and event receivers.

```html
<nebula-switch
  checked="{{checked}}"
  on-checked-changed="_onCheckedChanged">
</nebula-switch>
```

You can customize the icon, by specifying the name of an `iron-icon` in the icon registry. It is recommended you use an icon with a solid background.

```html
<nebula-switch
  icon="icons:favorite">
</nebula-switch>
```

## Style

Style the element using standard CSS properties or the following variables:

Custom property | Description | Default
:--- | :---
`--nebula-switch-color` | The color of the element. | dimgrey
`--nebula-switch-checked-color` | The color of the element when checked. | inherit
`--nebula-switch-size` | The height and width of the element. | 1.5rem

The element also inherits default values from the following global theme styles. If a global theme variable has not been set, it will use the local default.

Custom property | Description | Default
:--- | :--- | :---
`--nebula-ui-primary-color | The theme color of the element when checked. | teal
`--nebula-ui-margin` | The margin of the element. | 4px
`--nebula-ui-border-width` | The border width of the element. | 0px
`--nebula-ui-border-radius` | The border-radius of the element. | 2px
`--nebula-ui-disabled-opacity` | Opacity of the element when disabled. | 0.6