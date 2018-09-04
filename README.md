[![Build Status](https://travis-ci.org/biztek/usa-state-list.svg?branch=master)](https://travis-ci.org/biztek/usa-state-list)

[![Sauce Test Status](https://saucelabs.com/buildstatus/biztek_opensource_sauce)](https://saucelabs.com/u/biztek_opensource_sauce)

[![Sauce Test Status](https://saucelabs.com/browser-matrix/biztek_opensource_sauce.svg)](https://saucelabs.com/u/biztek_opensource_sauce)

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/biztek/usa-state-list)
  
[![Published on Vaadin  Directory](https://img.shields.io/badge/Vaadin%20Directory-published-00b4f0.svg)](https://vaadin.com/directory/component/biztekusa-state-list)
  
[![Stars on vaadin.com/directory](https://img.shields.io/vaadin-directory/star/biztekusa-state-list.svg)](https://vaadin.com/directory/component/biztekusa-state-list)

_[Demo and API docs](https://biztek.github.io/usa-state-list/components/usa-state-list)_

## <usa-state-list>

`usa-state-list` is similar to a native browser select element.
`usa-state-list` works with selectable content. The currently selected
item is displayed in the control. If no item is selected, the `label` is
displayed instead.

State drop down list that will include states, outlying territories, armed forces.
Example:
It includes an optional label, error message, invalid, autovalidate and required attributes.
```html
<usa-state-list file-name="jsonFile"></usa-state-list>
<usa-state-list label="label"></usa-state-list>
<usa-state-list error-message="state is required"></usa-state-list>
<usa-state-list invalid="boolean value"></usa-state-list>
<usa-state-list autoValidate="boolean value"></usa-state-list>
<usa-state-list required="boolean value"></usa-state-list>
```
### Validation

If the `auto-validate` attribute is set, element validates when the user not select the state from dropdown menu.

## Install

Install the component using [Bower](http://bower.io/):

```sh
bower install --save biztek/usa-state-list
```

## Usage

Import Custom Element:

```html
<link rel="import" href="bower_components/usa-state-list/usa-state-list.html">
```

And then use it:

```html
<usa-state-list file-name="jsonFile"></usa-state-list>
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b usa-state-list`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push -u origin usa-state-list`
5. Submit a pull request

## License

Licensed under the [Apache 2.0](LICENSE).
