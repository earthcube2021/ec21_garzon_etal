# Exploring Research Data Repositories with geoextent.

This notebook presents [geoextent](https://github.com/o2r-project/geoextent), a Python library for reliably extracting the geospatial and temporal extents of files, directories, and repository records. The geospatial and temporal metadata of research data could greatly benefit the discovery of relevant and related datasets (Gregory et al., 2018). However, it is underused in scientific data repositories except for specialised repositories. Much more scientific disciplines collect data and publish work that has some temporal or spatial relation. These datasets may not be connected through regular search indices based on keywords or full texts. The library geoextent presented in this notebook helps to understand the potential of extract information from files shared in data repositories and may be used to integrate geospatial and temporal metadata into repository infrastructures.

## Showcase

To run the showcase notebook, install [JupyterLab](https://jupyter.org/) or the classic Jupyter Notebook and then start a local server as shown below.
If your IDE has support for the Jupyter format, installing `ipykernel` might be enough.
We recommend running the below commands in a virtual environment as described [here](https://jupyter-tutorial.readthedocs.io/en/latest/first-steps/install.html).
The notebook must be [trusted](https://jupyter-notebook.readthedocs.io/en/stable/security.html#notebook-security).

```bash
cd showcase
pip install -r requirements.txt
pip install -r showcase/requirements.txt
pip install -e .

jupyter trust showcase/SG_01_Exploring_Research_Data_Repositories_with_geoextent.ipynb
jupyter lab
```

Then open the local Jupyter Notebook server using the displayed link and open the notebook (`*.ipynb` files) in the `showcase/` directory.
Consult the documentation on [paired notebooks based on Jupytext](https://github.com/mwouts/jupytext/blob/master/docs/paired-notebooks.md) before editing selected notebooks.

## How to cite

> Garzón, Sebastian and Nüst, Daniel, 2021. Exploring Research Data Repositories with geoextent.

## License

`geoextent` is licensed under MIT license, see file [LICENSE](https://github.com/o2r-project/geoextent/blob/master/LICENSE).

This project is developed as part of the   [DFG-funded](https://o2r.info/about/#funding) research project Opening Reproducible Research (o2r, [https://o2r.info](https://o2r.info)).

Copyright (C) 2021 - o2r project.
