# TP3 – Marché de Crypto-monnaie (Travail en Équipe avec Git)

## Objectif

Ce troisième TP a pour objectif de développer une application Java simulant un **marché de crypto-monnaies**, tout en travaillant **en binôme** avec **GitHub**.  
L’accent est mis sur :
- La collaboration via GitHub (invitation, clone, synchronisation)
- Le développement en branches
- La fusion de branches (merge)
- L'organisation d'un projet Java structuré

## Organisation & Rôles

- Le projet est réalisé en binôme.
- L’un assume le rôle d’**Athos**, l’autre de **Porthos**.
- En cas de trinôme, deux peuvent partager le rôle d’Athos.
- **Athos** : implémente la classe `CryptoMarche.java`
- **Porthos** : implémente la classe `Portefeuille.java`

## Membres du groupe

- Joigneau Arsène (pseudo GitHub : `@ARSeNEJA`)
- Gricourt Paul (pseudo GitHub : `@P4poule`)
  
## Structure du projet
tp3/

├── README.md 
|
└── src/ 
|
├── CryptoMarche.java 
|
├── Cryptomonnaie.java 
|
├── Portefeuille.java 
|
└── TestCryptoMarche.java

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




