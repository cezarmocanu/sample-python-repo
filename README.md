# Navigare foldere

#### Vezi folderul in care te afli

```bash
dir # windows cmd
pwd # linnux/unix
```

#### Schimbi partitia

D:

#### Change directory

```
# Navigare intr-un folder anume
cd [folderul in care sa navighez]

# Folderul anterior
cd ..
```

# Git Base

### Repository - un proiect de git

#### Initializam un repo in folderul nostru

```
git init
```

#### Legam repo-ul din registry(Github) cu repo-ul local si numim legatura origin
```
git remote add origin https://github.com/cezarmocanu/sample-python-repo.git
```

### Adaugam in commit(cutie goala) fisierele modificate

```
git add . # adauga toate fisierele modificare
git add [nume_fisier/path_fisier] # adauga un singur fisier
```

### Inchidem commitul (cutia cu fisiere) si ii punem o eticheta/un mesaj

```
git commit -m "Mesajul meu descriptiv"
```

### Trimitem commiturile la cloud 
```
git push # cand exita branch-ul
git push --set-upstream origin main # cand initializam proiectul
```

### Clonarea proiectului pe alta masina sau amsina existenta

```
git clone [url-ul de la git]
git clone [url-ul de la git] [folderul-destinatie]
```

# Git Colab


### Ia ultimele modificarei pe branch-ul pe care ma aflu
### Sincronizeaza repo-ul cu repo-ul din cloud DESCARCAND modificarile
```
git pull
```

### Sincronizeaza repo-ul cu repo-ul din cloud fara sa descarce modificarile
```bash
git fetch
```

### Afiseaza toate branchurile locale
```bash
git branch -a
```

### Te muta pe un anumit branch
```bash
git checkout [nume-branch]
```

### In caz ca branchul nu are modificarile din cloud dupa checkout facem git pull







