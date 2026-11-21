# Règles des étiquettes et des versions

Chaque issue porte **une seule étiquette par famille**. Chaque famille a son préfixe et sa couleur, pour qu'elles se rangent ensemble dans GitHub.

## 1. Type — obligatoire

| Étiquette | Pour quoi |
| --- | --- |
| `type: user story` | Une fonction décrite du point de vue de l'utilisateur (US-01, US-02…) |
| `type: incident` | Quelque chose ne marche pas : un critère a échoué, l'app plante |
| `type: demande` | Une nouvelle idée ou une amélioration |
| `type: tâche` | Un travail qui n'est pas une fonction : icône, fiche App Store, politique de confidentialité… |

Les formulaires **Incident**, **Demande** et **Tâche** posent le type automatiquement.

## 2. Priorité — obligatoire

| Étiquette | Pour une story | Pour un incident |
| --- | --- | --- |
| `P1 · indispensable` | Sans elle, pas de sortie | Bloquant : l'app plante ou une fonction clé ne marche pas |
| `P2 · important` | Attendue, mais la sortie est possible sans | Gênant, mais on peut contourner |
| `P3 · souhaitable` | Un plus, si on a le temps | Détail : faute de texte, alignement… |

Pour un incident ou une demande, la priorité est posée au moment du tri, quand on la lit ensemble.

## 3. Zone — la partie du produit concernée

Une étiquette `zone: …` par grande partie fonctionnelle du produit, propre à chaque projet. Une zone = un domaine clair : on ne mélange pas deux sujets dans la même zone.

| Étiquette | Contenu |
| --- | --- |
| `zone: [nom]` | [Ce qu'elle couvre] |

## 4. Offre — si le produit a plusieurs offres

`offre: [nom]` (par exemple `offre: gratuit`, `offre: complet`). Inutile si le produit n'a qu'une offre.

## 5. Statut

| État | Signification |
| --- | --- |
| Ouverte, sans statut | À faire |
| `statut: à tester` | Codé, à vérifier sur l'appareil |
| `statut: bloqué` | En attente d'une décision ou d'un élément extérieur |
| Fermée | Validée (story) ou corrigée (incident) |

## Versions : les jalons (Milestones)

Les versions ne sont pas des étiquettes mais des **jalons** GitHub, avec une barre de progression. Chaque issue est rattachée à la version qui la livre.

| Jalon | Contenu |
| --- | --- |
| **v0.1** | Le plus petit produit testable |
| **v0.2**, **v0.3**… | Ajouts par petites étapes |
| **v1.0** | La version publiée |

Un incident est rattaché à la version qui le corrige.

## Le cycle d'une story

1. Ouverte, sans statut : à coder.
2. Codée : `statut: à tester`.
3. Testée sur l'appareil : chaque critère qui passe est coché ; chaque critère qui échoue donne un **Incident** avec son numéro (`US-05.3`).
4. Tous les critères cochés : la story est fermée.
