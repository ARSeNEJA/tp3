# TP3 - Gestion de projets Java avec Git

## Objectif

Ce TP a pour but de mettre en pratique les notions suivantes :
- Collaboration à deux avec GitHub
- Suivi d’un projet Java structuré
- Respect des bonnes pratiques Git (commits, branches, issues, etc.)

## Membres du groupe

- 🧑 Joigneau Arsène (pseudo GitHub : `@ARSeNEJA`)
- 🧑 Gricourt Paul (pseudo GitHub : `@pseudo2`)

## Structure du projet
tp3/ ├── src/ 
     │ 
     └── ... (classes Java) 
     ├── .gitignore 
     ├── README.md 
     └── ...

## Mise en route

1. **Cloner le dépôt :**

```bash
git@github.com:ARSeNEJA/tp3.git
cd tp3
```
2.**Créer une branche :**

```
git checkout -b porthos    ## et création de la branche athos
```

3.**Travailler et versionner :**

```
git add .  ## les fichiers que l'on doit ajouter à notre commit
git commit -m " Ajout de la classe X" ## quand on fait des modifications
git push origin porthos/athos ## le git push origin notre_branche doit être fait qu'une seule fois, ensuite on a juste besoin de faire "git push" ou "git pull" pour récupérer le contenu du travail sur Github
```

4.**Faire une Pull Request sur GitHub pour intégrer les modifications.**




