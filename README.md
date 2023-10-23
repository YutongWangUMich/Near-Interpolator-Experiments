# Near Interpolators Experiments

For each figure panel in the paper, there are three associated directories inside the directory `figure_and_experiment_code`:
- NAME-plot/
- NAME-run1/
- NAME-run2/

For instance, NAME can be one of `figure1-left`, `figure1-right`, `figure4-bottom-left`, and so on.

To recreate the figures, for say `figure1-left` do the following:

```
cd figure1-left-run1
source run_experiment.sh
cd ..
cd figure1-left-run2
source run_experiment.sh
cd ..
cd figure1-left-plot
jupyter run plot_figure.ipynb
```

The figure will be in `figure1-left-plot/outputs/`
