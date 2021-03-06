# geoML
Spatial modeling using machine learning concepts.

This is a work in progress. Current functionality includes:

* Gaussian Process modeling in 1D, 2D, and 3D, with 
anisotropy ellipsoid;
* Support for directional data (structural geology
measurements, scalar field gradients, etc.);
* Support for classification with boundary data (points
lying in the boundary between two rock types);
* Limited 3D plotting with plotly;
* Back-end powered by TensorFlow;
* Gradient-free training with particle swarm optimization.

## Installation
Clone the repo and update the path to include the package's folder.

Dependencies:
* `scikit-image`
* `pandas`
* `numpy`
* `tensorflow` (preferably `tensorflow-gpu`)
* `tensorflow-probability`
* `plotly` for 3D visualization

## Examples
The following notebooks demonstrate the capabilities of the package.

* [Walker Lake](https://colab.research.google.com/drive/1zH-dAytMwR_OocDgJWE3Sy8pbcq0PdAJ)
* [2D classification with structural constraints](https://colab.research.google.com/drive/1eiIa8kavRIp5SK5R89ozkIj5lmeRrx9x)
* [Sunspot cycle prediction](https://colab.research.google.com/drive/1tbc7I8K0NmpCM4mOZZ1kghlXWnLamE5l)
* [3D classification](https://colab.research.google.com/drive/1oC8b-eCgrfLxMcVsxVv6EvQyeKelUUjE)
* [Potential field modeling using only directional data](https://colab.research.google.com/drive/141zuv7VH431fVt0dwHQiKCSJmYd6E9u8)

