# Atelier Docker - Parcours d'apprentissage

Ce dépôt regroupe l'ensemble des travaux et exercices réalisés lors de mon atelier de formation sur Docker. Le parcours est divisé en 9 modules progressifs, allant des bases de la conteneurisation jusqu'aux architectures microservices et au déploiement continu.

## Contenu de l'atelier

Voici la liste des activités couvertes dans ce dépôt, correspondant aux différents modules de la formation :

*   **1 - Découverte de Docker :** Expérimenter la récupération d'images et le lancement de conteneurs.
*   **2 - Le Dockerfile :** Apprentissage de la création d'images personnalisées.
*   **3 - Dockerfile et sécurité :** Introduction aux bonnes pratiques pour sécuriser les images Docker.
*   **4 - Docker Builds multi-étapes et gestion des secrets :** Optimisation du poids des images et protection des données sensibles lors du build.
*   **5 - Docker - Les volumes :** Persistance des données et partage de fichiers entre l'hôte et les conteneurs.
*   **6 - Docker - Les réseaux :** Communication entre les conteneurs et configuration réseau.
*   **7 - Docker - Compose :** Orchestration locale de plusieurs conteneurs et gestion simplifiée des applications multi-services.
*   **8 - Docker - Analyse de vulnérabilité avec Trivy :** Scan de sécurité des images pour identifier et corriger les failles.
*   **9 - Docker - Microservices et déploiement continu :** Mise en pratique avancée sur une architecture microservices intégrée dans un pipeline de déploiement.

## Structure du dépôt

Chaque dossier de ce dépôt correspond à un module spécifique listé ci-dessus. On y trouvera :
*   Les fichiers `Dockerfile` et `docker-compose.yml` pertinents.
*   Le code source des applications de démonstration.
*   Un fichier `README.md` interne avec les commandes spécifiques pour lancer chaque exercice.

## Prérequis

Pour exécuter les exercices de cet atelier, on aura besoin des éléments suivants installés sur la machine :
*   Docker Engine
*   Docker Compose
*   Trivy (nécessaire pour le module 8)
