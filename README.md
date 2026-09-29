# symbios
python -m venv .venv. .venv/bin/activatepip install --upgrade pip setuptools wheel pytest build twinepip install -e .pytest -qpython -m buildpython -m twine check dist/*
git init
git add .
git commit -m "Initialize Symbiote package"
git branch -M main
git remote add origin git@github.com:thomasbricknell9-pixel/symbiote-.git
git push -u origin main