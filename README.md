# CSS Online Options

## About
Simple library of Material Design based elements.

## Usage
Table of contents:

- [CSS Online Options](#css-online-options)
  - [About](#about)
  - [Usage](#usage)
    - [Forms](#forms)
    - [Tooltips](#tooltips)
    - [SASS Variables](#sass-variables)


### Forms
Classes:
* `text-field`
  * `text-field__input`
    * `text-field__input--textarea`
  * `text-field__label`
* `checkbox`
  * `checkbox__input`
  * `checkbox__label`
* `radio`
  * `radio__input`
  * `radio__label`
* `switch`
  * `switch__input`
  * `switch__label`

Example:
```html
<!-- text input -->
<div class="text-field">
    <input type="text" class="text-field__input" placeholder="John Doe" id="name">
    <label for="name" class="text-field__label">Last Name</label>
</div>

<!-- textarea -->
<div class="text-field">
    <textarea type="text" class="text-field__input text-field__input--textarea" id="about">I'm awesome!</textarea>
    <label for="about" class="text-field__label">Something about you</label>
</div>

<!-- switch (checkbox) -->
<div class="switch">
    <input type="checkbox" id="switch1" class="switch__input" checked>
    <label for="switch1" class="switch__label">Switch 1</label>
</div>

<!-- radio button -->
<div class="radio">
    <input type="radio" name="radio" id="radio1" class="radio__input" checked>
    <label for="radio1" class="radio__label">Radio 1</label>
</div>
```
Both `.checkbox` and `.switch` classes are intended for checkboxes.

### Tooltips
Classes:
* `tooltip--top`
* `tooltip--right`
* `tooltip--bottom`
* `tooltip--left`

Example:
```html
<span class="tooltip--top" data-tooltip="I'm at the top!">tooltip--top</span>

<span class="tooltip--right" data-tooltip="I'm on the right!">tooltip--right</span>

<span class="tooltip--bottom" data-tooltip="I'm at the bottom!">tooltip--bottom</span>

<span class="tooltip--left" data-tooltip="I'm on the left!">tooltip--left</span>
```

### SASS Variables
If you are using SASS you can adjust many aspects of library using variables.
