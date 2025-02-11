# Rate

Graphical representation of the degree of rating scale.

## When to Use

Useful for showing things ratings and quick scoring.

## Demos

<code src="./demos/demo1.tsx"></code>

## Rate

### Props

| Name         | Description                                    | Type                      | Default          |
| ------------ | ---------------------------------------------- | ------------------------- | ---------------- |
| allowClear   | Whether to allow clearing after another click. | `boolean`                 | `true`           |
| allowHalf    | Whether to allow the selection of half.        | `boolean`                 | `false`          |
| character    | Custom character.                              | `ReactNode`               | `<StarFilled />` |
| count        | Total number of stars.                         | `number`                  | `5`              |
| defaultValue | The default value of rate.                     | `number`                  | `0`              |
| readOnly     | The component is uninteractable when `true`.   | `boolean`                 | `false`          |
| value        | The value of rate.                             | `number`                  | -                |
| onChange     | Callback when select.                          | `(value: number) => void` | -                |

### CSS Variables

| Name             | Description               | Default                  |
| ---------------- | ------------------------- | ------------------------ |
| --star-size      | Star size.                | `24px`                   |
| --active-color   | Fill color when active.   | `#ffd21e`                |
| --inactive-color | Fill color when inactive. | `var(--adm-color-light)` |
