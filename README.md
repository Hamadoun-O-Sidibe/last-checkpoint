# Pricing Card - Correction et refactorisation

## Objectif

Réparer un composant de carte de prix défectueux,
corriger ses bugs de mise en page et d'interaction,
puis le transformer en composant réutilisable avec l'aide de Cursor AI.

## Avant

Le composant initial présentait plusieurs problèmes :
- erreur de fermeture de la balise h2
- erreur sur le sélecteur :hover
- bouton sans interaction
- mise en page peu responsive
- composant difficilement réutilisable

## Après

Le composant a été :
- corrigé
- rendu responsive
- amélioré visuellement
- rendu interactif
- refactorisé pour être réutilisable

## IA utilisée

Cursor AI

## Prompt utilisé

Analyse ce composant HTML/CSS défectueux et aide-moi à le corriger.

1. Identifie les erreurs HTML et CSS qui peuvent provoquer des problèmes de mise en page ou empêcher les interactions de fonctionner.
2. Corrige les erreurs sans changer inutilement le contenu.
3. Améliore la mise en page pour obtenir une carte de prix propre, moderne, responsive et centrée.
4. Corrige les états du bouton, notamment le hover.
5. Ajoute une vraie interaction au bouton avec JavaScript.
6. Refactorise ensuite le composant afin qu'il soit réutilisable avec une fonction de type Card(titre, prix, fonctionnalités).
7. Le composant doit permettre de créer facilement plusieurs cartes de prix avec des données différentes.
8. Sépare clairement la structure HTML, les styles CSS et la logique JavaScript.
9. Explique-moi les corrections effectuées afin que je puisse les comprendre en tant que débutant en développement full-stack.
10. Donne-moi le code final complet dans un nouveau fichier que je pourrai tester dans le navigateur.


## Test

Le fichier final a été ouvert dans le navigateur afin de vérifier :
- l'affichage de la carte
- le responsive
- l'effet hover
- le fonctionnement du bouton
- la création de plusieurs cartes