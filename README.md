
# Earthquake Visualizer 

This project is a Python-based earthquake visualizer that utilizes data from the US Geological Survey (USGS) to create interactive maps showcasing earthquake occurrences. The visualizer utilizes the Plotly library for data visualization purposes.





## Run Locally

Clone the project

```bash
  git clone https://link-to-project
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```


## Screenshots




## Features

- Available for any date and time
- Available for any region
- Available for range of magnitudes of earthquake
- Robust 
- User-Friendly 


## Badges

[![python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)](https://www.python.org)

[![plotly](https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white)](https://plotly.com/python/)




[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)


## API Reference

#### Get all items

```http
  GET https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/{???}.csv

```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `period` | `string` | **Required**.  |
| `region` | `string` | **Required**.  |
| `min_mag` | `integer` | **Required**.  |



