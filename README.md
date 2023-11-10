# Requirements:
To run this DSL, ensure you have the following installed:
1) Python3
2) Pip
3) Beautiful Soup 4
4) Scrapy

# Steps to run
To use the language in CLI mode, execute:

`python3 main.py`

To run a specific script:

`python3 main.py <location_of_script>`

# Syntax:
Below are the commands and their syntax:

## 1) let command
Creates a new variable.
Syntax: `let <var_name> equals <url_value>`

## 2) list command
Creates a new list of URL values.
Syntax: `list <list_name> equals <url_value1> <url_value2> ...`

## 3) freevar command
Deletes variables.
Syntax: `freevar <var_name1> <var_name2> ...`

## 4) freelist command
Deletes lists.
Syntax: `freelist <list_name1> <list_name2> ...`

## 5) mem command
Displays memory status.
Syntax: `mem <modeOfOption?> <verbose?>`

## 6) get command
Obtains resources from a URL.
Syntax: `get <resource_type> <resource_identifier> from <url_identifier> write? <location> store? location`

## 7) view command
Obtains details of a webpage or URL.
Syntax: `view <resource_type> <resource_identifier> from <url_identifier> write? <location>`

## 8) help command
Displays help information.
Syntax: `help`
