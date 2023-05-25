# Data

This is the README.md this project.

## Table 

<Table
  cols={[
    {
      key: 'id',
      name: 'ID'
    },
    {
      key: 'firstName',
      name: 'First name'
    },
    {
      key: 'lastName',
      name: 'Last name'
    },
    {
      key: 'age',
      name: 'Age'
    }
  ]}
  data={[
    {
      age: 35,
      firstName: 'Jon',
      id: 1,
      lastName: 'Snow'
    },
    {
      age: 42,
      firstName: 'Cersei',
      id: 2,
      lastName: 'Lannister'
    },
    {
      age: 45,
      firstName: 'Jaime',
      id: 3,
      lastName: 'Lannister'
    },
    {
      age: 16,
      firstName: 'Arya',
      id: 4,
      lastName: 'Stark'
    },
    {
      age: 44,
      firstName: 'Ferrara',
      id: 7,
      lastName: 'Clifford'
    },
    {
      age: 36,
      firstName: 'Rossini',
      id: 8,
      lastName: 'Frances'
    },
    {
      age: 65,
      firstName: 'Harvey',
      id: 9,
      lastName: 'Roxie'
    }
  ]}
/>
 
## Vega Lite Line Chart from URL 

<VegaLite spec={ { "$schema": "https://vega.github.io/schema/vega-lite/v5.json", "data": {"url": "data_2.csv"}, "width": 600, "height": 250, "mark": "line", "encoding": { "x": {"field": "Time", "type": "temporal"}, "y": {"field": "Anomaly (deg C)", "type": "quantitative"}, "tooltip": {"field": "Anomaly (deg C)", "type": "quantitative"} } } } />
