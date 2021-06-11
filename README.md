# DBL Data Challenge Project
TU/e Bachelor Data Science, DBL Data Challenge Q4, Group 17

## Features

- Import Twitter data in JSON format
- Clean & filter these tweets
- Export tweets to a database for releational querying
- Create categories of tweets
- Analyze tweet categories
- Create visualizations

This GitHub repo is designed to be able to efficiently load in our jupyter notebooks and convert the data in a linear way. By following this guide we will guide you through this process.

## Software

The following software was used during the project, these are all publicly available for free:

- [Python 3](https://www.python.org/download/releases/3.0/) - An interpreted, object-oriented, high-level programming language with dynamic semantics
- [Jupyter Notebook](https://jupyter.org/install) - An open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text
- [PostgreSQL](https://www.postgresql.org/download/) - An open source relational database management system

## Setting up the database

Please follow [this](https://www.youtube.com/watch?v=O0WNoYO-29U) tutorial by the Youtuber Jinu Jawad M, in which he explains how to setup a database with PostgreSQL and how to setup a user together with a password.

When setting this up please ensure that you are matching the different parameters (name, user, pass) with the ones displayed below:
```py
database_host = "localhost"
database_name = "dbl_data_challenge"
database_user = "admin"
database_pass = "vZtbqKNXGz27cQCH"
```

## Libraries

The Jupyter Notebooks that are created use a number of publicly available Python libraries to work properly:

- [Psycopg2](https://pypi.org/project/psycopg2/) - PostgreSQL Database Adapter
- [Pandas](https://pypi.org/project/pandas/) - Powerful data structures for data analysis, time series, and statistics
- [Numpy](https://pypi.org/project/numpy/) - The fundamental package for array computing with Python
- [Sklearn](https://pypi.org/project/scikit-learn/) - A set of python modules for machine learning and data mining
- [Searborn](https://pypi.org/project/seaborn/) - Statistical data visualization
- [Nltk](https://pypi.org/project/nltk/) - Natural Language Toolkit
- [Emoji](https://pypi.org/project/emoji/) - Emoji for Python
- [Matplotlib](https://pypi.org/project/matplotlib/) - Plotting package
- [JSON](https://docs.python.org/3/library/json.html) - Encoding basic Python object hierarchies
- [Os](https://docs.python.org/3/library/os.html) - A portable way of using operating system dependent functionality
- [Time](https://docs.python.org/3/library/time.html) - Provides various time-related functions
- [Re](https://docs.python.org/3/library/re.html) - Provides regular expression matching operations similar to those found in Perl
- [Strings](https://pypi.org/project/strings/) - Strings for humans

## Dataset

To download the exact twitter tweet dataset that was used to conduct research visit [this link](https://surfdrive.surf.nl/files/index.php/s/Dz082kih8yMGB5P). This dataset consists of 500+ files containing tweets in json format. Every single line in a file contains the data for a separate tweet.

## Installation

This project requires the software mentioned in [Software](#software) to be installed. The libraries mentioned in [Libraries](#libraries) are also mandatory, however these will be automatically installed and imported within the Jupyter Notebooks. The dataset that was used can be found and downloaded in [Dataset](#dataset), which will be needed for the code to run properly.

Please run the Jupyter Notebooks in the following order:
```py
1. Extract Tweets.ipynb
```

## License

TU/e
