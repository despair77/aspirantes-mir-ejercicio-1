cd documents
mkdir ejercicio
git config --global user.name Despair77
git config --global user.email aimealex4@gmail.com
git init
git add .
git commit -m "Version inicial"
git branch -M main
git remote add origin https://github.com/despair77/aspirantes-mir-ejercicio-1
git push -u origin main

git status
git add .
git commit -m “Agrega solución primer ejercicio”
git push -u origin main
