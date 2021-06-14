# DBL Data Challenge Project
TU/e Bachelor Data Science 2021 • DBL Data Challenge Q4 • Group 17

## Features

- Loading in a big tweet dataset in json format
- Cleaning & filtering of tweets
- Relational database querying for optimal efficiency
- Categorizing and analyzing tweets
- Creating visualizations

This GitHub repo is designed to be able to efficiently load our project consisting of Jupyter Notebooks and a large tweet dataset. This guide will guide you through the installation process.

## Software

The following software was used during the project and are required to be able to run this project:

- [Python 3](https://www.python.org/download/releases/3.0/) - An interpreted, object-oriented, high-level programming language with dynamic semantics
- [Jupyter Notebook](https://jupyter.org/install) - An open source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text
- [PostgreSQL](https://www.postgresql.org/download/) - An open source relational database management system

## Setting up the database

Please follow [this](https://www.youtube.com/watch?v=O0WNoYO-29U) tutorial by the Youtuber Jinu Jawad M, in which he explains how to setup a database with PostgreSQL and how to setup a user together with a password.

When setting this up please ensure that you are matching the different parameters (database name, username, password) with the ones displayed below.
```py
database_host = "localhost"
database_name = "dbl_data_challenge"
database_user = "admin"
database_pass = "vZtbqKNXGz27cQCH"
```

## Libraries

The Jupyter Notebooks use a number of publicly available Python libraries to work properly:

- [Psycopg2](https://pypi.org/project/psycopg2/) - PostgreSQL Database Adapter
- [Pandas](https://pypi.org/project/pandas/) - Powerful data structures for data analysis, time series, and statistics
- [Numpy](https://pypi.org/project/numpy/) - The fundamental package for array computing with Python
- [Sklearn](https://pypi.org/project/scikit-learn/) - A set of python modules for machine learning and data mining
- [Searborn](https://pypi.org/project/seaborn/) - Statistical data visualization
- [Nltk](https://pypi.org/project/nltk/) - Natural Language Toolkit
- [Emoji](https://pypi.org/project/emoji/) - Emoji for Python
- [Matplotlib](https://pypi.org/project/matplotlib/) - Plotting package
- [Json](https://docs.python.org/3/library/json.html) - Encoding basic Python object hierarchies
- [Os](https://docs.python.org/3/library/os.html) - A portable way of using operating system dependent functionality
- [Time](https://docs.python.org/3/library/time.html) - Provides various time-related functions
- [Re](https://docs.python.org/3/library/re.html) - Provides regular expression matching operations similar to those found in Perl
- [Strings](https://pypi.org/project/strings/) - Strings for humans

More information relating to these libraries will be given in the [Installation](#installation) section down below.

## Dataset

To download the exact Twitter tweet dataset that was used to conduct research visit [this link](https://surfdrive.surf.nl/files/index.php/s/Dz082kih8yMGB5P). This dataset consists of 30GB of files containing 500+ files with tweets in json format. Every single line in a file contains the data for a separate tweet. Please place these json files in a folder called data with the following structure:
```
dbl_data_challenge /
    1. Extract Tweets.ipynb
    2. Extract Conversations.ipynb
    ...
    data /
        airlinetweets1.json
        airlinetweets2.json
        ...
```
If you want to make use of another dataset, please make sure that the files are in json format, every single line of the files contains a new tweet and finally make sure this data was obtained using Twitter API V1. Otherwise the data will very likely be incompatible with the current code.

## Installation

This project requires the software mentioned in [Software](#software) and [Setting up the database](#setting-up-the-database) to be installed. The libraries mentioned in [Libraries](#libraries) are also mandatory, however these will be automatically installed and imported within the Jupyter Notebooks. The dataset that was used can be found and downloaded in the [Dataset](#dataset) section, also make sure to follow the instructions to ensure that the code to runs properly.

Please run the Jupyter Notebooks in the following order:
```py
1. Extract Tweets.ipynb
2. Extract Conversations.ipynb
3. Extract Replies.ipynb
4. Extract Root Groups.ipynb
5. Extract ABA Groups.ipynb
```

## License

TU/e 2021
