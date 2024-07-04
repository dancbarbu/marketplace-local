# arome-locale

# web app using react and nodejs

# Structura Branch-urilor

Branch-ul va contine numele stroy-ului si optional o scurta descriere
Exemplu:
FRESHTECH-6-FE-Product-Listing-descriere-optionala

**Exemplu creeare branch:**

1. git fetch > comanda asta va actualizeaza folder **local** de git cu tot ce este nou in github **remote**
2. git checkout main > Ma mut pe branch-ul main
3. git pull origin **branch-name** > va aduceti **local** tot ce este in branch-ul **remote** selectat
4. git branch branch-name > va creeati un branch nou
5. git checkout branch-name >  va mutati pe branch-ul dorit(sau nou creeat in cazul asta)
* 4 si 5 se pot face cu o singura comanda git checkout -b branch-name, comanda asta va si creeaza un branch si va si muta

**alte comenzi ajutatoare**
git branch > va arata pe ce branch sunteti
git status > va arata ce fisiere au fost modificate local sau adaugate local
git restore file-name > va sterge toate modificarile locale in fisierul respectiv pana la ultimul commit

Pasii pentru push:
1. git add file-name(sau folder-name)
2. git commit -m "mesaj despre ce am lucrat la/in fiserele pe care vreau sa le urc pe github"
3. git push origin branch-name(branch-ul pe care sunteti si in care ati lucrat)
4. verficati in github branch-ul si o sa puteti sa deschideti un Pull Request pentru a merge-ui branch-ul vostru in branch-ul main
5. ma adaugati pe mine ca review-er, pe voi optional

Alte Informatii ajutatoare:
Cand o sa va copiati(git clone) prima oara proiectul local o sa trebuiasca sa deschideti un terminal in Vscode si sa executati comanda:

**npm install**

asta o sa va installeze toate dependintele local.
dependintele le puteti vedea in package.json si package-lock.json(asta e o versiune mai detaliata a package.json dar si cu versiunile blocate, pt a avea consistenta indeferent unde rulam app-ul). Dependintele sunt installe in folderul node_modules, deci si asta trebuie sa apara local dupa ce rulati **npm install**

![image](https://github.com/dancbarbu/arome-locale/assets/13649172/c9750350-95af-4dd8-8c39-7394de90f629)

