create env

'''bash
conda create -n wineq python=3.7 -y
'''

activate env
'''bash
conda activate wineq
'''

created requirements file

installed the requirements
'''bash
pip install -r requirements.txt
'''
git init

dvc init

dvc add data_given/winequality.csv

git add

git commit -m "first commit"