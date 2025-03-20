# napari-stereoTis

[![License](https://img.shields.io/pypi/l/napari-stereoTis.svg?color=green)](https://github.com/secretloong/napari-stereoTis/raw/main/LICENSE)
[![PyPI](https://img.shields.io/pypi/v/napari-stereoTis.svg?color=green)](https://pypi.org/project/napari-stereoTis)
[![Python Version](https://img.shields.io/pypi/pyversions/napari-stereoTis.svg?color=green)](https://python.org)
[![napari hub](https://img.shields.io/endpoint?url=https://api.napari-hub.org/shields/napari-stereoTis)](https://napari-hub.org/plugins/napari-stereoTis)

## Description

A napari plugin for spatial transcriptomics data analysis and visualization. This plugin provides tools for processing and analyzing spatial transcriptomics data using bio-photos, with a focus on cell aggregation detection, tissue segmentation, and data visualization.

## Features

- **Cell Aggregation Analysis**: Detect and analyze cell aggregates using OPTICS clustering algorithm
- **Tissue Segmentation**: Visualize gene signature scores across spatial coordinates and tissue segmentation
- **Data Visualization**: Interactive visualization of spatial transcriptomics data
- **Data Export**: Export processed data into multi-columns csv for further merging with anndata or seurat objects

## Installation

You can install `napari-stereoTis` via [pip]:

```bash
pip install napari-stereoTis
```

## Usage

1. Start napari:
   ```bash
   napari
   ```

2. Load the plugin from the Plugins menu


## Input Data Format

The plugin accepts CSV files with the following format:
- For cell aggregation: CSV with x,y coordinates (with header)
- For signature scoring: CSV with x,y coordinates and score values (with header)

## Requirements

- napari
- numpy
- scikit-image
- opencv-python
- pandas
- matplotlib

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

Distributed under the terms of the [BSD-3] license,
"napari-stereoTis" is free and open source software.

## Issues

If you encounter any problems, please [file an issue] along with a detailed description.

[napari]: https://github.com/napari/napari
[BSD-3]: http://opensource.org/licenses/BSD-3-Clause
[file an issue]: https://github.com/secretloong/napari-stereoTis/issues