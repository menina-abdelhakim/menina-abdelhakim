# Abdelhakim Menina

**Développeur Full Stack & Cloud — Java/Spring Boot · TypeScript/Next.js · Python**
*Master Informatique (Programmation, Sûreté et Sécurité), Université Sorbonne Paris Nord.*

---

## Qui suis-je ?

Je conçois et déploie des applications full-stack sur trois écosystèmes : **Java/Spring Boot**, **TypeScript/Next.js** et **Python**.

En entreprise, j'ai développé une application RH complète (React, NestJS, Prisma, Keycloak, S3) puis migré et sécurisé une infrastructure web de production sur **AWS EC2**. En parallèle, **trois applications personnelles déployées en production**, chacune couverte par des tests automatisés, une intégration continue et une vraie documentation.

---

## Projets en production

### [Facturo](https://github.com/menina-abdelhakim/facturo) — application de facturation · [démo](https://facturo-gilt.vercel.app)
`Java 17` `Spring Boot 3.5` `PostgreSQL` `Flyway` `Angular 20` `Docker`

- Calcul de **TVA multi-taux** conforme à la règle française (arrondi par taux, montants en entiers) et **numérotation séquentielle garantie sans trou** par compteur verrouillé.
- Authentification **JWT** et gestion des rôles, piste d'audit écrite **dans la même transaction** que la modification qu'elle enregistre, tableau de bord des impayés et export PDF conforme.
- **56 tests**, dont des tests d'intégration sur un PostgreSQL réel via **Testcontainers** ; CI GitHub Actions, image Docker multi-étapes, déploiement Neon + Railway + Vercel.

### [Tickets](https://github.com/menina-abdelhakim/tickets-helpdesk) — helpdesk interne · [démo](https://tickets-helpdesk.vercel.app)
`TypeScript` `Next.js 16 (App Router, Server Actions)` `PostgreSQL` `Prisma` `Auth.js`

- Autorisation appliquée **directement dans les requêtes SQL** : une donnée non autorisée n'est jamais chargée, plutôt que filtrée après coup.
- **Recherche full-text PostgreSQL** (colonne `tsvector` générée, index GIN, insensible aux accents), fil de discussion actualisé sans rechargement, piste d'audit.
- **38 tests unitaires (100 % de couverture sur la logique métier)** et **20 tests end-to-end Playwright** ; CI GitHub Actions, déploiement Vercel + Neon.

### [Carbu](https://github.com/menina-abdelhakim/carbu) — comparateur de prix des carburants · [démo](https://carbu-beta.vercel.app)
`Python 3.11` `PostgreSQL + PostGIS` `Next.js` `GitHub Actions`

- Pipeline d'ingestion quotidien des **9 800 stations françaises** (données publiques), **idempotent** : seuls les changements de prix sont enregistrés, un rejeu ne duplique rien.
- Recherche géospatiale par rayon (**PostGIS**, index GiST), carte interactive, géocodage d'adresses et statistiques régionales.
- **29 tests**, dont 9 d'intégration sur PostGIS ; ingestion planifiée et CI GitHub Actions, hébergement entièrement gratuit et pérenne.

---

## Compétences techniques

| **Catégorie** | **Technologies** |
| :--- | :--- |
| **Back-end** | Java 17, Spring Boot 3 (Security, Data JPA, Flyway), Python 3.11, Node.js, NestJS, Express |
| **Front-end** | TypeScript, React, Next.js (App Router, Server Components), Angular 20, HTML/CSS, Tailwind |
| **Bases de données** | PostgreSQL (recherche full-text, PostGIS, migrations Flyway), MySQL, Prisma, JPA/Hibernate, SQL |
| **Tests & qualité** | JUnit, Testcontainers, Playwright, pytest, ESLint, Ruff, intégration continue |
| **Cloud & DevOps** | AWS EC2 et S3 (Apache, DNS, HTTP/HTTPS, Security Groups, durcissement), Docker, GitHub Actions, Vercel, Railway, Neon, Bash |
| **Sécurité** | Keycloak (SSO, OpenID Connect), authentification JWT et gestion des rôles, SSH par clés, durcissement système |
| **Outils** | Git (GitHub/GitLab), WordPress (Elementor), Figma, Jira, Trello, Linux/Windows |

---

## Expériences professionnelles

**Développeur Full Stack & Cloud — France Téléphone**, Fontenay-sous-Bois · *Mai – Sept. 2025*
- Conception et développement d'une application RH complète (**R-WIN**) : front React, API NestJS, persistance Prisma/PostgreSQL, authentification et gestion des rôles via **Keycloak** (OpenID Connect), stockage des documents sur **S3**, déploiement sur **EC2**.
- Migration complète du site depuis IONOS vers **AWS EC2** (données, Apache, DNS, HTTPS, SSH), sans interruption de service signalée.
- Déploiement et sécurisation de serveurs Apache sur EC2 : HTTP/HTTPS, DNS, accès SSH par clés, Security Groups et durcissement système.
- Automatisation des installations et sauvegardes par scripts **Bash**, réduisant les interventions manuelles récurrentes.
- Développement de deux sites vitrines WordPress (Finanssor, WINVEST Capital) ; tracking, analytics et optimisation SEO.

**Développeur WordPress — The ENERGY ACTION Project (ACT4)**, Aubervilliers · *Mai – Août 2023*
- Développement et intégration du site **EnAct** sous WordPress, intégration de contenus et optimisation de l'expérience utilisateur.
- Maintenance et amélioration continue de la plateforme.

**Réalisations en entreprise :** [finanssor.fr](https://finanssor.fr) · [r-win.fr](https://r-win.fr) · [winvest-capital.fr](https://winvest-capital.fr) · [en-act.org](https://en-act.org) · [france-telephone.com](https://france-telephone.com)

---

## Formation

- **Master Informatique — Programmation, Sûreté et Sécurité** (*Mention Bien*) — Université Sorbonne Paris Nord, Institut Galilée · 2023 – 2025
- **Licence Informatique** — Université Sorbonne Paris Nord, Institut Galilée · 2020 – 2023

---

## Me contacter

- **Email** : [meninaabdelhakim@gmail.com](mailto:meninaabdelhakim@gmail.com)
- **Téléphone** : +33 6 98 24 12 57
- **LinkedIn** : [linkedin.com/in/abdelhakim-menina](https://www.linkedin.com/in/abdelhakim-menina/)
- **Localisation** : France

---

*Langues : français (natif), anglais (C1), arabe (natif).*
