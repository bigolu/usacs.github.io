# How to build!
1. install python3
2. (Optionally) make a virtual environment:
    1. `pip3 install virtualenv`
    1. `virtualenv -p python3 venv`
    1. `source venv/bin/activate`
2. install dependencies via pip3 (`pip3 install -r requirements.txt`)
3. run `python3 scripts.py build` from the root directory of the git repo
5. html files apear in root of git repo

## IMPORTANT NOTE
The index page isnt compiled like the rest of the site because its fancy, for now edit it in its html file

## How to add css or javascript to a individual file
Add it at the top of the views/<yourfile>.mustache file instead of in a head tag. See /views for examples

## How to edit layout stuff like the nav bar
Edit the layout file layouts/layout.mustache

More functionality coming soon!
See the original repo for [some reference](https://github.com/mjrb/compile.py)!
The build config is inline in scripts.py :C @mjrb will hopefully fix this.
