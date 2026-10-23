# College Football Analysis

Python dictionaries, loops and conditionals used to explore Division I FBS college football schools: team nicknames, enrollments and conferences.

**Notebook:** [notebooks/M3_College_Football_Analysis.ipynb](notebooks/M3_College_Football_Analysis.ipynb)

This is a milestone project from the Global Career Accelerator program. The scenario and data come from the program. It is not work done for any university or sports organization.

## Context

The scenario puts the analysis inside a sports analytics team looking at Division I Football Bowl Subdivision (FBS) schools. The data is stored as Python dictionaries that map each school to its team nickname, enrollment, city, state and conference.

## Tools and skills

- Python, Jupyter
- Dictionaries and lists, including a dictionary with list values
- `for` loops with `if` / `elif` conditions
- Counting and accumulator variables
- Importing a local data module with `sys.path`

## Approach

1. Counted the FBS teams in the data.
2. Looped over the nickname dictionary to find every school whose team is called the Tigers.
3. Counted schools with fewer than 10,000 students and with more than 50,000.
4. Calculated the number of schools, total enrollment and average enrollment in the Big 12 conference, once with a list and summary functions and once with accumulator variables.
5. Listed questions for the athletic department to look into next.

## Key findings

- **131 FBS teams** are in the data.
- **Five schools are the Tigers:** Auburn, Clemson, LSU, Memphis and Missouri.
- **Large schools outnumber small ones:** 14 schools have more than 50,000 students and 7 have fewer than 10,000.
- **The Big 12 has 10 schools in this data**, with 280,990 students in total and an average of 28,099.
- **Questions to explore next:** how a team's past performance relates to enrollment, the demographics of students who join the team, and whether social media engagement affects enrollment.

The optional LevelUp extension at the end of the notebook (repeating the Big 12 analysis with a nested dictionary) was not completed.

## How to run

The data module is not included (see [files/README.md](files/README.md)). The notebook keeps its saved outputs, so it can be read on GitHub without running anything.

To run it yourself:

1. Place `ncaa_fbs.py` in `files/`.
2. Open `notebooks/M3_College_Football_Analysis.ipynb` in Jupyter from the `notebooks/` folder and run the cells from the top. The notebook finds the module through `sys.path.append('../files')`.

Requirements: Python 3 (the notebook was saved with Python 3.10.6) and Jupyter. No other packages are used.

## Repo structure

```
college-football-analysis-python/
├── notebooks/
│   └── M3_College_Football_Analysis.ipynb   analysis notebook with saved outputs
└── files/
    └── README.md                            which data module goes here
```
