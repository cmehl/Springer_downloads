# Springer_downloads
In the difficult context of COVID-19, Springer has decided to facilitate access to educational resources and has therefore granted a free access to a vast amount of books in several disciplines (more details here: https://www.springernature.com/fr/librarians/news-events/all-news-articles/industry-news-initiatives/free-access-to-textbooks-for-institutions-affected-by-coronaviru/17855960). These books will be available until mid-July 2020 according to Springer.

This list of books comes however as an Excel list, where the URLs are indicated individually for each entry. The present code automatically downloads the books' PDFs using Python, and in particular the _selenium_ and _openpyxl_ libraries. Required libraries are detailed in _requirements.txt_. The required libraries may be installed using pip for instance:

```
pip install -r requirements.txt
```

Note that the code is written for use with Chrome browser.

The Excel file containing the list of books is included in this git. Feel free to delete entries in the Excel, the script will only download the items present in the Excel file.
