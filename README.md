# Start Jupiter from a virtualenv

python3 -m venv venv

source venv/bin/activate

(venv) $ pip3 install ipykernel

(venv) $ ipython kernel install --user --name=[projectname]

(venv) $ pip3 install [whatever else you want]

jupyter notebook

New -> <[projectname]