[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/arsnebula/nebula-switch)

[![Build Status](https://saucelabs.com/browser-matrix/arsnebula.svg)](https://saucelabs.com/beta/builds/7bb9e6ef718f47c499009ef811b64ae3)

# \<nebula-switch\>

A web component to display a switch control.

* Simple flat switch control
* Customizable icon
* Easily customized using CSS, custom variables and mixins
* Looks great on a light or dark background
* Consistent visual presentation across all browsers
* Supports [WAI-ARIA](https://www.w3.org/TR/wai-aria-practices-1.1/#checkbox) authoring practices for **a11y**

## Installation

```
$ bower install -S arsnebula/nebula-switch
```

## Usage

Import the element:

```html
<link rel="import" href="/bower_components/nebula-switch/nebula-switch.html"> 
```

Declare the element.

```html
<nebula-switch
  checked="{{checked}}"
  on-change="_onChange">
</nebula-switch>
```

Style the element.

```css
nebula-switch {
  --nebula-switch-color: currentColor;
  --nebula-switch-active-color: darkred;
  --nebula-switch-size: 1.5rem;
}
```

*For more information on element properties and methods see the element API documentation.*

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Change Log

See [CHANGELOG](/CHANGELOG.md)

## License

See [LICENSE](/LICENSE.md)