### `<Radio />`

Use the `<Radio />` component to set the HTML `<input type='radio' />` element

use it with `<Label />` 
```
<div onChage={onChange}>
  <Label fontSize="14px">
    <Radio checked />
    selected
  </Label>
  <Label fontSize="14px">
    <Radio disabled />
    can't choose this one
  </Label>
  <Label fontSize="14px">
    <Radio />
    not selected
  </Label>
</div>
```

Prop | Type | Description
---|---|---
checked | boolean | item checked
disabled | boolean | item disabled