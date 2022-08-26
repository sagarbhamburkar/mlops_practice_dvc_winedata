create conda env 
'''bash
conda create -n venv_mlops_wine python=3.7 -y

activate env
'''bash
conda activate venv_mlops_wine

create requirements.txt
'''bash
pip install -r requirements.txt

download data from 
https://drive.google.com/drive/folders/1xw0XX-WK74uxtFFLySbtnX-ODdmdK5Ec

git init
dvc init
dvc add data_given/winequality.csv
git add .
git commit -m "first commit"
git add . && git commit -m "update readme.md"