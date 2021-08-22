# Module_6_Challenge

# Proptech One-click Rental Service

---

## Introduction:

The premise of this project is the scenario that I am an analyst at a proptech company that wants to offer an instant, one-click service for people to buy properties and then rent them. The company wants to have a trial of this offering in the San Francisco real-estate market. If the service proves popular, they can then expand to other markets.

My job is to use data visualization, including aggregation, interactive visualizations, and geospatial analysis, to find properties in the San Francisco market that are viable investment opportunities.

I have created a Jupyter notebook with my analysis of the housing rental market data for San Francisco. The analysis includes styled and formatted interactive visualizations.

---

## Technologies

This project leverages python 3.7 with the following modules:

* [os](https://docs.python.org/3/library/os.html) - For providing a portable way of using operating system dependent functionality.

* [plotly](https://plotly.com/python/scattermapbox/) - For making scatter plots on Mapbox maps.

* [hvplot](https://hvplot.holoviz.org) - For plotting in various formats working with a wide array of datatypes in the PyData ecosystem.

* [pandas](https://github.com/pandas-dev/pandas) - For reading data into a DataFrame and analyzing data via statistics and plots.

* [dotenv](https://pypi.org/project/python-dotenv/) - For reading key-value pairs from a .env file and setting them as environment variables.

* [csv](https://docs.python.org/3/library/csv.html) - For reading and writing tabular data in CSV (Comma Seperated Values) format.

* [pathlib](https://docs.python.org/3/library/pathlib.html) - For representing the file system path to a csv.

* [matplotlib](https://matplotlib.org/stable/users/index.html) - For embedding plots in the application.

---

## Installation Guide

Before running the application first install the following dependencies:

```python
  pip install pandas
  pip install hvplot
  pip install python-dotenv
  pip install mkdocs
```

To install PyViz and its dependencies in your Conda dev environment, complete the following steps:

```python
  conda install -c plotly plotly=4.13.
  conda install -c pyviz hvplot
  conda install -c conda-forge nodejs=12
```

For your PyViz plots to render in JupyterLab, you also need to install a specific version of JupyterLab, as well as the JupyterLab extensions. To install the required JupyterLab version and the extensions for PyViz and Plotly Express, run the following commands in the terminal:

```python
  conda install -c conda-forge jupyterlab=2
  jupyter labextension install jupyterlab-plotly@4.13.0 --no-build
  jupyter labextension install @jupyter-widgets/jupyterlab-manager plotlywidget@4.13.0 --no-build
  jupyter labextension install @pyviz/jupyterlab_pyviz --no-build
```

Now that you’ve installed the extensions in your Conda dev environment, you need to apply, or build, them to the JupyterLab software. To do so, run the following code:

```python
  jupyter lab build
```

To use the Mapbox API, you need to register for a public Mapbox API access token. You can find detailed instructions on the Plotly Express documentation page:

(https://plotly.com/python/scattermapbox/#mapbox-access-token-and-base-map-configuration)

---

## Usage

To use the Proptech One-click Rental Service application:

Clone the Module_6_Challenge repository from GitHub:

'git clone https://github.com/jpweldon/Module_6_Challenge.git'

Create an environment (.env) file with your MAPBOX_API_ACCESS_TOKEN in the same folder as san_francisco_housing.ipynb.

Run the san_francisco_housing.ipynb program.

Examine the analysis of the housing rental market data for San Francisco including the styled and formatted interactive visualizations.

---

## Contributors

John P Weldon

Email: johnpweldon01@gmail.com

[LinkedIn:] (www.linkedin.com/in/john-weldon-333b0695)

---

## License

MIT

---