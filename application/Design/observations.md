
# Observations — bêta simulée

> Scénario fictif basé sur la persona de Julienne et la page HTML actuelle. Aucun test n’a été réalisé avec une participante réelle.

## Contexte

- **Application :** Petites vies, catalogue des insectes de Suisse
- **Testeuse simulée :** Julienne, 23 ans, passionnée d’entomologie
- **Appareil :** téléphone
- **Observateur :** scénario de test simulé
- **Tâche :** trouver les insectes de jardin observables au printemps

## Test de compréhension — 5 secondes

- **Question :** « À votre avis, à quoi sert ce site ? »
- **Réponse simulée :** « C’est un catalogue pour découvrir les insectes de Suisse et les rechercher selon la saison ou l’endroit. »
- **Écart avec l’intention :** aucun écart important. Le catalogue et l’idée de recherche sont compris rapidement.

## Test de localisation — une tâche

- **Consigne :** « Montrez où vous appuieriez pour trouver les insectes de jardin à observer au printemps. »
- **Le bon contrôle est repéré :** oui, la testeuse ouvre « Affiner ma recherche ».
- **Hésitation :** elle se demande si le bouton « Voir les espèces » va vraiment filtrer la liste.
- **Dit à voix haute :** « Je choisis le jardin et le printemps, puis je valide. »
- **Aide de l’observateur :** non pour repérer les contrôles. La tâche complète reste toutefois bloquée par le filtre non fonctionnel.

## Résultat du parcours

La page présente des menus déroulants pour le lieu, la saison et le cycle de vie. Le parcours prévu parlait de cases à cocher : ce sont deux comportements différents. Dans le HTML actuel, le formulaire n’est pas relié à une logique de filtrage; après validation, la liste des quatre espèces ne change pas. La recherche d’un résultat précis et l’affichage d’un message lorsqu’aucune espèce ne correspond restent donc à implémenter.

## Changement prioritaire

- **Avant :** la testeuse choisit ses critères et valide, mais les quatre fiches restent affichées.
- **Après (prévu) :** appliquer les critères aux espèces et mettre à jour la liste et son compteur. Si aucun résultat ne correspond, afficher un message clair avec une action pour réinitialiser la recherche.
