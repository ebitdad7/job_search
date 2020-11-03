# job_search
### Scraping jobs from Indeed

## This repository
The module job_search.py enables you to web scrape job postings from Indeed.com.

This will require the packages Beautiful Soup and Selenium web driver is also required. These can be installed as follows:

```bash
$ pip install beautifulsoup4
$ pip install selenium
```

To use this module, import the job_search.py file and call the funciton "find_jobs_from()", which takes in several arguments. For an explanation and demonstration of the required arguments, see job_search_notebook.ipynb.

## Terms and conditions
I do not condone scraping data from Indeed in any way. Anyone who wishes to do so should first read their statements on scraping software [here](https://www.indeed.com/legal)


## Using the selenium web driver
At present, the default browser is set as Google Chrome. This can be modified within job_search.py.

## Add-ons
I also recommend installing PandasGUI if you would like to later incorporate word clouds in an easily and plotly format. You can install PandasGUI as follows:

``` bash
$ pip install pandasgui
```

You can learn more about PandasGUI [here](https://github.com/adamerose/pandasgui)
