# Installation

```bash
cd themes
composer create-project puzzle_themes/fr puzzlefr
```
Depuis la racine du projet executer :
```bash
mkdir public/puzzlefr
mv themes/puzzlefr/public/* public/puzzlefr
```
Choisissez votre nouveau thème sur le canal :
```bash
Dans le panneau d'administration, allez dans les canaux et changez le thème du canal souhaité .
```

# Mise à jour

Depuis la racine du projet executer :
```bash
rm-rf public/puzzlefr
cd themes
rm -rf puzzlefr
composer create-project puzzle_themes/fr puzzlefr
```
Retourner à la racine du projet et executer :
```bash
mkdir public/puzzlefr
mv themes/puzzlefr/public/* public/puzzlefr
```
