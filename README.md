# Amazon Prime Video - Data Analysis with Python

Amazon Prime Video is one of the largest providers of online streaming services. It collects a huge amount of data because it has a very large subscriber base. In this article, I’m going to introduce you to a data Analysis project on Amazon Prime Video  data analysis with Python.

## Amazon Prime Video Data Analysis

We can analyze a lot of data and models from Amazon Prime Video because this platform has consistently focused on changing business needs by shifting its business model from on-demand DVD movie rental and now focusing a lot about the production of their original shows.

In this article, I’ll take a look at some very important models of Amazon Prime Video data to understand what’s best for their business. Some of the most important tasks that we can analyze from Amazon Prime Video data are:

1. understand what content is available
2. understand the similarities between the content
3. understand the network between actors and directors
4. what exactly Amazon Prime Video is focusing on
5. sentiment analysis of content available on Amazon Prime Video.


### How to run the code

This is an executable [*Jupyter notebook*](https://jupyter.org) hosted on [Jovian.ml](https://www.jovian.ml), a platform for sharing data science projects. You can run and experiment with the code in a couple of ways: *using free online resources* (recommended) or *on your own computer*.

#### Option 1: Running using free online resources (1-click, recommended)

The easiest way to start executing this notebook is to click the "Run" button at the top of this page, and select "Run on Binder". This will run the notebook on [mybinder.org](https://mybinder.org), a free online service for running Jupyter notebooks. You can also select "Run on Colab" or "Run on Kaggle".


#### Option 2: Running on your computer locally

1. Install Conda by [following these instructions](https://conda.io/projects/conda/en/latest/user-guide/install/index.html). Add Conda binaries to your system `PATH`, so you can use the `conda` command on your terminal.

2. Create a Conda environment and install the required libraries by running these commands on the terminal:

```
conda create -n zerotopandas -y python=3.8 
conda activate zerotopandas
pip install jovian jupyter numpy pandas matplotlib seaborn opendatasets --upgrade
```

3. Press the "Clone" button above to copy the command for downloading the notebook, and run it on the terminal. This will create a new directory and download the notebook. The command will look something like this:

```
jovian clone notebook-owner/notebook-id
```



4. Enter the newly created directory using `cd directory-name` and start the Jupyter notebook.

```
jupyter notebook
```

You can now access Jupyter's web interface by clicking the link that shows up on the terminal or by visiting http://localhost:8888 on your browser. Click on the notebook file (it has a `.ipynb` extension) to open it.

# Downloading the Dataset

About this Dataset: Amazon Prime is another one of the most popular media and video streaming platforms. They have close to 10000 movies or tv shows available on their platform, as of mid-2021, they have over 200M Subscribers globally. This tabular dataset consists of listings of all the movies and tv shows available on Amazon Prime, along with details such as - cast, directors, ratings, release year, duration, etc.

The dataset I use for the Amazon Prime data analytics task consists of TV shows and movies streamed on Amazon Prime as of 2021. The dataset is provided by Kaggle.
