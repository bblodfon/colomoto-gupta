# colomoto-gupta

## Intro
 
This repo has the necessary files to reproduce the analysis on the boolean model presented in [Gupta et al. (2018)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6053189/), titled '*Modeling the role of microRNA-449a in the regulation of the G2/M cell cycle checkpoint in prostate LNCaP cells under ionizing radiation*'. The present reproducibity analysis was the project of the PhD course **Logical Modeling for Experimental Design in Current and Future Biotechnology and Biomedicine**, offered by NTNU during the Autumn of 2018.

## Run notebook

First, you need to install the [colomoto-docker](https://github.com/colomoto/colomoto-docker). Then:
```
git clone https://github.com/bblodfon/colomotoGupta.git
cd pathTo/colomoto-docker
python colomoto_docker.py -V 2018-08-17 --bind /pathTo/colomotoGupta
```
The [gupta_john_zobolas.ipynb](https://github.com/bblodfon/colomotoGupta/blob/master/gupta_john_zobolas.ipynb) is the main notebook file.
