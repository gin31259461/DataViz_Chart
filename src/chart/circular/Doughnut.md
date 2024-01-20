```tsx
let data = [{'name': 'month count', 'label': '8', 'value': 22}, {'name': 'month count', 'label': '6', 'value': 17}, {'name': 'month count', 'label': '12', 'value': 15}, {'name': 'month count', 'label': '9', 'value': 14}, {'name': 'month count', 'label': '11', 'value': 13}, {'name': 'month count', 'label': '10', 'value': 12}, {'name': 'month count', 'label': '7', 'value': 12}, {'name': 'month count', 'label': '1', 'value': 0}, {'name': 'month count', 'label': '2', 'value': 0}, {'name': 'month count', 'label': '3', 'value': 0}, {'name': 'month count', 'label': '4', 'value': 0}, {'name': 'month count', 'label': '5', 'value': 0}];

<Doughnut
  data={data}
  mapper={{
    getX: (d) => d.label,
    getY: (d) => d.value
  }}
  base={{
    title: 'Month Count',
    height: 500
  }}
></Doughnut>
```
