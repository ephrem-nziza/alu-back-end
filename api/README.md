# api

Python scripts that read employee TODO data from
https://jsonplaceholder.typicode.com and export it in different formats.

## Requirements

- Python 3 with the `requests` module
- Code follows PEP 8

## Files

| File | What it does | Usage |
| --- | --- | --- |
| `0-gather_data_from_an_API.py` | Prints an employee's TODO progress | `./0-gather_data_from_an_API.py 2` |
| `1-export_to_CSV.py` | Writes all of an employee's tasks to `USER_ID.csv` | `./1-export_to_CSV.py 2` |
| `2-export_to_JSON.py` | Writes all of an employee's tasks to `USER_ID.json` | `./2-export_to_JSON.py 2` |
| `3-dictionary_of_list_of_dictionaries.py` | Writes every employee's tasks to `todo_all_employees.json` | `./3-dictionary_of_list_of_dictionaries.py` |
