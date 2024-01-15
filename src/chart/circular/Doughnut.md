```tsx
let data = [
  {'name': '臺北市', 'label': '高中以下', 'value': 4914143795516.0},
  {'name': '臺北市', 'label': '大專', 'value': 7336112508338.0},
  {'name': '臺北市', 'label': '研究所', 'value': 2006204037944.0}
];

<Doughnut
  data={data}
  mapper={{
    getX: (d) => d.label,
    getY: (d) => d.value
  }}
  base={{
    title: '臺北市',
    height: 500
  }}
></Doughnut>
```
