# GreenTrack — Cadrage d’un produit digital

## Présentation du projet

GreenTrack est un projet de cadrage d’une application de déclaration et de suivi des incidents terrain pour Ecolistics, une PME spécialisée dans la logistique verte.

Ce projet a été réalisé dans le cadre de ma formation **Chef de projet No-Code et IA** chez OpenClassrooms.

## Problématique

Ecolistics gère environ 300 à 350 incidents par mois.

Les informations sont réparties entre un fichier Excel, OneDrive, des messages et des notes papier. Cette organisation entraîne plusieurs difficultés :

- double saisie des informations ;
- risques d’erreur ou d’oubli ;
- photos et données dispersées ;
- recherche des incidents difficile ;
- problèmes lors des modifications simultanées du fichier Excel.

## Objectifs

Le projet GreenTrack vise à :

- réduire de 50 % le temps de suivi administratif ;
- réduire de 80 % les erreurs de saisie ;
- faciliter la recherche des incidents ;
- permettre une réponse rapide aux demandes des clients ;
- centraliser les incidents, les photos et leur suivi.

## Fonctionnalités principales de la V1

- Formulaire mobile de déclaration
- Contrôles de saisie et listes de choix
- Ajout de photos
- Localisation et horodatage automatiques
- Gestion des droits selon le rôle
- Authentification sécurisée
- Recherche filtrée
- Consultation du statut des incidents
- Export des données vers Excel
- Suppression des données à la fin de leur durée de conservation

## Méthodologie

Le projet a été réalisé en plusieurs étapes :

1. Analyse des entretiens avec les parties prenantes
2. Cartographie des données existantes
3. Création d’un Lean UX Canvas
4. Idéation personnelle enrichie par l’intelligence artificielle
5. Priorisation de 12 idées avec la méthode RICE
6. Définition du périmètre de la V1
7. Définition des objectifs SMART et des KPI
8. Comparaison de cinq stacks techniques no-code
9. Identification des risques et des mesures de mitigation

## Priorisation RICE

Les fonctionnalités ont été comparées selon quatre critères :

- **Reach** : nombre d’utilisateurs concernés ;
- **Impact** : amélioration attendue ;
- **Confidence** : solidité des informations disponibles ;
- **Effort** : charge estimée pour réaliser la fonctionnalité.

Les cinq idées les mieux classées sont :

1. Contrôles de saisie et listes de choix — **15,00**
2. Formulaire mobile de déclaration — **8,33**
3. Gestion des droits par rôle — **8,33**
4. Ajout de photos au signalement — **7,50**
5. Localisation et horodatage automatiques — **7,50**

## Solution no-code recommandée

Cinq stacks techniques ont été étudiées :

- Bubble
- Airtable + Softr
- Glide
- FlutterFlow + Supabase
- Power Apps + SharePoint + Power Automate

La solution recommandée est **Power Apps + SharePoint + Power Automate**.

Cette solution a été retenue pour les raisons suivantes :

- intégration avec l’environnement Microsoft 365 existant ;
- utilisation des comptes professionnels ;
- création d’une application mobile ;
- centralisation des incidents dans SharePoint ;
- gestion des rôles et des permissions ;
- automatisation de certaines tâches avec Power Automate ;
- import facilité des données Excel existantes.

Cette recommandation doit être validée par la DSI et testée pendant un pilote.

## Livrables

- [Consulter le document de cadrage](docs/document-cadrage-greentrack.pdf)
- [Consulter la présentation de soutenance](docs/presentation-soutenance.pdf)

## Liens du projet

- [Document de cadrage sur Notion](https://hushed-wolfberry-30a.notion.site/Document-de-cadrage-Ecolistics-ac229b773ed08206a8970102b36beeed?source=copy_link)
- [Cartographie des données sur Miro](https://miro.com/app/board/uXjVHn4l1VQ=/?share_link_id=424277008460)
- [Lean UX Canvas sur Miro](https://miro.com/app/board/uXjVHm2W9l8=/?share_link_id=369966793635)
- [Matrice RICE sur Airtable](https://airtable.com/appd6XLuBRQieCm1w/shr8eWo0CJBm9zeOK)

## Outils utilisés

- Notion
- Miro
- Airtable
- Intelligence artificielle
- Recherche documentaire
- PowerPoint / outil de présentation

## Compétences mobilisées

- Analyse des besoins utilisateurs
- Cartographie des données
- Lean UX Canvas
- Priorisation RICE
- Définition d’objectifs SMART et de KPI
- Délimitation du périmètre d’une V1
- Comparaison de solutions no-code
- Analyse et gestion des risques

## Statut du projet

Projet de cadrage terminé et validé.

## Auteur

**Maan Al Ali**  
Formation Chef de projet No-Code et IA — OpenClassrooms
