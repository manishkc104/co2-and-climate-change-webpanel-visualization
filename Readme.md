<div align="center">
  <h3 align="center">Co2 and Climate Change Web Panel Visualization</h3>
</div>

<details open>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#introduction">Introduction</a>
    </li>
     <li>
      <a href="#built-with">Built With</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
    </li>
  </ol>
</details>

## Introduction

Interactive visualization dashboard for Sustainble Energy in Python with Panel.

Panel is an open-source Python library designed to streamline the development of robust tools, dashboards, and complex applications entirely within Python. With a comprehensive philosophy, Panel integrates seamlessly with the PyData ecosystem, offering powerful, interactive data tables, visualizations, and much more, to unlock, visualize, share, and collaborate on your data for efficient workflows.

https://github.com/manishkc104/co2-and-climate-change-webpanel-visualization/assets/43213617/2f912447-a352-44d5-bcef-b9fda583f1d1

## Built With

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)

## Getting Started

This section describes how you can setup the project locally. To get the local copy up and running follow these simple steps.

### Clone the repo

```sh
git clone https://github.com/manishkc104/co2-and-climate-change-webpanel-visualization.git
```

### To load the csv file replace the filelocation with our current file location

```
df = pd.read_csv(replace your file location)
```

### To serve the dashboard locally, use the command:

```
panel serve Co2_Dashboard.ipynb
```
