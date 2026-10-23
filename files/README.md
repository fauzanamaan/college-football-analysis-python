# files

The notebook imports its data from a Python module in this folder. The module comes with the Global Career Accelerator program and is not published in this repo.

| File | What it holds |
|---|---|
| `ncaa_fbs.py` | Data on Division I FBS college football schools, stored as Python dictionaries: `nickname` and `enrollment` (school name to team nickname or student enrollment), `fbs_teams` (school name to a list of nickname, city, state, enrollment and conference), and `fbs_teams_dict` (the same details as a nested dictionary). |

Where to get it: TODO. The file is only available inside the program.

The notebook adds this folder to the import path with `sys.path.append('../files')`, so place `ncaa_fbs.py` here and run the notebook from the `notebooks/` folder.
