# Parcours de non-régression

À refaire **à chaque nouvelle version**, avant de tester les nouveautés. Il vérifie en quelques minutes que ce qui marchait marche toujours.

## 1. Tests automatiques

[Comment les lancer, par exemple : dans Xcode, Product › Test (⌘U).]

- [ ] Tous les tests sont verts, et leur nombre est celui annoncé dans la livraison.

Si un test est rouge, ouvre un **Incident** avec le nom du test, sans aller plus loin.

## 2. Parcours sur l'appareil

[Une ligne par fonction essentielle, avec la story entre parenthèses. Exemple :]

- [ ] **[Action]** : [ce que je fais], [ce que je dois voir]. *(US-01)*

## 3. Les critères touchés par la version

Chaque livraison donne la liste des **critères touchés** : les critères déjà validés que la nouvelle version modifie, ou dont l'écran change. Re-teste chacun d'eux.

Si la version change l'apparence d'un écran, relis aussi les critères de toutes les stories de cet écran : une information validée ne doit pas disparaître sans décision du PO.

Un point qui échoue : ouvre un **Incident** avec le numéro du critère concerné (par exemple `US-05.3`).
