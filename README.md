Calculatrice PySide6

Une calculatrice simple et élégante développée en Python avec PySide6, permettant les opérations de base (+, -, x, /) et offrant une interface graphique moderne.

Fonctionnalités

Opérations de base : addition, soustraction, multiplication, division.

Interface graphique : design sombre et boutons stylisés.

Support clavier : utilisez les touches numériques et opérateurs, Enter pour = et Backspace pour supprimer le dernier caractère.

Bouton C : réinitialise l'affichage.

Affichage dynamique : le résultat s’affiche en temps réel après calcul.

Installation

Installer Python 3.10+ (ou version compatible).

Installer PySide6 si ce n’est pas déjà fait :

pip install PySide6

Utilisation

Cloner le projet ou télécharger le fichier calculatrice.py.

Exécuter le script :

python calculatrice.py


La calculatrice s’ouvre et est prête à l’emploi.

Touches clavier prises en charge :

0-9 : chiffres

+, -, x, / : opérations

Enter : calculer le résultat (=)

Backspace : supprimer le dernier caractère

C : effacer l’écran

Structure du code

Calculatrice(QWidget) : classe principale contenant l’interface et la logique.

BUTTONS : dictionnaire définissant les boutons et leurs positions dans la grille.

OPERATIONS : liste des opérateurs pris en charge.

Méthodes principales :

compute_result() : calcule le résultat de l’expression.

clear_result() : réinitialise l’écran.

number_or_operation_pressed() : gère l’ajout des chiffres et opérateurs.

remove_last_character() : supprime le dernier caractère.

connect_keyboard_shortcuts() : connecte les touches du clavier aux actions des boutons.

<img width="1172" height="622" alt="calculatrice" src="https://github.com/user-attachments/assets/13dae7f6-028e-4ede-aefd-1bc97e7e5ace" />


Licence

Ce projet est open-source et libre d’utilisation.
