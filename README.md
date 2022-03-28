<<<<<<< HEAD
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
=======
# PyPSA Africa Hackathon 
### - Getting ready to change the world!
Expected experience level: Beginner  
Duration hackathon: 3 hours  
Duration extra DIY exercises: 5 hours

Content:
------------
Slides and jupyter notebook examples are provided in this repository. While there is a lot of theory and text, we always recommend to code & check out stuff where possible. Small examples also help you to "do rather than only observe".

- Vision and Mission - Hackathon-slides.pdf
- Full GitHub workflow exercise for a PyPSA-Africa contribution
- The architecture of PyPSA-Africa on GitHub
- Development tools, requirements and installation of pypsa-africa
- 3 ways of Snakemake executions and introduction to debugging
- Code-Dev story on efficient vs. poor code and the role of discord
- Guideline on "How to add to need regions to PyPSA-Africa"
- Wrap-up - Hackathon-slides.pdf

### List of selected self-learning material
Aim: We provide a couple of links to efficient self-learning material
- [Fundamentals of energy economics and energy systems](https://nworbmot.org/teaching.html), great open lecture materials from Tom Brown
- [Unix-Shell](https://swcarpentry.github.io/shell-novice/), the Unix shell is fundamental to a wide range of advanced computing tasks, including high-performance computing
- [Python Dojo](https://www.youtube.com/playlist?list=PLBZBJbE_rGRWeh5mIBhD-hhDwSEDxogDg), a series of Python videos for absolute beginners
- [PyPSA examples](https://github.com/PyPSA/PyPSA/tree/master/examples), that help understanding what PyPSA does. Click on [Binder at the PyPSA page](https://github.com/PyPSA/PyPSA) opens the examples.
- [Atlite examples](https://github.com/PyPSA/atlite/tree/master/examples), that help understanding what Atlite does. Requires to install Atlite and open Jupyter notebooks
- [Snakemake tutorial](https://snakemake.readthedocs.io/en/stable/tutorial/tutorial.html), learn more about the powers of Snakemake

Useful packages to dive deeper into:
- [pandas](https://pandas.pydata.org/)
- [geopandas](https://geopandas.org/en/stable/)
- [shapely](https://shapely.readthedocs.io/en/stable/manual.html#introduction)
- [numpy](https://nbviewer.org/github/jrjohansson/scientific-python-lectures/blob/master/Lecture-2-Numpy.ipynb)
- [xarray](http://xarray.pydata.org/en/stable/tutorials-and-videos.html)
- [dask](https://github.com/dask/dask-tutorial)

### List of hero's with a successfull Pull Request (GitHub exercise): 
- Lukas Franken from Germany
- Davide Fioriti from Italy
- Matin Mahmood from United Kingdom
- Max Parzen from Germany
- Thomas Lesieur from France
- Jan Ohlenbusch from Germany
- Taco Niet from Canada
- Pierre McWhannel from Canada
- Mariana Rodríguez-Arce from Costa Rica
- YOU?
>>>>>>> clean-history
