# PyPSA Earth Documentation

![Size](https://img.shields.io/github/repo-size/pypsa-meets-earth/documentation)

## Getting ready to change the world

This repository contains the documentation of PyPSA-Earth including:

- hackathon material in folder `hackathon`  (mandatory for beginners): it contains a 6-step introduction starting from the basics to learn PyPSA-Earth
- sample notebooks to investigate the PyPSA-Earth repository in the folder `notebooks`
- storage of documentation images in the folder `doc`

## Installation

1. Ensure the [PyPSA-Earth package and environment](https://github.com/pypsa-meets-earth/pypsa-earth.git) is installed

2. Open your terminal at the parent location where PyPSA-Earth has been installed. Type the following in your terminal to download the package from GitHub:

   ```bash
      .../pypsa/earth/parent/folder % git clone https://github.com/pypsa-meets-earth/documentation.git
   ```

## 1. Hackathon material

Expected experience level: Beginner  
Duration hackathon: 3 hours  
Duration extra DIY exercises: 5 hours

### Content

Slides and Jupyter Notebook examples are provided in the folder `hackathon`. While there is a lot of theory and text, we always recommend to code & check out stuff where possible. Small examples also help you to "do rather than only observe".

- Full GitHub workflow exercise for a PyPSA-Earth contribution
- The architecture of PyPSA-Earth on GitHub
- Development tools, requirements and installation of PyPSA-Earth
- 3 ways of Snakemake executions and introduction to debugging
- Code-Dev story on efficient vs. poor code and the role of discord
- Guideline on "How to add new regions to PyPSA-Earth"
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

### List of heroes with a successful Pull Request (GitHub exercise)  

- Lukas Franken from Germany
- Davide Fioriti from Italy
- Matin Mahmood from United Kingdom
- Max Parzen from Germany
- Thomas Lesieur from France
- Jan Ohlenbusch from Germany
- Taco Niet from Canada
- Pierre McWhannel from Canada
- Mariana Rodríguez-Arce from Costa Rica
- Hana Elattar from Egypt
- Yerbol Akhmetov from Kazakhstan
- Kumbuso Joshua Nyoni from Zambia
- Gift Sichone from Zambia
- Chris Mambwe from Zambia
- Akshat Mittal from India
- Albert Chitandula from Zambia
- Albert Solà Vilalta from Spain
- Tommaso Ferrucci from Italy
- Daniel Castro from Mexico
- Inutu Katoti from Zambia
- Oluwafemi Abiona from Nigeria
- Emmanuel Bolarinwa from Nigeria
- Liza Kiwara from Kenya
- Mwiche Simpemba from Zambia
- Moses Kaoma from Zambia
- Divyansh Singhal from India
- Anton Achhammer from Germany
- Mira Theidel from Germany
- Huy Hoang Nguyen from Vietnam
- Derval Toukam from Germany
- Pierre Karamountzos from The Netherlands
- Albert Kreutzer from Germany
- Andrea Mastrantuono from Italy
- Khalid Jamour from Chad
- Femke Nijsse from the United Kingdom

## 2. Notebooks for data exploration

The folder `notebooks` contains useful notebooks to explore the data of PyPSA-Earth.
The notebooks are self-explanatory and the `pypsa-earth` environment is needed to successfully run the examples.
