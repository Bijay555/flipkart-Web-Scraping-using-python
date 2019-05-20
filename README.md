# flipkart-Web-Scraping-using-python
Basically it contains code and procedures of how we can scrap any web and get tons of information. It is easy to understand.
You should include two python linraries while working with it

1. BEAUTIFUL SOUP

Beautiful Soup is a Python library for pulling data out of HTML and XML files. It works with your favorite parser to provide idiomatic ways of navigating, searching, and modifying the parse tree. It commonly saves programmers hours or days of work.
>>> from bs4 import BeautifulSoup

2. REQUEST
Requests is a Python HTTP library, released under the Apache2 License. The goal of the project is to make HTTP requests simpler and more human-friendly. The current version is 2.21.0
Example code for installing request package

>>> import requests
    >>> r = requests.get('https://api.github.com/user', auth=('user', 'pass'))
    >>> r.status_code
    200
    >>> r.headers['content-type']
    'application/json; charset=utf8'
    >>> r.encoding
    'utf-8'
    >>> r.text # doctest: +ELLIPSIS
    u'{"type":"User"...'
    >>> r.json() # doctest: +ELLIPSIS
    {u'private_gists': 419, u'total_private_repos': 77, ...}
