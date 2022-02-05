t init -> git inicializálása a klónozáshoz

git clone https://github.com/szpeter992/git-vizsga-0205.git

cd git-vizsga-0205 -> klónozott mappa megnyitása

coode . -> alapértelmezett editor megnyitása, esetünkben Visual Studio Code

touch README.md 

touch .gitignore 
 
git staus

git commit -m '.gitignore és a README.md fájlok létrehozva, .gitignore-ba felvételre kerültek a megadott fájlformátumok'

git add .
git commit -m 'style.css-ben a szükséges változtatást elvégeztem'

git branch console ->console ág létrehozása
git checkout console -> console ágra váltás

git add .
git commit -m 'app.js-ben a szükséges változtatást elvégeztem'

git rm origin

git remote add origin https://github.com/zulumester/git-vizsga.git
git push -u origin main
git push -u origin console