create env
```bash
conda create -n ml_demo python=3.7 -y
```
activate env
```bash
conda activate ml_demo
```

create a req file

install the req
```bash
pip install -r requirements.txt
```

download the data 
git init
dvc init
dvc add data_given/bike_sharing.csv

git add .

git commit -m "first commit"