# EXPLORING FURTHER RELATIONS OF METRICAL STRENGTH AND PITCH RELATIONS IN TURKISH MAKAM MUSIC

This repo contains a jupyter notebook for the research:
EXPLORING FURTHER RELATIONS OF METRICAL STRENGTH AND PITCH RELATIONS IN TURKISH MAKAM MUSIC 

In this research we further develop the research of Holzapfelet et al [1]
exploring  the  reinforcement  of  meter  in  the music of Turkish Makam. 
Our research follows a similar methodology to that described by Holzapfel, 
deriving note onset  distributions  which  we  subsequently  correlate  to 
weighted usul histograms used  to  formalise  meter.   

In particular, we aim to answer three main questions:
RQ1 - To  what  extent  are  the  findings  andconclusions drawn in Holzapfel et al’s work reproducible on  a different  data-set?   
RQ2 - To  what degree  does thechoice ofmakamalso act to reinforce or diminish metricalstrength?  
RQ3 - To what extent do pitch relations acrossmakamswith differingusulsact to also reinforce metre?

We find  the  results  of  [1]  to  be  reproducible  such  that  our research  is  able  to  identify  similar 
correlation  patterns across all usul considered. 
Consistent correlation variation acros smakams are also identified.  
In addition, our work goes  further  to  assess  the  extent  to  which  pitch  is  used to  reinforce  
metrical  structure  in makam (to  the  best  ofour knowledge,  not previously addressed in past works).
Although no immediate patterns are identified, we suggest subsequent developments which could be made in future works  to 
further  explore  the  role  of  pitch  in  metrical reinforcement.

[1]
> Andre Holzapfel and Barıs  Bozkurt. Metrical strength and contradiction in turkish makam music. In Proceedings of the 2nd CompMusic Workshop; 2012 July 12-13, pages 79–84, 2012. http://mtg.upf.edu/node/3886

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

### Prerequisites

Python and the following modules are necessary to run the notebook correctly: music21, numpy, matplotlib, scipy and pandas. 

You can install the modules required simply running (the file requiremennts.txt) is in the repository

```
$ pip install -r requirements.txt
```

Otherwise, you can manually install the single modules with the following commands: 

In Ubuntu the user can install all these modules it is as simple as typing on the Terminal:
```
$ sudo apt-get install python-dev python-numpy python-matplotlib python-scipy python-pandas
$ pip install music21
```

In OSX the user can install these modules by typing on the Terminal:

```
$ brew install python
$ pip install numpy matplotlib scipy pandas
$ pip install music21
````

In Windows the user can refer to this link to install python on your local machine: https://docs.python.org/3/using/windows.html and install the other modules by typing on the Terminal: 

```
$ pip install pandas numpy scipy matplotlib music21
```

### Clone or Download the repository 

Clone or download the repository. 
It contains a jupyter notebook, please read Jupyter Notebook instruction to properly change directories paths and run the notebook correctly.

Command to clone the repository:
```
$ git clone https://github.com/RonFrancesca/makam_research.git
```

The dataset can be downlaoded at the following links:
- download the full pdf score dataset here: https://github.com/MTG/SymbTr-pdf 
- download the full xml files dataset here: https://github.com/MTG/SymbTr/releases/tag/v2.4.3


### Jupyter Notebook instructions
Install Jupyter Notebook according to the its instructions https://jupyter.org/install

Start up jupyter notebook

```
$ jupyter notebook
```

Follow instructions appearing in the console regarding navigating your browser to the notebook

### MuseScore 

The user will also need a score editor to follow the examples. 
MuseScore (suggested) could be download at the following link: https://musescore.org

# License
This project is licensed under a Creative Commons Attribution 4.0 International License (CC BY4.0). Attribution:Dougal Shakespeare, Francesca Ronchini.  “Exploring Further Relations of Metrical Strength and Pitch Relations in Turkish Makam music”. 

## Authors 
- Francesca Ronchini
- Dougal Shakespeare

