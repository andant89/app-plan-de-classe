# Cadrage – Plan de classe

Ce document se remplit **avant** le cahier des charges. Il sert à passer d'une idée floue à une idée claire, testée et triée. Le même gabarit sert pour tous les projets : sur un petit projet, les réponses sont simplement plus courtes (une ligne au lieu d'un paragraphe), mais on ne saute aucune étape.

Pour le remplir avec Claude, dis : **« Lance une séance de brainstorming »**. Claude pose les questions une par une et remplit ce fichier au fur et à mesure.

**État** : arrêté (non nécessaire pour un petit outil, décision du PO) · **Décision** : go, sans cadrage complet · **Date** : 2026-11-21

---

## 0. L'idée brute

> La maîtresse de notre fils trouve que placer les enfants dans la classe est un casse-tête. Régulièrement, elle les change de table en tenant compte des 1P et 2P, des enfants qui ont besoin de plus ou de moins d'attention, et en évitant qu'ils se retrouvent toujours avec les mêmes. Une petite app où elle entre les prénoms et quelques critères pourrait l'aider.

- **Pourquoi moi, pourquoi maintenant** : la maîtresse nous en a parlé, et j'ai les moyens de l'aider.
- **Ce que je veux en retirer** : me rendre utile, et trouver une utilité concrète à ce que je sais faire.

---

## 1. Le problème

### La phrase problème

> **La maîtresse de 1P-2P** a du mal à **refaire régulièrement le plan de classe** parce que **beaucoup de critères doivent être tenus en tête en même temps**. Aujourd'hui, elle se débrouille avec **[solution actuelle inconnue : à lui demander]**.

*Hypothèses du PO, à vérifier avec la maîtresse.*

### Les 5 pourquoi

Chercher la vraie cause du problème en demandant « pourquoi ? » cinq fois.

1. Pourquoi est-ce un casse-tête ? Trop de critères à tenir en tête en même temps, et une tâche qui revient souvent et prend du temps à chaque fois. *(hypothèse)*
2. Pourquoi autant de critères ? La classe mélange deux degrés (1P et 2P) ; les enfants ont des besoins d'attention très différents ; certains ne s'entendent pas ou se dissipent ensemble. *(hypothèse)*
3. Pourquoi ? [À compléter après l'entretien]
4. Pourquoi ? [Réponse]
5. Pourquoi ? [Réponse] → **cause profonde** : [Réponse]

### Jobs to be done

| Quand… (situation) | Je veux… (action) | Pour… (résultat) |
| --- | --- | --- |
| [Situation] | [Action] | [Résultat] |

---

## 2. Les utilisateurs

### Personas

| Persona | Profil (âge, contexte, aisance avec le numérique) | Frustration principale | Objectif |
| --- | --- | --- | --- |
| [Prénom] | [Profil] | [Frustration] | [Objectif] |

### Carte d'empathie (persona principal)

| Il pense | Il ressent | Il voit | Il dit | Il fait |
| --- | --- | --- | --- | --- |
| [ ] | [ ] | [ ] | [ ] | [ ] |

### Parcours actuel

Les étapes que suit aujourd'hui le persona principal, et où ça coince.

1. [Étape] — [ce qui coince, ou « ok »]
2. [Étape] — [ ]
3. [Étape] — [ ]

### Entretiens (Mom Test)

Interroger 3 à 5 personnes sur ce qu'elles ont **vraiment fait** la dernière fois, pas sur ce qu'elles feraient. Questions types : « Raconte-moi la dernière fois que… », « Qu'as-tu essayé ? », « Combien ça t'a coûté (temps, argent) ? ».

Questions préparées pour la maîtresse :

1. Raconte-moi la dernière fois que tu as changé les places : comment tu t'y es prise ?
2. Combien de temps ça t'a pris ?
3. À quoi tu fais attention quand tu places les enfants ?
4. Qu'est-ce qui est le plus pénible dans tout ça ?
5. Tous les combien tu changes les places, et pourquoi à ce rythme ?
6. Combien de tables et d'élèves as-tu cette année ?
7. Tu as déjà essayé un outil (Excel, une app, un plan à aimanter) ? Qu'est-ce qui n'allait pas ?

Note : le prototype lui a déjà été envoyé le 2026-11-21. Recueillir aussi ses retours sur l'app, séparément de ses réponses sur sa façon de faire actuelle.

| Personne | Ce qu'elle a vraiment fait | Ce qui la gêne le plus | Surprise |
| --- | --- | --- | --- |
| La maîtresse | [ ] | [ ] | [ ] |

**Ce que j'en retiens** : [2 ou 3 phrases.]

---

## 3. Les idées (brainstorming)

Règle d'or : d'abord produire sans juger, ensuite seulement trier.

### « Comment pourrait-on… ? »

Chaque frustration devient une question ouverte.

- Comment pourrait-on [ ] ?
- Comment pourrait-on [ ] ?

### Carte mentale

[Le problème au centre, les branches autour. Coller un lien, une photo, ou une liste à puces imbriquée.]

- [Problème]
  - [Branche]
    - [Idée]

### Crazy 8

Huit idées d'écran ou de fonction en huit minutes. La quantité compte, pas la qualité.

1. [ ] 2. [ ] 3. [ ] 4. [ ] 5. [ ] 6. [ ] 7. [ ] 8. [ ]

### SCAMPER (à partir d'une app existante : [nom])

| Question | Idée |
| --- | --- |
| **S**ubstituer : que remplacer ? | [ ] |
| **C**ombiner : qu'assembler ? | [ ] |
| **A**dapter : qu'emprunter ailleurs ? | [ ] |
| **M**odifier : qu'agrandir, réduire, changer ? | [ ] |
| **P**roposer un autre usage | [ ] |
| **É**liminer : que supprimer ? | [ ] |
| **R**éorganiser : quel autre ordre ? | [ ] |

---

## 4. Le tri

### Concurrence

| App ou solution | Ce qu'elle fait bien | Ce qui lui manque | Prix |
| --- | --- | --- | --- |
| [Nom] | [ ] | [ ] | [ ] |

**Ma différence** : [Une phrase.]

### Matrice valeur / effort

| | Effort faible | Effort élevé |
| --- | --- | --- |
| **Très utile** | [À faire d'abord] | [À planifier] |
| **Peu utile** | [Plus tard, si temps] | [À oublier] |

### MoSCoW

| Idée | Must (P1) | Should (P2) | Could (P3) | Won't (pas maintenant) |
| --- | :---: | :---: | :---: | :---: |
| [Idée] | ✓ | | | |

### Story mapping

Les grandes étapes du parcours, puis les fonctions sous chaque étape. Tout ce qui est au-dessus de la ligne forme la V1.

| [Étape 1] | [Étape 2] | [Étape 3] |
| --- | --- | --- |
| [Fonction] | [Fonction] | [Fonction] |
| **— ligne V1 —** | **— ligne V1 —** | **— ligne V1 —** |
| [Fonction plus tard] | [ ] | [ ] |

---

## 5. La validation

### Lean Canvas

| Bloc | Contenu |
| --- | --- |
| Problème (3 au plus) | [ ] |
| Clients cibles | [ ] |
| Promesse unique | [ ] |
| Solution (3 fonctions clés) | [ ] |
| Canaux (comment ils me trouvent) | [ ] |
| Revenus | [ ] |
| Coûts | [ ] |
| Indicateur clé (comment je sais que ça marche) | [ ] |
| Avantage difficile à copier | [ ] |

### Prototype

- **Forme** : [papier, maquette, écran cliquable…] · **Lien** : [ ]
- **Montré à** : [qui]
- **Où ils ont hésité** : [ ]
- **Ce que je change** : [ ]

### Pré-mortem

« Dans un an, le projet a échoué. Pourquoi ? »

| Cause possible d'échec | Ce que je fais dès maintenant |
| --- | --- |
| [ ] | [ ] |

### Décision

- [ ] Le problème est réel (confirmé par au moins 3 personnes).
- [ ] Je sais pour qui je le fais.
- [ ] La V1 tient en peu de fonctions.
- [ ] Je connais ma différence.
- [ ] Les risques principaux ont une parade.

**Décision** : [go / ajuster / abandon], parce que [raison].

---

## Vers le cahier des charges

| Ce cadrage | Alimente la section du cahier des charges |
| --- | --- |
| Phrase problème, promesse, nom | Présentation du projet |
| Personas, entretiens | Public cible |
| MoSCoW, story mapping (ligne V1) | Fonctionnalités V1 et futures |
| Concurrence, prototype | Design et expérience utilisateur |
| Lean Canvas (revenus, coûts) | Modèle économique |
| Pré-mortem, questions restées sans réponse | Planning et questions ouvertes |
