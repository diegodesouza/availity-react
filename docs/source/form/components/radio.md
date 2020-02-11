---
title: <Radio />
summary: Inputs of type radio. Radios should be wrapped in a RadioGroup.
---

## Example

```jsx live=true viewCode=true
import { Radio, RadioGroup } from '@availity/form';
import { Button } from 'reactstrap';

<Form
  initialValues={{
    hello: '',
  }}
  onSubmit={() => {}}
  validationSchema={yup.object().shape({
    hello: yup.string().required('This field is required'),
  })}
>
  <RadioGroup name="hello" label="Radio Group">
    <Radio label="Radio One" value="uno" />
    <Radio label="Radio Two" value="dos" />
    <Radio label="Radio Three" value="tres" />
  </RadioGroup>
  <Button type="submit">Submit</Button>
</Form>;
```

## Props

### `id?: string`

Should match `<RadioGroup />` name for validation.

### `label?: ReactNode`

Label for the checkbox.

### `value?: string`

Value of the checkbox.

### `disabled?: boolean`

Disables the checkbox.
