# Week 4: More Interactive Data Viz, Getting Started with APIs

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MUSA-620-Spring-2019/week-4/master?filepath=lecture-4.ipynb)

## Updating your local environment

First, download the `environment.yml` file in this repository to your computer.

**Important**: if you are on a Windows machine, make sure that `.txt` wasn't appended to the file name when you downloaded it. If so, you will need to rename it so the file ends in `.yml`.

Then you can run, from either the Anaconda Prompt (Windows) or Terminal app (MacOS):

```
conda env update --file environment.yml --name musa
```

where `musa` should be the name of the environment you have been using.

Then you can activate the environment and start a notebook

```
conda activate musa
```

## Topics

- hvplot, Holoviews, GeoViews
- APIs
- SQL

## Readings

- [hvplot User Guide](https://hvplot.pyviz.org/user_guide/index.html)
- [Socrata API](https://dev.socrata.com/consumers/getting-started.html)

## References

- [pyViz tutorial](http://pyviz.org/tutorial/index.html): introduction to the pyViz ecosystem
- [HoloViews user guide](http://holoviews.org/user_guide/index.html) and [gallery](http://holoviews.org/gallery/index.html)
- [GeoViews user guide](http://geoviews.org/user_guide/index.html) and [gallery](http://geoviews.org/gallery/index.html)
- [SQL documentation for CARTO](https://www.postgresql.org/docs/9.1/sql.html)
- [GeoServices](http://geoservices.github.io/)
- [String formatting for DateTime objects](http://strftime.org/)
