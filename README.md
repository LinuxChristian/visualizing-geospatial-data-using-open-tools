# Geospatial data visulization using open tools

This repo contains a presentation about Geospatial data visulization. It is structured into three separate sections,

- `NoCode`: Examples on using Kepler.gl directly in the browser. The folder mainly contains code to preprocess files.
- `LowCode`: Examples on using deck.gl in Jupyter notebooks for data exploration.
- `HighCode`: Example of creating an standalone website that displays information directly from a local JSON file.

**Tools**

The examples showcases two libraries from the Uber [Vis.gl](https://vis.gl/) application suite built for large scale geospatial data visualization.
- [Kepler.gl](https://kepler.gl/): Kepler.gl is a powerful open source geospatial analysis tool for large-scale data sets. No installation required.
- [Deck.gl](https://deck.gl/): WebGL-powered framework for visual exploratory data analysis of large datasets. Developers use Deck as a framework to build application from.

## Getting started

Get the required Python dependencies to run,

```bash
pip install -r requirements.txt
```

## Datasets

All examples are based on data from the Danish Energy Agency. The data shows Wind turbine data from Denmark (on- and offshore). The data is available on the agencies [website](https://ens.dk/service/statistik-data-noegletal-og-kort/download-gis-filer).