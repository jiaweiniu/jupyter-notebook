# jupyter-notebook
how to set python2 and python3 in jupyter 
if you want to install python2 

(upgrade pip2)
python -m pip install --upgrade pip 
(install jupyter)
python -m pip install jupyter  
(open jupyter on your computer)
jupyter notebook  

this time, you only have python2, but if you also want to run jupyter on python3,you can set up a python3 kernel after checking your version of pip

(upgrade pip3)
sudo pip3 install --upgrade pip
(install kernel)
python3 -m pip install ipykernel
(if it can not work try this command)
python3 -m pip install ipykernel --user
python3 -m ipykernel isntall --user
(Finally, check the new botton.Done!)
