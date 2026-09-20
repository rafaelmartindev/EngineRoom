Usaremos esta política:
Crear el PR en GitHub.
Revisarlo.
Hacer el Merge desde GitHub (botón).
Actualizar el repositorio local con:
git switch main
git pull origin main
git branch -d docs/project-foundation
git push origin --delete docs/project-foundation
