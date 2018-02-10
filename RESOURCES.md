#  Resources For New Data Scientists


## Developer Toolkit

[Getting Started With Anaconda](https://conda.io/docs/user-guide/getting-started.html)

[Jupyter Notebook Quickstart](https://jupyter.readthedocs.io/en/latest/content-quickstart.html)


## Python Libraries

[NumPy Quickstart](https://docs.scipy.org/doc/numpy/user/quickstart.html)

[10 Minutes to Pandas](https://pandas.pydata.org/pandas-docs/stable/10min.html)

[Matplotlib tutorials](https://matplotlib.org/tutorials/index.html)

[WordCloud.generate_from_frequencies](https://amueller.github.io/word_cloud/generated/wordcloud.WordCloud.html#wordcloud.WordCloud.generate_from_frequencies)

[nltk](http://www.nltk.org) + [nltk book](http://www.nltk.org/book)

[NetworkX tutorial](https://networkx.github.io/documentation/networkx-1.10/tutorial/index.html)


## Books

Data Science From Scratch, Joel Grus, O'Reilly, 2015.

Python For Data Analysis, 2nd Edition, Wes McKinney, O'Reilly, 2017.

The Manga Guide To Linear Algebra, by Shin Takahashi, Iroha Inoue 
and Trend-Pro Co., Ltd., No Starch Press, 2012.

Short, free excellent book from GitHub: [Development Workflows for Data Scientists](https://resources.github.com/downloads/development-workflows-data-scientists.pdf), 
Ciara Byrne, O'Reilly, 2017.

### Community 

[Reddit.com/r/datascience](https://www.reddit.com/r/datascience/)

## Articles 

[Why is Python growing so quickly?](https://stackoverflow.blog/2017/09/14/python-growing-quickly/)

[Tag clouds](https://en.wikipedia.org/wiki/Tag_cloud)

[Split-Apply-Combine](https://www.jstatsoft.org/htaccess.php?volume=40&type=i&issue=01&paper=true), Hadley Wickham,
 _Journal of Statistical Software_, April 2011.

[We Need Both Exploratory and Confirmatory](http://www.aliquote.org/cours/2013_AS/docs/Tukey1980.pdf), John Tukey, _The American Statistician_, 1980.

## Handy `conda` commands

Create a virtual environment: 

`conda create --name PYTN python=3`

Activate a virtual environment:

`source activate PYTN`

Deactivate a virtual environment:

`source deactivate PYTN`

Remove an virtual environment:

`conda env remove -n PYTN`

Create a spec list file from the current environment:

`conda list --explicit > spec-list.txt`

Create a new environment from this spec-list:

`conda create --name PYTN --file spec-list.txt`
