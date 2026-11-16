# TOMSEN — Stratégie de test et cahier de recette

Projet de formation **Testeur logiciel (OpenClassrooms)** : concevoir toute la démarche de test de **TOMSEN**, une application mobile qui regroupe les comptes de plusieurs banques (création de compte, connexion avec double authentification et biométrie, tableau de bord multi-banques, transactions, relevés, suivi de consommation, conseiller virtuel).

Il s'agit de **test manuel** : de la lecture des spécifications jusqu'aux cas de test prêts à exécuter, organisés par sprint.

## Livrables

| # | Document | Contenu |
|---|---|---|
| 1 | [Revue des exigences](BOUGUELLID_Mohamed_1_RevueExigences_032026.xlsx) | **16 questions** posées sur les spécifications avant de tester (9 critiques, 6 majeures, 1 mineure) : champs mal typés, formats de date ambigus, règles de mot de passe incomplètes, mot de passe envoyé en GET dans un appel API, contradictions sur la double authentification, réglementation des connexions bancaires… |
| 2 | [Stratégie de test](BOUGUELLID_Mohamed_2_Strat%C3%A9gieTest_032026.pdf) | **20 scénarios** couvrant les évolutions du produit et **8 scénarios de non-régression** classés par criticité, méthodes de test adaptées à chaque fonctionnalité |
| 3 | [Cahier de recette](BOUGUELLID_Mohamed_3_CDR_032026.xlsx) | **93 cas de test** (étapes détaillées et résultats attendus), une matrice de traçabilité exigences → cas de test, et les scénarios répartis sur **6 sprints** |
| — | [Abaque](Abaque.xlsx) | Outil d'estimation de la charge de conception et d'exécution selon la complexité des scénarios |

## Démarche

1. **Analyser les exigences** (user stories TOM-2 à TOM-15) et remonter les ambiguïtés et les risques avant d'écrire le moindre test.
2. **Définir la stratégie** : quoi tester, avec quelle priorité, quels parcours protéger contre la régression (parcours de bout en bout, session, intégrité des données multi-banques, sécurité des appels, mode dégradé si une banque ne répond pas).
3. **Rédiger les cas de test** et les relier aux exigences pour vérifier que chacune est couverte.
4. **Planifier** l'exécution sprint par sprint et estimer la charge avec l'abaque.

## Compétences mises en œuvre

Revue des spécifications · analyse de risques · stratégie de test · tests de non-régression · conception de cas de test (valeurs limites, cas d'erreur) · traçabilité des exigences · estimation de charge

## Auteur

**Mohamed Bouguellid** — Testeur QA · [LinkedIn](https://www.linkedin.com/in/mohamed-bouguellid) · [Portfolio](https://lasquale619.github.io/Portfolio-de-testeur-logiciel/)
