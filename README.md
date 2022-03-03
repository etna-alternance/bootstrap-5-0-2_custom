# bootstrap-5-0-2_custom
Theme bootstrap qui correspond au design system qu'on prévoit pour le refresh des outils

## Installation

Pour lancer bootstrap 5.0.2, il faut avoir installé :
- node js
- npm
- dart
- sass

Une fois tout installé, il faut :
- télécharger le repo
- aller dans le repo
- lancer la commande : npm install
- puis pour lancer le server de pré-visualisation faire : npm start

Pour voir le rendu de pré-visualisation : http://localhost:9001/

## Personnalisation

Nous, nous avons un fichier custom.scss. C'est là que toutes nos modifications ce trouvent.
Vous pouvez vous baser sur les exemples que vous voyez car ils sont mis à jour en conséquence pour donner un exemple de ce que ça sera.

```La base actuelle
bootstrap-5.0.2/
├── scss
    └── custom.scss
```

## Nos modifications
 Voici la liste des modifications effectuées.

### Les couleurs
Les gris sont limités à 5.
On se retrouve avec 6 couleurs (blue, green, red, yellow, orange, purple) chacune avec 4 déclinaisons (to improve).

### Les bordures
Des modifications légères comme le radius à 5px.

### Les Headings
Plus grands de 0,5 rem que prévu par Bootstrap.

### Blockquotes
La couleur qui sera abricot.

### Les tableaux
Ici plus de changements, on change les bordures, les fonds, les couleurs...

### Les boutons
On apporte plus de simplicité et on révise le style des boutons large et small pour correspondre à nos besoins.

### Les éléments de formulaires
On revoit le look des inputs, selects, range, checkbox...
