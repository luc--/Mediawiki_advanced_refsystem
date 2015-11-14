# Mediawiki_advanced_refsystem

Lorsque l'on souhaite numériser un livre sous wikisource, il appert 
que l'outil de référence n'est pas toujours pleinement adapté.
Ce **modèle** permet une utilisation avancée des notes tout en étant pleinement compatible avec la fonction `ref`
de mediawiki.

## Licence

Ce modèle est proposé sous la licence GPLv3.

## Installation

Vous n'avez qu'à installer le code de `Modèle:Note.wikimedia` dans une page `Modèle:Note` (ou autre selon le langage de votre wiki).

## Utilisation

````mediawiki
{{Note|t|id|tr}}
````

Tous les paramètres sont optionnels. Si on en met aucun (`{{Note}}`), rien n'est affiché.

Les deux paramètres correspondent à l'utilisation normale des références :
- `{{Note|t}}` donne `<ref>t</ref>` ;
- `{{Note|t|id}}` donne `<ref name="id">t</ref>`.

Le troisième paramètre permet d'afficher autre chose que le numéro de la note (paramètre `tr`).
