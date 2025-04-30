# Corrélation n'est pas causalité - Le jeu de cartes

Un jeu de cartes pédagogique et ludique pour comprendre la différence entre corrélation et causalité.

## 🎯 Description

Ce projet affiche des cartes pour un jeu sur le thème de la corrélation et de la causalité. Il permet d'afficher et d'imprimer :
- Des cartes de variables (événements à corréler)
- Des cartes de facteurs de confusion
- Des cartes de structure (définissant le type de corrélation)

## 🛠️ Installation

1. Clonez ce dépôt :
```bash
git clone https://github.com/votre-compte/correlation-causalite-cartes.git
```

2. Ouvrez le projet :
- Soit avec un serveur web local (recommandé)
- Soit en ouvrant directement `index.html` dans votre navigateur

## 📑 Structure du projet

```
correlation_causalite_cartes/
├── index.html          # Page principale
├── styles.css          # Styles des cartes et de l'interface
├── regles.md          # Règles du jeu en markdown
├── marked.min.js      # Bibliothèque pour le rendu markdown
└── data/              # Contenu des cartes
    ├── cartes_variables.txt
    ├── facteurs_confusion.txt
    └── structures.txt
```

## 🎮 Utilisation

1. Ouvrez la page dans votre navigateur
1. Utilisez les boutons pour afficher différents types de cartes ou les règles du jeu
1. Utilisez le bouton "Imprimer" pour imprimer les cartes ou les règles

## 🖨️ Impression

- Les cartes sont optimisées pour l'impression sur papier A4
- Chaque type de carte a une couleur de bordure distincte
- Les règles s'impriment sur une page séparée (petit bug : une page vide en début de document)


## 🎨 Personnalisation

Pour modifier l'apparence des cartes, éditez :
- `styles.css` pour les styles généraux
- Les classes CSS correspondantes pour les couleurs et la mise en page

Pour modifier le contenu des cartes, éditez les fichiers texte dans le dossier `data/` :
- `cartes_variables.txt` : Liste des événements à corréler
- `facteurs_confusion.txt` : Liste des facteurs de confusion possibles
- `structures.txt` : Types de corrélations (plus/moins)

## 📝 License

Ce projet est sous licence libre - voir le fichier LICENSE pour plus de détails.

## 🤝 Contribution

Les contributions sont les bienvenues !
