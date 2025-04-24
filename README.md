# Skupinovy-projekt

& "g:/win32app/Portable Python-3.10.5 x64/App/Python/python.exe" -m venv venv
& "g:/win32app/Portable Python-3.13.3 x64/python.exe" -m virtualenv venv

python -m venv venv (doma)

Set-ExecutionPolicy -Scope CurrentUser 

0

.\venv\Scripts\activate

pip install pygame

pip freeze > requirements.txt (udělá textový soubor s nainstalovanými knihovnami)
pip install requirements.txt

git clone odkaz
git add .
git commit -m "vložení req.txt"
git push origin main
git pull origin main

git stahni (jen git)
