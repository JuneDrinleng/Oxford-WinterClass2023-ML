# Oxford-WinterClass2023-ML
even copy the code from the slide we meet a lot of problems,so I trying to solve each problem and create the repository.  

As a greenhand，I have met so many problems  

so I hope that my experience could help every green hand to handle these problem.  

The session I have already upload will use some package in python  

here are them  

The code is mainly run on my macbook pro (m1 ver)  

and I have try it on my windows pc y9000p however there is some problem with sklearn  

when I transformed into mac, I surprisingly found that it works   


## Session 1  
pandas install by conda  

    conda install -c anaconda pandas 
numpy install by conda  

    conda install -c anaconda numpy  
    
## Session 2  
pandas install by conda. 

    conda install -c conda-forge missingno
    conda install -c "conda-forge/label/cf201901" missingno
    conda install -c "conda-forge/label/cf202003" missingno
    conda install -c "conda-forge/label/gcc7" missingno 

and sklearn can be install by following two path in conda. 

firstly, we can use the code from its website.  
https://scikit-learn.org/stable/install.html. 


step 1. 

    conda create -n sklearn-env -c conda-forge scikit-learn
    conda activate sklearn-env
step 2. 

    conda list scikit-learn  # to see which scikit-learn version is installed
    conda list  # to see all packages installed in the active conda environment
    python -c "import sklearn; sklearn.show_versions()"
secondly, we can also use the code from anaconda   
(however I have not tried it successfully on my windows pc for some unknown reasons.  

    conda install -c anaconda scikit-learn 
