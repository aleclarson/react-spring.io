| Property | Type             | Required | Default      | Description                                                                                                                             |
| -------- | ---------------- | -------- | ------------ | --------------------------------------------------------------------------------------------------------------------------------------- |
| keys     | fn/undefined/any | false    | item => item | Item keys (the same keys you'd hand over to react in a list). If you specify items, keys can be an accessor function (item => item.key) |
| from     | obj              | false    | -            | Base values, optional                                                                                                                   |
| to       | obj              | false    | -            | Animates to ...                                                                                                                         |
| items    | undefined/any    | true     | -            | An array of items to be displayed, use this if you need access to the actual items when distributing values as functions (see above)    |
| children | fn               | true     | -            | A single function-child that receives the individual item and return a functional component (item, index) => props => view)             |
| reverse  | bool             | false    | -            | When true the trailing order is switched, it will then trail bottom to top                                                              |
