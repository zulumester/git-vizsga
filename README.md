t init -> git inicializálása a klónozáshoz

git clone https://github.com/szpeter992/git-vizsga-0205.git

cd git-vizsga-0205 -> klónozott mappa megnyitása

console . -> alapértelmezett editor megnyitása, esetünkben Visual Studio Code

touch README.md -> README.md fájl létrehozása
git add . -> fájl hozzáadása a repositoryhoz
git commit -m 'README.md fájlt létrehozva' 

touch .gitignore -> .gitignore fájl létrehozása
git add . -> fájl hozzáadása a repositoryhoz
git commit -m '.gitignore fájlt létrehozva' 

git staus -> fájlok státuszénak ellenőrzése

git branch console ->console ág létrehozása
git checkout console -> console ágra váltás

git remote add origin https://github.com/zulumester/git-vizsga-0205.git
git push -u origin master