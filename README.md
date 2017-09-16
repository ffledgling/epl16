# About
Notebook to keep track of a little prediction league amongst friends.

## Developing

Setup a conda environment using the `conda_env.yaml` file. Start up a jupyter notebook, edit, submit a PR.

To run the notebook via the CLI, i.e without firing it up in the browser, you can use:

```
jupyter nbconvert --execute --ExecutePreprocessor.kernel_name=python3 --to notebook --inplace epl.ipynb
```
