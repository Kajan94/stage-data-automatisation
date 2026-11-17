# Stage Data et automatisation — Centreville Télévision

**Kajan Arulnathan · BUT Informatique · 20 avril au 12 juin 2026**

[Voir mon portfolio](https://kajan94.github.io/Portefolio/#experience)

## Assistant IA de recherche documentaire

J’ai développé deux workflows n8n. Le premier prépare et vectorise les procédures Notion pour les indexer dans Qdrant. Le second recherche les passages pertinents et les transmet au modèle exécuté localement avec Ollama. Une interface web permet aux techniciens de poser une question et de démarrer une nouvelle discussion.

Mon tuteur a validé le workflow. La précision des réponses et le temps de traitement dépendaient du modèle et du matériel disponibles.

![Workflow n8n reliant un agent IA à Ollama et à la base vectorielle Qdrant.](https://github.com/user-attachments/assets/d6223b32-aeec-4a7e-b53b-8eb44fabeb3b)

![Écran d’accueil de l’assistant technique avec une zone de saisie des questions.](https://github.com/user-attachments/assets/c3759571-38e5-4c4e-bee5-6b413a17945c)

## Tableau de bord d’occupation

J’ai développé une extraction Python et une interface Flask pour analyser les réservations. Le tableau de bord affiche le taux d’occupation par catégorie de salle, la répartition des logiciels utilisés et un inventaire filtrable. Les résultats d’une semaine ont été comparés au planning d’origine avec mon tuteur.

![Tableau de bord d’occupation avec filtres de dates, indicateurs et répartition des logiciels, sur données fictives.](https://github.com/user-attachments/assets/8068cb09-c72c-403f-87eb-58b3be9bf2a7)

![Inventaire de salles fictives avec leur catégorie et leur identifiant de démonstration.](https://github.com/user-attachments/assets/31370ec9-5c57-4110-af7a-aff045128d2b)

## Automatisation des accès

J’ai conçu un flux n8n qui récupère les interventions prévues, vérifie les comptes existants et lance une création lorsqu’elle est nécessaire.

Deux pistes de poursuite sont l’historisation des indicateurs et l’évaluation d’un modèle local plus performant.
