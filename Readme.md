# Installation

```bash
cd themes
composer create-project puzzle_themes/fr puzzlefr
php bin/console sylius:theme:assets:install
```

Choisissez votre nouveau thème sur le canal :
```bash
Dans le panneau d'administration, allez dans les canaux et changez le thème du canal souhaité .
```

# Mise à jour

```bash
cd themes
rm -rf puzzlefr
composer create-project puzzle_themes/fr puzzlefr
php bin/console sylius:theme:assets:install
```

