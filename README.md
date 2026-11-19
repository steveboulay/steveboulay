# Steve Boulay

Développeur full stack senior : PHP 8, Symfony, API Platform, Angular et TypeScript. Je développe des logiciels métier depuis plus de 20 ans, du recueil du besoin à la formation des utilisateurs.

**Disponible immédiatement** en CDI, en télétravail ou en hybride (Tours, Orléans, Le Mans, Angers, Paris).

## Mon parcours

Chez LOGOS, éditeur d'un logiciel de radiologie utilisé par 6 groupes d'imagerie médicale, j'étais seul sur tous les projets web et nous étions deux sur le moteur de rendez-vous en C. J'y ai notamment développé :

- le portail de prise de rendez-vous en ligne, jusqu'à 20 000 RDV par mois pour un même client, que j'ai refondu seul à partir de 2019 avec une API REST en Symfony / API Platform et un front Angular en TypeScript. Après une recette en équipe, la bascule s'est faite en une nuit, bases de données comprises, sans incident ;
- l'authentification en JWT et l'envoi asynchrone des mails de compte avec Symfony Messenger ;
- un module de pré-accueil qui transmet les données au RIS en HL7 ;
- un outil de planification pour groupes de radiologues, du cahier des charges au déploiement ;
- un macro-langage (DSL) intégré au moteur en C, avec lequel les utilisateurs écrivent eux-mêmes leurs règles ;
- un ordonnanceur de tâches en C, paramétré par un fichier INI, qui gère les flux HL7 et l'envoi des convocations par mail.

## Ce que vous trouverez ici

Le code de ces projets appartient à LOGOS et n'est pas public. Je publie donc, ici et sur GitLab, de petits projets personnels qui montrent ma façon de travailler : une branche et une relecture pour chaque évolution, des tests automatisés et une intégration continue.

- **[SyliusSandboxPaymentPlugin](https://github.com/steveboulay/SyliusSandboxPaymentPlugin)** · PHP 8, Sylius 2, PHPUnit, PHPStan, GitHub Actions
  Plugin Sylius qui simule un prestataire de paiement : moyen de paiement configurable dans l'administration, redirection vers une page de paiement simulée, signature des webhooks en HMAC-SHA256. CI sur trois configurations (Sylius 2.2 et 2.3, MySQL et PostgreSQL). En cours.
- **[planning-gardes](https://gitlab.com/steveboulay/planning-gardes)** (GitLab) · Python, Django REST Framework, PostgreSQL, pytest, GitLab CI
  Vérificateur de planning de gardes pour soignants : il signale les repos insuffisants, les nuits consécutives en trop, les dépassements d'heures hebdomadaires et les jours de repos demandés non respectés. API Django REST Framework sur PostgreSQL, sous Docker Compose, avec une contrainte d'exclusion qui refuse deux postes qui se chevauchent. 76 tests pytest écrits avant le code, CI GitLab avec PostgreSQL. Je l'écris pour apprendre Python et Django ; l'interface React suivra.

Je code avec l'IA (Claude Code). Le fichier [NOTES-IA.md](https://gitlab.com/steveboulay/planning-gardes/-/blob/main/NOTES-IA.md) du projet de planning détaille, test par test, ce qu'elle a proposé, ce que j'ai gardé ou corrigé, et comment je l'ai vérifié.

## Technologies

- **Backend :** PHP 8, Symfony 6.4, API Platform, Symfony Messenger, JWT, C, C++
- **Frontend :** TypeScript, JavaScript, Angular 17, RxJS
- **Données :** PostgreSQL, MySQL, Redis
- **DevOps :** Docker, Docker Compose, Nginx, Apache, Linux
- **Tests et CI :** Git, PHPUnit, PHPStan, pytest, GitHub Actions, GitLab CI
- **En apprentissage :** Python, Django, Sylius 2
- **Santé :** HL7, DICOM

## Me contacter

[Mon profil LinkedIn](https://www.linkedin.com/in/steve-boulay/) · [Mon compte GitLab](https://gitlab.com/steveboulay)
