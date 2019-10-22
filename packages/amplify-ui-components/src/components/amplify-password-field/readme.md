# amplify-password-field



<!-- Auto Generated Below -->


## Properties

| Property            | Attribute     | Description                                                                     | Type                                | Default                |
| ------------------- | ------------- | ------------------------------------------------------------------------------- | ----------------------------------- | ---------------------- |
| `fieldId`           | `field-id`    | Based on the type of field e.g. sign in, sign up, forgot password, etc.         | `string`                            | `PASSWORD_SUFFIX`      |
| `handleInputChange` | --            | The callback, called when the input is modified by the user.                    | `(inputEvent: Event) => void`       | `undefined`            |
| `hint`              | `hint`        | Used as the hint in case you forgot your password, etc.                         | `FunctionalComponent<{}> \| string` | `undefined`            |
| `label`             | `label`       | Used for the password label                                                     | `string`                            | `PASSWORD_LABEL`       |
| `placeholder`       | `placeholder` | Used for the placeholder label                                                  | `string`                            | `PASSWORD_PLACEHOLDER` |
| `required`          | `required`    | The required flag in order to make an input required prior to submitting a form | `boolean`                           | `false`                |


## Dependencies

### Used by

 - [amplify-auth-fields](../amplify-auth-fields)

### Depends on

- [amplify-form-field](../amplify-form-field)

### Graph
```mermaid
graph TD;
  amplify-password-field --> amplify-form-field
  amplify-form-field --> amplify-label
  amplify-form-field --> amplify-input
  amplify-form-field --> amplify-hint
  amplify-auth-fields --> amplify-password-field
  style amplify-password-field fill:#f9f,stroke:#333,stroke-width:4px
```

----------------------------------------------

*Built with [StencilJS](https://stenciljs.com/)*