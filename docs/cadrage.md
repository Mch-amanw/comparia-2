# Besoin cadré — Comparateur d’assurances assisté par IA

> Projet: 4dacbc86-a043-4e95-a385-a0bd55e0216d
> Session: cea74658-c8f4-4fb7-94f3-ef6a5768e7e5
> Date: 2026-07-15

## Contexte
Le projet vise à lancer au Maroc une plateforme de comparaison d’assurances destinée aux particuliers. L’objectif est de simplifier la recherche d’assurances auto, santé et habitation grâce à une recommandation personnalisée basée sur l’analyse des besoins, du budget et des critères de couverture.

Les utilisateurs recherchent aujourd’hui leurs assurances principalement via des comparateurs en ligne, les sites des assureurs ou des courtiers. Les difficultés identifiées sont la complexité des offres, le manque de transparence sur les garanties et exclusions, ainsi que le temps nécessaire pour effectuer une comparaison fiable.

La première version du produit se concentre sur la comparaison et la recommandation d’offres ainsi que sur la transmission de demandes de devis. La souscription en ligne est explicitement exclue du périmètre initial.

## Problématique
Les particuliers ont des difficultés à identifier rapidement une assurance adaptée à leur situation en raison de la diversité des offres, du manque de lisibilité des garanties et des différences de franchises, exclusions, plafonds et délais de carence.

Le besoin consiste à fournir un outil capable d’analyser plusieurs offres d’assurance et d’expliquer de manière compréhensible pourquoi une offre est recommandée selon le profil utilisateur.

Le projet doit également maintenir un positionnement clair de comparateur et d’outil d’aide à la décision sans se substituer au conseil réglementé d’un professionnel de l’assurance.

## Objectifs métier
- Réduire significativement le temps nécessaire pour comparer des assurances.
- Aider les utilisateurs à identifier une offre adaptée à leurs besoins et à leur budget.
- Améliorer la transparence des comparaisons entre garanties, exclusions et niveaux de couverture.
- Générer des demandes de devis qualifiées pour les assureurs et courtiers partenaires.
- Fournir des recommandations compréhensibles et justifiées.

## Critères de succès
- Réduction du temps de recherche d’assurance de 50 % dans la première année.
- Taux de demande de devis supérieur à 20 % dans la première année.
- Satisfaction utilisateur supérieure à 90 % dans la première année.

## Périmètre
### Inclus
- Comparaison d’assurances auto, santé et habitation.
- Recommandation personnalisée assistée par IA.
- Collecte d’informations générales utilisateur selon le type d’assurance.
- Comparaison des garanties, exclusions, plafonds, franchises, délais de carence et conditions particulières importantes.
- Explication des recommandations proposées.
- Transmission de demandes de devis aux assureurs et courtiers partenaires.
- Affichage d’offres partenaires et, lorsque disponibles, d’offres non partenaires à titre informatif.
- Gestion des cas d’offres incomplètes avec avertissement et comparaison partielle.
- Proposition d’offres proches et orientation vers un conseiller lorsqu’aucune offre ne correspond exactement au besoin.

### Exclus
- Souscription en ligne dans la première version.
- Gestion des contrats ou des sinistres.
- Produits d’assurance autres qu’auto, santé et habitation.
- Utilisateurs professionnels ou entreprises.
- Remplacement du conseil d’un professionnel de l’assurance.
- Expansion internationale dans la phase initiale.
- Collecte de données médicales détaillées dans la plateforme.

## Parties prenantes
- Fondateur de la plateforme: sponsor et décideur métier.
- Équipe produit: cadrage fonctionnel et arbitrages produit.
- Utilisateurs particuliers: bénéficiaires de la comparaison et des recommandations.
- Assureurs partenaires: fournisseurs d’offres et destinataires des demandes de devis.
- Courtiers partenaires: fournisseurs d’offres et destinataires des demandes de devis.

## Processus
### Processus actuel
Les particuliers consultent plusieurs comparateurs, sites d’assureurs ou courtiers pour comprendre les offres disponibles. Ils doivent analyser eux-mêmes les garanties, exclusions et tarifs, ce qui rend la comparaison longue et difficile.

### Processus cible
L’utilisateur renseigne ses besoins, son budget et les informations nécessaires selon le type d’assurance.

La plateforme analyse les offres disponibles provenant des partenaires ou d’autres sources disponibles.

Les offres sont comparées selon plusieurs critères: prix, garanties, exclusions, franchises, plafonds, délais de carence et qualité de service.

La plateforme affiche les offres les plus adaptées et explique les raisons des recommandations.

L’utilisateur peut demander un devis depuis la plateforme.

Si aucune offre ne correspond exactement au profil, les offres les plus proches sont proposées avec possibilité de contacter un conseiller.

## Exigences fonctionnelles
- Collecter les informations nécessaires à la comparaison selon le type d’assurance.
- Comparer les offres selon des critères métier multiples.
- Générer des recommandations personnalisées.
- Expliquer les critères ayant conduit à la recommandation.
- Afficher les offres incomplètes avec avertissement.
- Permettre une comparaison partielle lorsque certaines données sont manquantes.
- Permettre la transmission de demandes de devis.
- Intégrer les données d’offres via partenariats ou APIs lorsque disponibles.
- Afficher des offres non partenaires à titre informatif lorsque disponibles.
- Orienter vers un accompagnement humain dans les cas sans correspondance satisfaisante.

## Contraintes
- Lancement initial limité au Maroc.
- Budget maîtrisé pour la première phase.
- Priorité donnée à la qualité et à la pertinence des recommandations.
- Respect des contraintes réglementaires liées à l’assurance et à la protection des données.
- Limitation des données collectées en santé à des critères non sensibles.

## Dépendances
- Disponibilité des partenariats assureurs et courtiers.
- Disponibilité des APIs partenaires.
- Qualité et fraîcheur des données d’offres fournies.

## Risques
- Risque réglementaire si la recommandation est assimilée à du conseil sans traçabilité adaptée.
- Risque de recommandations inadaptées si les critères de comparaison sont incomplets.
- Risque lié à la qualité ou à l’exhaustivité des données partenaires.
- Risque de mauvaise compréhension des recommandations si les explications sont jugées opaques.
- Risque de conformité lié aux données personnelles et sensibles.

## Planning macro
Lancement initial au Maroc dans une première phase avec focalisation sur la qualité des recommandations avant extension éventuelle à d’autres marchés.

## Décisions prises
- La première version ne permettra pas la souscription en ligne.
- Les offres incomplètes seront affichées avec avertissement.
- Les demandes de devis seront transmises aux partenaires depuis la plateforme.
- Les données médicales détaillées ne seront pas collectées par la plateforme.
- Les offres partenaires seront prioritaires mais des offres non partenaires pourront être affichées à titre informatif.
- Lorsque aucune offre ne correspond exactement au besoin, les offres les plus proches seront proposées avec possibilité de contacter un conseiller.

## Alternatives écartées
- Collecte de données médicales détaillées directement dans la plateforme, écartée pour limiter les risques réglementaires et de confidentialité.
- Limitation stricte aux seules offres partenaires, écartée afin d’améliorer la perception de neutralité et la couverture de comparaison.