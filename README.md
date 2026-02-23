# Analyse de risques d’une architecture fintech SaaS (EBIOS RM, ISO 27001)

## Présentation du projet
Ce projet effectue une analyse de risques de type EBIOS Risk Manager appliquée à une architecture fintech de type SaaS hébergé sur un cloud. L’objectif est de comprendre et analyser les types de risques liés aux infrastructures ou les données de la plateforme et de planifier une contre-mesure face à ces risques afin de réduire la probabilité que ces risques se réalisent dans la plateforme.

L’analyse s’inspire de la méthodologie EBIOS Risk Manager et du Gouvernance, Rsique, et Conformité (GRC). Le projet vise à comprendre comment appliquer ce type de méthodologie sur un environnement moderne, tel que le cloud et un assistant IA de type LLM.

Cette plateforme héberge quelques fonctionnalités, telles que la gestion de compte clients, le traitement des transactions financières, ainsi que le stockage des documents.

---

## Architecture étudiée
- Interface web (frontend)
- API (backend)
- Base de données relationnelle
- Stockage objet pour les documents
- Gestion des identités et des accès (IAM)
- Journalisation, alerte, et traçabilité
- Assistant IA (LLM) externe
- Base de connaissances interne pour l'IA

L'architecture peut être consulté ci-dessous.

![Architecture](Architecture_CloudLLM_EBIOSRM.pdf)

---

## Démarche d’analyse de risques
- Identification des valeurs métier
- Identification des biens supports
- Identification des événements redoutés
- Construction de scénarios de risque
- Evaluation des risques (gravité et vraisemblance)
- Proposition de mesures de sécurité

Les mesures proposées se conforment aux bonne pratiques de ISO 27001.

---

## Exemples de scénarios de risque étudiés
- Mauvaise configuration d’un stockage cloud
- Compromission d’un compte IAM
- Transmission involontaire de données clients vers un LLM externe
- Génération de réponses dangereux par l’assistant IA
- Tentative de prompt injection via la base de connaissances

---

## Travaux en cours
Le rapport complet d’analyse de risques est en cours de rédaction et sera ajouté prochainement au dépôt.