# Modèles UNIL pour XeLaTeX
Cf. les exemples pour plus d'infos. Ce package simplifie la création de documents respectant la charte graphique de l'UNIL (sans nécessairement y coller à 100%).

## Options
### Presets
* interne
* externe
* externe-strict
    * externe-strict-demo

### Autres options
* logo (couleur/noir/gris)
* decliner (non/premiere/partout)
* filigrane (non/derniere/premiere/partout)
* pageEtroite (large/etroite)
* futura
* espaceSignature

### Tokens
* date
* expadresse
* destadresse
* emetteur
* emetteursup
* contact

## Ressources nécessaires
### Dossier `/includes`
Pour des raisons de propriété intellectuelle, les fichiers nécessaires au typesetting de documents avec le paquet `charteunil` ne peuvent être mis à disposition ici. Vous pouvez les obtenir auprès d'Unicom ou en cherchant bien.

Voici la liste des fichiers et dossiers devant se trouver dans `/includes` : 
* le dossier `/FrutigerLTStd` doit contenir les fichiers `.otf` pour, au moins, les fontes suivantes :
    * Roman,
    * Bold,
    * Italic,
    * Light.
    * pour la convention de nommage des fichiers `.otf`, consulter `charteunil.sty`.
* `signature.pdf` : la signature (partie calligraphiée du logo), en noir 8%,
* `unilogo_couleur.pdf` : le logo complet, en couleur (texte en noir + signature en Pantone Process Blue C)
* `unilogo_nb.pdf` : le logo complet, en nuances de gris
