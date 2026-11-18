# La boîte mystère

**20 minutes — En binôme — Méthode inductive**

## Consignes

Modifier successivement `width`, `padding`, `border` et `margin` sur l'élément `.boite` et observer comment chaque propriété influence la taille visible de la boîte.

| # | Consigne | Propriété à utiliser |
|---|----------|---------------------|
| 1 | Donner à la boîte une **largeur** de 200 px | `width` |
| 2 | Ajouter un **espace intérieur** de 20 px | `padding` |
| 3 | Ajouter une **bordure** de 5 px, noire et pleine | `border` |
| 4 | Ajouter un **espace extérieur** de 30 px | `margin` |
| 5 | Passer la boîte en **`border-box`** et observer la différence | `box-sizing` |
| 6 | Arrondir les **coins** de la boîte | `border-radius` |
| 7 | Ajouter une **ombre portée** subtile | `box-shadow` |

## Bilan

Après chaque modification, notez la taille totale de la boîte visible dans le navigateur (avec les outils de développement).

**Questions à se poser :**

- Avec `content-box` (défaut), la boîte fait-elle 200 px ou plus ?
- Avec `border-box`, la boîte fait-elle toujours la même taille ?
- Quelle est la différence entre `padding` et `margin` ?
