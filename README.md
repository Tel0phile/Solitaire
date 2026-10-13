# Solitaire

## Prérequis & Technologies
- **JDK 17** ou supérieur (ex: OpenJDK 27).
- **JavaFX 21** (`javafx-controls`, `javafx-graphics`).
- **IDE** : IntelliJ IDEA (recommandé).

## Structure du Projet
```text
Solitaire/
├── src/
│   ├── Cards/                 
│   └── Solitaire/
│       ├── Model/             
│       └── View/             
├── .gitignore
└── README.md
```
## Configuration & Lancement

Cloner le dépôt 

Ouvrir sous IntelliJ IDEA :

Ouvrez le dossier du projet dans IntelliJ.

vérifer que les librairies JavaFX sont bien liées au module dans Project Structure > Modules > Dependencies.

Configurer les ressources :

Fais un clic droit sur le dossier src/Cards.

Sélectionne Mark Directory as > Resources Root.

Lancer le jeu :

Exécute la classe principale Solitaire.View.SolitaireGui.

## Règle du jeu

Pioche / Talon : Cliquez sur la pioche pour révéler une carte dans le talon. Cliquez sur le talon pour la sélectionner.

Colonnes : Cliquez sur une carte visible pour sélectionner la sous-pile, puis cliquez sur la colonne de destination.

Fondations : Cliquez sur la fondation souhaitée pour y envoyer la carte sélectionnée.
