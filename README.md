# pypsa-africa-hackathon
General instructor notes:
- Total length 3 hours.
- All content should be reusable! (jupyter scripts with screenshots,explaination and code snippets?)
- Story-telling better than only content-telling.
- Make interactive. Prepare multiple choice and questions.
- Easy to use and understand. Store mini-example datakits here.

### The PyPSA Earth mission: (15min) -- Max
The mission and the features we want from the code [basically three slides from past presentations]
PyPSA Africa
1. mission
2. general code principle (GIS data, into shapes, aggregated, solved with powerflow & constraints)

### Architecture of PyPSA-Africa on GitHub (10-15min) -- Davide
Aim: Explain each component and it's function
- environment.yml
- config.yml
- Snakefile (dag)
- .py scripts
- .ipynb scripts
- .gitignore
- most data needs to be stored outside

### Requirements for PyPSA-Africa (Python, "VSCode", conda, solver):(15min) -- Davide
They should install environments!
briefly introduce them and check if all have them installed
  - If you use windows, install WSL: https://docs.microsoft.com/en-us/windows/wsl/install
  - Github,git
  - VScode
  - conda
  - Solver [briefly how to test i.e. gurobi.sh]

### Installation [ACTION] (20-30min) -- Davide (Max, Lukas support)
- Together (clone already done above, continiue with environment etc. (homework?))
- brief intro to the analyis [Jupyer script, import network -> series vs integer/float]

### Github [ACTION] (30-40min) -- Lukas
Aim: Show the workflow on how to contribute
- Issue list and discussion board
- Github logic ![image](https://user-images.githubusercontent.com/61968949/142782206-22c7d80d-6884-4c84-91d8-93933cd9ba05.png)
- The 7 steps: Fork, load locally, branch, add changes, push upstream, PR to PyPSA-Africa https://www.tomasbeuzen.com/post/git-fork-branch-pull/
- Everyone should contribute a <first_name>.txt. Learning by doing. (New GitHub authentification might cause problems)

# ------------------15 min BREAK-------------------------

### Executiion, Snakemake and debugging [ACTION - parallel coding with prepared scripts] (30min) -- Max
Aim: Explain the architecure and show execution example
- Snakefile deep dive into one function
- create a dag
- execution of snakemake workflow example (dry run, successful run, failed run, introduction to wildcards)
- execution of single script (one that works, one that fails)
- how to debug? Interactive debug. Role of jupyter notebooks

### Sharing real live code experience. Efficient vs poor code. (10-15min) -- Matin?
- different type of loops and timeit
- create an efficient loop
- Global variables out of function. They read in. (davide)

### Forming teams & co-hacking - role of discord (10-15min) -- Matin?
- Co-hacking experience story
- Using discord, voice channel etc.

### Final note on challenges that we need to tackle (10min) -- Max
Aim: Inspire people to take on some of them
- Solver, solver interface, problem builder PyPAS, dataworkflow and AI data creation.
- Widen picture of use case
- Climb open source ladder
- Final remark

# ---------------END-----------------

### List of selected self-learning material (ALL can provide some material?) -- ALL
Aim: We provide a couple of links to efficient self-learning material
- unix-shell
- code courses (object oriented programming, functional, test oriented programming, etc.)
- snakemake tutorial
- pypsa examples
- atlite

Useful packages to dive deeper into:
- pandas
- geopandas
- shapely
- numpy
- xarray/dask
