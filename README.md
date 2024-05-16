# **Auto3D**
<a href="https://pypi.org/project/Auto3D/" target="_blank"><img src="https://img.shields.io/badge/pypi-url-informational" alt="pypi_link"></a>
![PyPI](https://img.shields.io/pypi/v/Auto3D)
![PyPI - Downloads](https://img.shields.io/pypi/dm/Auto3D)
![PyPI - License](https://img.shields.io/pypi/l/Auto3D)

<img width="1109" alt="image" src="https://user-images.githubusercontent.com/60156077/180329514-c72d7b92-91a8-431b-9339-1445d5cacd20.png">




**Auto3D** is a Python package for generating low-energy conformers from SMILES/SDF. Over the development process, we also added the APIs for computing single point energies, optimizing geometries, find stable tautomers. Auto3D can be imported as a Python library, or be excuted from the terminal.

Please check out the information at [**documentation**](https://auto3d.readthedocs.io/en/latest/index.html), including [installation](https://auto3d.readthedocs.io/en/latest/installation.html), [usage](https://auto3d.readthedocs.io/en/latest/usage.html), [API](https://auto3d.readthedocs.io/en/latest/api.html) and [citation](https://auto3d.readthedocs.io/en/latest/citation.html).

- **Jupyter notebook examples** can be found [here](https://github.com/isayevlab/Auto3D_pkg/tree/main/example)
- To-do list for **improvement and new features** can be found [here](https://github.com/isayevlab/Auto3D_pkg/discussions). You are welcomed to share your thoughts.
- Bugs go to the [issues](https://github.com/isayevlab/Auto3D_pkg/issues)
- **AIMNet2**: The default model in Auto3D is AIMNet2 since 2.2.1. If you specify optimizing_engine="AIMNET", it actually uses AIMNet2. The old AIMNet model has been deprecated since Auto3D 2.2.1, and every call to “AIMNET” refers to the AIMNet2 model.
