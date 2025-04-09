# protein-evaluation-notebook

Credit: this evaluation script is from https://github.com/Eurekashen/protein-evaluation-notebook, thanks to @Eurekashen for his help in building this pipeline.

Note: Setting up env on UIUC jupyterhub may fail to install ``aria2c`` with ``apt`` (permission required). Run ``EvalRunner_jupyter.py`` or ``eval_jupyter.ipynb`` on your server (GPU mem > 8G) or colab. Sample code will output ``tm_score``, ``bb_rmsd``, ``sample_path``, ``header``, ``sequence``, ``ptm``, ``plddt``, ``pae``.

If you are using your own server, you can clone directly from https://github.com/Eurekashen/protein-evaluation-notebook and follow instructions in ``eval_jupyter.ipynb``. Additional dependencies before you start:

```
pip install -U jax
apt install aria2c
```

If you are using colab, a runnable colab notebook will be shared soon.
