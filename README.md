# Video interview question

This repository contains a dataset:
- SST_and_CO2FLUX.nc

And a Jupyter Notebook that loads these data and performs some computation:
- Assignment.ipynb

Please address the questions in the notebook and plan to walk us through your response on the video.

The notebook requires a handful of Python packages. A suitable conda environment is described in 
- environment.yaml

If you have these packages already installed, you can proceed to working on `Assignment.ipynb`.

If you need to create this environment using conda, we recommend installing
[miniconda](https://docs.conda.io/en/latest/miniconda.html). 

Following the conda installation, you can create the `SE1_toy_problem` environment using the following command at the terminal prompt:
```bash
conda env create -f environment.yaml
```

The [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/) package is included in this environment.
Therefore, after creating the environment, you can activate it using
```bash
source activate SE1_toy_problem
 ```
  or 
 ```bash
conda activate SE1_toy_problem
 ```
depending on whether shell integration has been configured.


Finally, start JupyterLab using:
 ```bash
jupyter lab
```