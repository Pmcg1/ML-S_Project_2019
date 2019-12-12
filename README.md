# Machine Learning and Statistics Project 2019
## G00190832 Peter McGowan

## Introduction

This project using Python, Jupyter, SciPy, and Keras has been carried out as an assignment of the Machine Learning and Statistics module of the Higher Diploma In Data Analytics at GMIT. The project description can be found [here](https://github.com/ianmcloughlin/project-2019-machstat/blob/master/project.pdf).

The repository contains a Jupyter Notebook that imports the Boston House Prices dataset. It includes three main sections:
* Describe: The dataset is assessed using descriptive statistics and plots;
* Infer: Inferential statistics are applied to the dataset to assess if the difference in median house prices for houses along the Charles River and those not are statistically different;
* Predict: A neural network is implemented using Keras to predict median house prices from other variables in the dataset.

The repository also includes:
* Readme file
* License file
* Gitignore folder
* Several images

## License

This project is licensed under the GNU General Public License v3.0 - see [LICENSE.md](LICENSE) for details.

## Jupyter Notebook

### Downloading the Repository

The repository is stored at [https://github.com/Pmcg1/ML-S_Project_2019](https://github.com/Pmcg1/ML-S_Project_2019).

To download it, do the following:

1. Click on the "Clone or Download" button
2. Select "Download ZIP". This will open a prompt allowing you to save the file to your computer.
3. Navigate to the download location and extract the compressed (.zip) folder to a suitable location.

### Software Required

The notebook has been written using Jupyter Lab v1.0.2. and Python v3.7.3 and should be run on a computer with these versions or higher if possible. I recommend that you download the current Python 3.x Anaconda Distribution (which contains both Python and Jupyter Lab) from the [downloads section](https://www.anaconda.com/distribution/#download-section) of the Anaconda Website.

When it has downloaded, follow the installation steps with the default options to install Anaconda on your computer.

You can check which (if any) versions of these that you have installed by typing the following at the command prompt:
* python --version
* jupyter --version

This project also requires a number of external Python libraries ([listed below](#Libraries-Used)). With the exception of Keras, these come with the Anaconda Distribution and should not need to be installed separately, however links to the website for each are included.

#### Keras Installation

Keras requires some extra steps to install. If you have installed Anaconda as above, you can follow these steps to install Keras:

1. Open Anaconda Prompt
2. Enter: > conda update conda
3. Enter: > conda update --all
4. Enter: >  conda install -c conda-forge keras tensorflow

Please note that this may take some time to install.

### Libraries Used

- [Pandas] (https://pandas.pydata.org/): Pandas, particularly its "DataFrame" indexed array object is used to manage and manipulate datasets
- [Scipy.stats] (https://docs.scipy.org/doc/scipy/reference/stats.html): The t-test function in scipy.stats is used within the "Infer" section
- ****[Statsmodels.stats] (https://www.statsmodels.org/stable/index.html): The t-test function in sc
- [Matplotlib.pyplot](https://matplotlib.org/tutorials/introductory/pyplot.html): Used for manipulation of elements of certain plots in the notebook
- [Seaborn](https://seaborn.pydata.org/): Used for creation and manipulation of all plots in the notebook
- [NumPy](https://www.numpy.org/): A small number of NumPy functions are used to help generate a correlation heatmap
- [Scikit-Learn] (https://scikit-learn.org/):
  - sklearn.datasets: Used to import the Boston House Prices dataset only
  - sklearn.model_selection: Used to split the dataset into training and testing datasets
  - sklearn preprocessing: Used to scale the input datasets to improve the performance of Keras models
  - ****sklearn.decomposition: 
- [Keras] (https://keras.io/):
  - keras
  - keras.models: Used to import Keras sequential model type
  - keras.layers: Used to import Dense layers for neural networks
  - keras.callbacks: EarlyStopping callback is imported to stop model runs early once certain conditions are met

Please note that the programmes will not run successfuly if their required libraries are not installed.

### How to Run

Once the correct software has been installed, running either of the included programmes can be carried out as follows:

1. Open a command prompt (cmd) or equivalent on your PC. The alternative "cmder" programme ([available here](https://cmder.net/)) is recommended.
2. Navigate to the drive that the folder is on.
3. Navigate to the correct folder.
4. Run jupyter lab by typing the following at the command prompt (do not close the command prompt window throughout):
> jupyter lab

5. A window or tab should open in your default web browser (Mozilla Firefox and Google Chrome are recommended). If this does not happen, read the command prompt output. It should provide a URL which you can copy and paste into your web browser to access Jupyter Lab.
6. Using the menu on the left side of the page, double click the jupyter notebook file:
> ProgDA_Assessment_1_2019.ipynb

7. The notebook should open in a new tab. You can run each cell with the keyboard shortcut SHIFT+ENTER, alternatively use the "play" button on the menu bar. Please note that certain cells must be run before others e.g. the cells importing the various Python libraries. You may find it convenient to use the "Run all Cells" option in the "Run" dropdown menu.