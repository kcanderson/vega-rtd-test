# Demonstration of Vega graphics using Denver RTD data

The [Vega project](https://vega.github.io/) created a fantastic (and underutilized) grammar of visualization, along with Javascript tools to embed charts in web pages. The grammar is analogous to ggplot for R, but it is more universal in scope and accessibility. 

The purpose of this project is to demonstrate how Vega may be used to visualize a dataset. Here I'm using a dataset from the Regional Transportation District of Denver. I take integrate the bus/rail routes with trip timings to estimate headway times.

### Environment

My Jupyter environment may be created using the `requirements.txt` file.

```
python -m venv env
source env/bin/activate
pip install -r requirements.txt
```

### Viewing the notebook

The Jupyter notebook can be opened locally or in [Google Collab](https://colab.research.google.com/github/kcanderson/vega-lite-test/blob/main/vega_notebook.ipynb).

### Chart artifacts from notebook

[Chart 1](https://rawcdn.githack.com/kcanderson/vega-lite-test/a8e36778b3137ff005c4981ce4b509345162d7d8/charts/box_plot_headways_by_hour.html)

[Chart 2](https://rawcdn.githack.com/kcanderson/vega-rtd-test/05d0780de13dd57f00587424d143c0b65a906449/charts/box_plot_headways_by_route.html)




