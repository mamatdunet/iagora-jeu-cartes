# Causons IA — jeu de cartes de conversation sur l'IA

IAgora × Amuseurs — festivals IA 2026.

Application autonome en un seul fichier : ouvrez `index.html` dans un navigateur
(ou publiez le dépôt avec GitHub Pages).

## Modification des cartes

La consultation, l'impression et l'export sont libres. Modifier, ajouter, importer
ou réinitialiser des cartes demande le mot de passe d'édition (communiqué à l'équipe).
Une fois saisi, il reste valable jusqu'à la fermeture de l'onglet ; le lien
« verrouiller l'édition » le révoque.

Le mot de passe n'est pas stocké en clair : la page compare son empreinte SHA-256.
Il s'agit d'une protection côté navigateur contre les modifications accidentelles,
pas d'un contrôle d'accès serveur. Les modifications restent enregistrées dans le
navigateur de la personne qui édite (localStorage).
