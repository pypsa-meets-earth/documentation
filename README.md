# pypsa-africa-hackathon
General instructor notes:
- Total length 3 hours.
- All content should be reusable! (jupyter scripts with screenshots,explaination and code snippets?)
- Story-telling better than only content-telling.
- Make interactive. Prepare multiple choice and questions.
- Easy to use and understand. Store mini-example datakits here.

### Github [ACTION] (30-40min) -- Max/Davide
Aim: Show the workflow on how to contribute
- Issue list and discussion board
- Github logic ![image](https://user-images.githubusercontent.com/61968949/142782206-22c7d80d-6884-4c84-91d8-93933cd9ba05.png)
- The 7 steps: Fork, load locally, branch, add changes, push upstream, PR to PyPSA-Africa https://www.tomasbeuzen.com/post/git-fork-branch-pull/
- Everyone should contribute a <first_name>.txt. Learning by doing. (New GitHub authentification might cause problems)

### Architecture of PyPSA-Africa (10-15min) -- Max/Davide
Aim: Explain each component and it's function
- environment.yml
- config.yml
- Snakefile
- .py scripts
- .ipynb scripts
- .gitignore
- most data needs to be stored outside

### Installation [ACTION] (20-30min) -- Max/Davide
- Together (clone already done above, continiue with environment etc. (homework?))

# ------------------15 min BREAK-------------------------

### Executiion, Snakemake and debugging [ACTION - parallel coding with prepared scripts] (30min) -- Max/Davide
Aim: Explain the architecure and show execution example
- Snakefile deep dive into one function
- create a dag
- execution of snakemake workflow example (dry run, successful run, failed run, introduction to wildcards)
- execution of single script (one that works, one that fails)
- how to debug? Interactive debug. Role of jupyter notebooks

### Sharing real live code experience. Efficient vs poor code. (15min) --MATIN?
- different type of loops and timeit
- create an efficient loop
- 
### Forming teams & co-hacking - role of discord (15min) --MATIN?
- Co-hacking experience story
- Using discord, voice channel etc.

### Final note on challenges that we need to tackle (10min) -- Max/Davide
Aim: Inspire people to take on some of them
- Solver, solver interface, problem builder, dataworkflow and AI data creation.
- Final remark

# ---------------END-----------------

### List of selected self-learning material
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
