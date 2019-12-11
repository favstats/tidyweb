Readme
================

# Tidyweb

This package is meant to ease web scraping with Selenium by “tidying”
the html structure. To do so, it iterates recursively on web elements
until a given depth and returns a tibble, with the children elements
nested in list-columns. That way, tidy principles can be used to
identify specific elements and eventually interact with them.
