# Web-Crawl

Python program that searches whether given string exists in html version of a website
and all hyperlinks inside it Amount of sub-sites visited are limited by depth intiger

My code also prevents you from visiting the same site twice and searches through every
website in different threads

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install bs4 module.

```bash
pip install bs4
```

## Usage

In order to use the program, you have to change the given url to your chosen one and
specify which function you want to perform on the html-parsed website code, as below:

```python
crawl("YOUR URL", DEPTH, YOUR FUNCTION)
```
