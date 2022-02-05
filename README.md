t init -> git inicializálása a klónozáshoz

git clone https://github.com/szpeter992/git-vizsga-0205.git

cd git-vizsga-0205 -> klónozott mappa megnyitása

coode . -> alapértelmezett editor megnyitása, esetünkben Visual Studio Code

touch README.md 

touch .gitignore 
 
git staus

git commit -m '.gitignore és a README.md fájlok létrehozva, .gitignore-ba felvételre kerültek a megadott fájlformátumok'



git branch console ->console ág létrehozása
git checkout console -> console ágra váltás

git remote add origin https://github.com/zulumester/git-vizsga-0205.git
git push -u origin master