# ESS-Report-generator
Python code that should be run on isca. It takes in a file with lists of folder and generates a tex file that can be compiled in latex with the correct format and appropriate section based on Exeter Sequencing Service (ESS) folder delivery format. Currently the format is for Illumina runs only but Nanopore runs report will come soon. 

## Steps

```
$python3 python_generator.py
```
You should get a prompt for the project number and the run number please fill them in with the capital M/V for miseq or Novaseq runs. 
```
$zc_sandox

$conda activate python_latex

$tectonic <output>.tex
```  
