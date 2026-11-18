# 🎮 SansSpoil — du recueil des besoins au code

**BTS SIO SLAM · 2e année · Bloc 2 — Conception et développement d'applications**

GTA 6 est sorti le jeudi 19 novembre 2026. Tout le monde y joue, chacun à son rythme… et les astuces partagées gâchent la suite de l'histoire à ceux qui sont moins avancés.

Le **Forez Gaming Club**, une association (fictive) de joueurs stéphanois, vous commande **SansSpoil** : un carnet de progression entre amis, avec une règle d'or.

> **Un membre ne doit jamais pouvoir lire ce qui se trouve plus loin que là où il en est.**

Vous allez recueillir le besoin, concevoir le modèle de données **sur papier**, puis le réaliser deux fois : en **Laravel**, puis en **Rust**, sur la même base de données.

## 🗺️ Le parcours

| Séance | Phase | Ce que vous faites | Ce que vous rendez |
|---|---|---|---|
| 1 | 📝 Papier — recueil | Vous interrogez la présidente du club, vous repérez ses contradictions | Questions, règles de gestion, dictionnaire des données |
| 2 | 📝 Papier — MCD | Réflexion seul, tri des cartes, MCD Merise 2 sur A3, confrontation entre groupes | MCD sur A3, règles que le MCD ne sait pas dire |
| 3 | 🐘 Laravel | Du modèle relationnel aux migrations, données de test neutres | Base créée |
| 4 | 🐘 Laravel | Modèles, relations, règle anti-spoiler testée | Test au vert |
| 5 | 🐘 Laravel | API : astuces visibles, votes, classement des défis | 3 routes, tests au vert |
| 6 | 🦀 Rust | Les mêmes 3 routes avec Axum et SQLx | API Rust |
| 7 | 🦀 Rust | Mesurer et comparer les deux versions, soutenir vos choix | Grille de comparaison, oral de 5 min |

Le fil conducteur : **le modèle survit au langage**. Le MCD dessiné à la main en séance 2 sert tel quel aux deux applications.

## 📁 Le dépôt

| Dossier | Contenu | Disponible |
|---|---|---|
| [seance-01-recueil](seance-01-recueil/) | Le message du club, les consignes de l'entretien | ✅ |
| [seance-02-mcd](seance-02-mcd/) | Le déroulé du temps de réflexion sur table | ✅ |
| [imprimer](imprimer/) | Les documents papier de la séance 2 (PDF et sources) | ✅ en partie, le reste après la séance 1 |
| [laravel](laravel/) | Le squelette Laravel (séances 3 à 5) | après la séance 2 |
| [rust](rust/) | Le squelette Rust (séances 6 et 7) | après la séance 5 |

## 🤫 Règle de la classe : zéro spoiler

On parle des **besoins des joueurs**, jamais de l'histoire du jeu. Aucune image ni vidéo du jeu en classe ; les chapitres, zones et objets du projet portent des noms neutres (« Chapitre 3 », « Zone Nord »). Le jeu est classé PEGI 18.

Le Forez Gaming Club, sa présidente et SansSpoil sont fictifs. Ce projet n'a aucun lien avec l'éditeur du jeu.
