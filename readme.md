# About
Estimating distance by using parallax from Gaia Catalogue.
This repo follows Bailer-Jones (2015) recipe to calculate distances.

### Requirements
- Astropy
- Numpy
- Scipy
- Matplotlib


### How
This repo used `uv` as package manager. Install it first. Then sync to install dependencies.

```bash
uv sync
```

If you used other package manager, you know how 😊

### License
[BSD 3-Clause License](./LICENSE)

### References
- [Bailer-Jones, C. A. (2015). Estimating distances from parallaxes. Publications of the Astronomical Society of the Pacific, 127(956), 994.](https://iopscience.iop.org/article/10.1086/683116)
- [Bailer-Jones, C. A. (2018). Inference of cluster distance and geometry from astrometry](https://www2.mpia-hd.mpg.de/homes/calj/cluster_inference.pdf)