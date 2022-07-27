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

git remote add origin https://github.com/manojbandi64/simple_dvc_demo.git
git branch -M main
git push -u origin main