# Cahier des charges - Déploiement d'un cluster Kubernetes avec Nextcloud et outils de supervision

## Objectif

L'objectif de ce projet est de déployer un cluster Kubernetes avec l'application Nextcloud et sa base de données, en utilisant les outils de supervision Grafana, Prometheus et New Relic. Le déploiement sera administré à l'aide d'un référentiel GitHub et d'une pipeline Azure DevOps. De plus, le code sera surveillé en continu dans la pipeline à l'aide des outils DevSecOps OWASP ZAP, Grype et SonarCloud.


## Fonctionnalités requises

- Déploiement d'un cluster Kubernetes sur une plateforme de cloud (Azure Kubernetes Service - AKS)
- Déploiement de l'application Nextcloud sur le cluster Kubernetes
- Configuration et déploiement d'une base de données compatible avec Nextcloud (par exemple MySQL ou PostgreSQL)
- Configuration et déploiement de Grafana pour la supervision des métriques du cluster Kubernetes, de Nextcloud et de la base de données
- Configuration et déploiement de Prometheus pour la collecte des métriques du cluster Kubernetes, de Nextcloud et de la base de données
- Configuration et déploiement de New Relic pour la surveillance des performances de l'application Nextcloud
- Utilisation d'un référentiel GitHub pour gérer les fichiers de configuration et les scripts de déploiement
- Mise en place d'une pipeline Azure DevOps pour automatiser le déploiement et la gestion du cluster et des outils de supervision
- Intégration des outils DevSecOps OWASP ZAP et SonarCloud pour la surveillance du code dans la pipeline

## Contraintes techniques

- Utilisation d'une plateforme de cloud pour le déploiement du cluster Kubernetes (par exemple Azure AKS, AWS EKS ou Google GKE)
- Utilisation de Helm pour la gestion des packages et le déploiement des ressources Kubernetes
- Utilisation de Docker pour créer les images conteneurisées de l'application Nextcloud et de la base de données
- Utilisation de Terraform pour provisionner les ressources nécessaires
- Utilisation de Git pour versionner et gérer les fichiers de configuration et les scripts de déploiement
- Utilisation des outils DevSecOps OWASP ZAP, Grype et SonarCloud pour la surveillance du code dans la pipeline

## Livrables

- Un repository Github contenant les fichiers de configuration, les scripts de déploiement et les ressources nécessaires à l'infrastructure
- Un pipeline Azure DevOps configuré pour automatiser le déploiement et la gestion du cluster Kubernetes et des outils de supervision
- Un cluster Kubernetes fonctionnel avec l'application Nextcloud, la base de données et les outils de supervision Grafana, Prometheus et New Relic déployés et opérationnels
- Surveillance continue du code dans la pipeline à l'aide des outils DevSecOps OWASP ZAP, Grype et SonarCloud