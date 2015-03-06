# Intro to Python at NICAR
### A one hour session

These are materials for getting started with Python. Learning things is hard. Please reach out before throwing in the towel.

## What do to if you get stuck?

* Google for the answer (DO THIS FIRST)
* Ask a friend or user group

Read [How to Ask Questions](http://www.propublica.org/nerds/item/how-to-ask-programming-questions), before posting your questions online. It covers ways to help frame your questions so others can best help you.

## Launching Your Python interpretor

On a PC
* Search for "Python".
* Select the top choice.

On a Mac
* Launch Terminal
* Type `python`


Your Python interpretor prompt, looks like this:

`>>>`

Your terminal prompt, looks like this:

* PC - `>`
* Mac/Linux - `$`


## Basic Data Structures

| Tables        | Are           |
| ------------- |---------------|
| string        | 'Joker'       |
| integer       |2              |
| floats        | 2.0           |
| variable      | animal_names  |
| list          | ['Joker', 'Simon', 'Ellie', 'Lishka', 'Fido'] |
| dictionary    | {'cats': 2, 'dogs': 5, 'horses': 1, 'snakes': 0} |

## Helpful tools

* Type - What data type?
  * `type('Joker')`
  * `type(5)`
  * `type(['Joker', 'Simon', 'Ellie', 'Lishka', 'Fido'])`
* Dir - What are some of things I can do with this thing?
  * `dir('Joker')`
  * `dir(['Joker', 'Simon', 'Ellie', 'Lishka', 'Fido'])`
* Help - Tell me all about this thing
```python
import csv
help(csv)
```

## Installing libraries

Google and see what other people use or what makes sense to you - use that.

If you try to install the [requests library](http://docs.python-requests.org/en/latest/):

`pip install requests`

If you get a permissions error, try...

`sudo pip install requests`

If you want to see all the libraries that are available, visit [Pypi](Pypi.python.org)

## Running scripts

From inside the csv folder:
* `python import_csv_data.py`

From inside the excel folder:
* `python parse_excel.py`

Lastly, here is a great repo of [web scrapers](https://github.com/ireapps/first-web-scraper).

Try running this [Boone County Arrest scrapers](https://github.com/ireapps/first-web-scraper/tree/master/scrapers/crime).



