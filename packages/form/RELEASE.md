### v0.6.6
- implement validation hooks with form's `triggerValidationOn` prop
- types and intellisense improvements
- validation support for RadioGroup
- form's `action` and `method` props

### v0.6.5
- fix deps

### v0.6.4
- Form component's new `validateOnLoad` property
- FormGroup.setValue() method to set values for the whole form
- fix for Radio Group's inputs not having unique IDs

### v0.6.3
- make `Checkbox.checked` optional

### v0.6.2
- fix broken `ControlConfig`

### v0.6.1
- fix wrong dependency version

## v0.6.0
- deprecate `labelPosition` prop
- implement TextArea control
- add method `setValidators` to FormControl
- implement `readOnly` flag
- implement Dropdown control

### v0.5.1 - v0.5.2
- use @astro-reactive/common

### v0.5.1
- fix for dynamic import of validator causing errors (breaks independence)

## v0.5.0
- server-rendered validation errors (when control was set with invalid value)
- radio control accepts array of value or RadioOption
- added tests for form components

### v0.4.5
- update project documentations

### v0.4.4
- `validators` property in ControlConfig to set validators for a control

### v0.4.1
- set `showValidationHints` to true to show validation hints

## v0.3.0
- new control configuration type `ControlConfig`

### v0.2.7
- updated project logo

### v0.2.6
- support single `FormGroup` as input to the `Form` component
- implement `Form` component input prop `theme`
- add initial implementation of `FormControl` `isPristine` and `isValid` states
- filter out control with type 'submit' from the FormGroup.controls
- implement the submitControl Form input prop
- implement the FormControl placeholder attribute

### v0.2.4 to v0.2.5
- update package README
- update dependencies

### v0.2.2
- initial light and dark mode scaffold
- update package README

### v0.2.1
- FormGroup.get(name) - returns the FormControl with matching name
- FormControl.setValue(value) - sets the FormControl value
