# KAREEM DEVOPS STARTER LAB

### Projet DevOps — Infrastructure, Cloud et CI/CD

Bienvenue sur **KareemLab**, une organisation GitHub dédiée à la présentation de mon projet réalisé dans le cadre de ma formation DevOps chez **O'clock**.

**KAREEM DEVOPS STARTER LAB** est un environnement de laboratoire conçu pour mettre en pratique le cycle de vie d'une application web, depuis son développement jusqu'à son déploiement sur des infrastructures cloud.

Le projet repose sur une application de blog composée d'un **frontend** et d'un **backend**, avec des environnements distincts de **préproduction** et de **production**.

L'objectif est de mettre en œuvre une chaîne DevOps associant infrastructure, automatisation, intégration continue, tests et livraison applicative.

## Technologies et pratiques mises en œuvre

| Domaine | Technologies et pratiques |
|---|---|
| **Cloud** | Amazon Web Services (AWS), Google Cloud Platform (GCP) |
| **Infrastructure as Code** | Terraform, modules réutilisables, gestion des états distants |
| **Automatisation** | Ansible, configuration des serveurs et déploiement applicatif |
| **Conteneurisation** | Docker, Docker Compose, Docker Hub |
| **CI/CD** | GitHub Actions, workflows conditionnels, livraison inter-dépôts |
| **Tests automatisés** | PHPUnit, Cypress |
| **Qualité et validation** | Terraform Validate, TFLint, Trivy |
| **Réseau et exposition** | DNS, HTTPS, Nginx, Load Balancer, Cloud CDN |
| **Stockage cloud** | Amazon S3, Google Cloud Storage |
| **Gestion des accès** | IAM, authentification fédérée OIDC, Ansible Vault |

## Architecture et organisation du projet

Le projet distingue plusieurs responsabilités techniques afin de représenter les différentes étapes d'une chaîne de livraison DevOps.

### Développement et intégration continue

Les dépôts applicatifs regroupent le code du frontend et du backend, ainsi que leurs mécanismes de construction, de validation et de tests automatisés.

### Infrastructure de préproduction

La préproduction s'appuie notamment sur **AWS, Terraform, Ansible et Docker Compose** pour provisionner les ressources, configurer les serveurs et déployer les composants applicatifs.

Les pipelines CI/CD permettent de valider les changements et d'automatiser les opérations de préproduction.

### Infrastructure de production

La production exploite **Google Cloud et Terraform** pour gérer les ressources nécessaires à l'hébergement et à la livraison de l'application.

Le frontend de production est distribué sous forme de fichiers statiques avec **Cloud Storage, Load Balancer HTTPS et Cloud CDN**.

Les mécanismes de livraison assurent également la transmission et le traitement des informations nécessaires au passage de la préproduction vers la production.

## Organisation des dépôts GitHub

Les dépôts de l'organisation sont structurés selon les composants de l'application, les infrastructures cloud et les environnements de déploiement.

Chaque dépôt dispose de sa propre documentation technique permettant de retrouver :

- Son rôle dans l'architecture globale.
- Les technologies et services utilisés.
- Les workflows CI/CD et leurs déclencheurs.
- Les fichiers d'infrastructure et d'automatisation.
- Les schémas illustrant les parcours de validation et de déploiement.

Cette organisation permet d'explorer progressivement le projet, depuis les dépôts applicatifs jusqu'aux infrastructures de production.

## Visibilité temporaire des dépôts

Dans le cadre de la présentation de mon projet DevOps, les dépôts de cette organisation sont temporairement accessibles au public afin de permettre aux **membres de la communauté de formation O'clock** de découvrir les réalisations techniques, les architectures cloud et les pipelines CI/CD mis en œuvre.

À l'issue de cette période de présentation, les dépôts retrouveront leur visibilité privée.

## Objectif du projet

Ce projet présente les compétences techniques développées et mises en pratique au cours de ma formation DevOps.

Il illustre une démarche de conception, d'automatisation et d'exploitation d'infrastructures cloud, ainsi que l'intégration des outils et méthodes permettant d'accompagner une application tout au long de son cycle de livraison.

**KAREEM DEVOPS STARTER LAB** constitue ainsi un support concret pour découvrir les architectures, les configurations et les pipelines réalisés dans le cadre de ce projet.

