# 2. Dépôts, parts et dette des stratégies

Le premier mécanisme central du dépôt concerne dépôts, parts et dette des stratégies.
Le code reçoit des données structurées, vérifie leurs contraintes puis applique la transition correspondante.
Les types publics fixent la forme des valeurs que les autres composants peuvent transmettre.
Les contrôles locaux empêchent qu’un état incomplet soit accepté comme une opération terminée.
Les valeurs persistantes servent de référence aux appels suivants et aux outils d’observation.
Les erreurs rendent explicites les préconditions qui ne sont pas satisfaites.
Les événements ou sorties exposent les résultats sans remplacer l’état canonique du protocole.
Une intégration doit respecter l’ordre des étapes et les unités utilisées par ces structures.

[Chapitre suivant : Rapports, profits et frais](03-rapports-profits-et-frais.md)
