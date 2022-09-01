# Property_Technology
A jupyter notebook analysis of San Francisco rental properties with interactive visualizations. First we take curated census data and read it into a pandas dataframe. Next, we prepare it 

Currently under construction...


---

## Technologies

Language: Python 3.9.12

Libraries used:

[Pandas](https://pandas.pydata.org/pandas-docs/stable/index.html) - For the creation and visualization of Data Frames

[Jupyter Labs](https://jupyter.org/) - An ipython kernel for interactive computing in python

[PyViz hvPlot](https://hvplot.holoviz.org/index.html) - A high level python library for data visualization and plotting

[PyViz GeoViews](https://geoviews.org/) - A python library used for viewing geographical, meteorological, and oceanographic datasets


---

## Installation Guide

If you are using an anaconda or a conda environment chances are pandas, and jupyter labs are already installed in your virtual environment. In addition, installing HoloPlot GeoViews will be an added necessity 

For a full install activate a conda development environment and run in GitBash:
```python
    conda install pandas
    conda install jupyterlab
    conda install -c pyviz hvplot geoviews
```

Check the to make sure everything has been installed properly
```python
    conda list hvplot
    conda list geoviews
```


---

## Usage

To run this jupyter lab notebook you will need to use GitBash and navigate to where you have exported the files associated with this project.

Next you will need to perform the following

![Activate](Images/activate.png)

This will open a jupyter lab notebook in your default browser with the correct working directory.

Next open **'san_francisco_housing.ipynb'** and click the double arrow to run the notebook. Alternatively you can run each cell individually.

Make sure to follow the pseudocode to see the coding logic and fully understand what is being analyzed and displayed.

There are a couple of interactive graphs for rent prices vs sales prices in a line plot and a geoview. Make sure to follow the analysis and
check out the different neighborhoods.


---

## Highlights:

Here are a few snippets of what you can find in this project

### Interactive Visualization

[>insert images here]

### GeoViews Visualization

[>insert images here]


---

## Contributors

Created by Silvano Ross while in the UW FinTech Bootcamp
> Contact Info:
> email: silvanoross3@gmail.com |
> [GitHub](https://github.com/silvanoross) |
> [LinkedIn](https://www.linkedin.com/in/silvano-ross-b6a15a93/)

---

## License

[MIT](LICENSE)
