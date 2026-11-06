# Wooclap

<span class="badge badge-ue">Entreprise UE</span> <span class="badge badge-gratuit">Licence de l'école</span>

<p class="maj">Dernière vérification : à compléter</p>

**Wooclap** est une plateforme de questions interactives : pendant votre cours, les étudiants répondent depuis leur téléphone ou leur ordinateur, et les résultats s'affichent en direct. L'école dispose d'une licence, et vous vous connectez avec votre compte de l'école. Depuis peu, cette licence donne aussi accès aux **agents IA de Wooclap**, des assistants intégrés qui vous aident à créer des questions, à rendre un schéma interactif ou à analyser les réponses de vos étudiants.

[Ouvrir Wooclap](https://www.wooclap.com){ .md-button .md-button--primary }

!!! info "Fiche en cours de rédaction"
    Le tutoriel complet sera bientôt disponible.

## À quoi ça sert dans le supérieur

- **Créer en quelques secondes des questions** (QCM, questions ouvertes, textes à trous, appariements…) à partir de votre support de cours.
- **Rendre un schéma interactif** : les étudiants placent eux-mêmes les légendes d'un schéma technique.
- **Vérifier la compréhension en direct** et adapter la suite du cours aux réponses.
- **Faire émerger et classer les idées** d'un amphithéâtre lors d'un remue-méninges.
- **Faire une synthèse** des réponses ouvertes des étudiants à la fin d'une séance.

## Accès et licence

Wooclap est accessible **avec votre compte de l'école**, grâce à la licence souscrite par l'établissement : vous n'avez rien à payer. Les **agents IA** sont réservés aux établissements qui ont souscrit l'option IA (ou qui la testent) et aux abonnements Pro. Wooclap s'engage à ce qu'**aucun modèle d'IA ne soit entraîné avec vos données**, respecte le RGPD et héberge les données en Europe.

## Les agents IA de Wooclap

| Agent | À quoi il sert |
|---|---|
| **Générateur de questions** | Créer des questions en quelques secondes à partir d'un document (PDF, PowerPoint), d'un lien, d'un texte collé ou d'un fichier audio ou vidéo |
| **Image Labeler** | Transformer un schéma ou une carte en activité interactive, en plaçant automatiquement les repères et en masquant les légendes |
| **Answer Organizer** | Classer automatiquement les réponses des participants par thèmes |
| **Idea Generator** | Proposer des réponses à une question de remue-méninges |
| **Summarizer** | Structurer et résumer les contributions des participants |

<!-- Intitulés français des agents à vérifier sur les captures -->

## Cas d'usage

=== "Questions à partir d'un cours"

    **Exemple** : un QCM de fin de séance sur un chapitre de résistance des matériaux.

    Importez votre support de cours (PDF ou PowerPoint) dans le **Générateur de questions**, puis précisez :

    ```
    Génère 6 questions à choix multiples sur ce chapitre,
    pour des élèves ingénieurs de 1re année : 3 questions de
    compréhension des notions (contrainte, déformation, module
    d'Young) et 3 questions d'application numérique simples.
    Une seule bonne réponse par question, avec des
    distracteurs fondés sur les erreurs fréquentes.
    ```

=== "Schéma à légender"

    **Exemple** : le schéma d'une pompe centrifuge en mécanique des fluides.

    Importez le schéma dans l'agent qui place les repères : il masque les légendes, et les étudiants doivent replacer chaque élément (roue, volute, aspiration, refoulement) pendant le cours.

=== "Analyser les réponses"

    **Exemple** : une question ouverte en début de cours de développement durable.

    Posez la question « Citez un exemple de gaspillage d'énergie que vous avez observé sur le campus », puis utilisez l'agent qui **classe les réponses par thèmes** : vous voyez immédiatement les sujets qui reviennent le plus, et vous pouvez en partir pour la suite du cours.

=== "Synthèse de fin de séance"

    **Exemple** : la fin d'un TD de gestion de projet.

    Posez la question « Qu'est-ce qui reste flou pour vous après cette séance ? », puis demandez à l'agent de **synthèse** de résumer les réponses : vous savez quoi reprendre au début de la séance suivante.

## Pas à pas

:material-magnify-plus-outline: Cliquez sur une capture pour l'agrandir.
{ .astuce-zoom }

<div class="etape" markdown>

### <span class="etape-num">1</span> Se connecter avec le compte de l'école

1. Ouvrez [wooclap.com](https://www.wooclap.com/fr/), puis cliquez sur **Se connecter**, en haut à droite.

    ![Site Wooclap : bouton Se connecter](wooclap-01-site.png)

2. Sur l'écran **Authentification unique (SSO)**, saisissez votre adresse e-mail de l'école dans le champ **Email**, puis cliquez sur **Continuer avec l'authentification unique**.
3. Connectez-vous avec vos identifiants habituels de l'école.

N'utilisez pas **Se connecter sans SSO** : seul le compte de l'école donne accès à la licence et aux agents IA.

![Écran Authentification unique (SSO) : champ Email et bouton Continuer avec l'authentification unique](wooclap-01-sso.png)

</div>

<div class="etape" markdown>

### <span class="etape-num">2</span> Découvrir le tableau de bord

La page d'accueil propose en haut des **modèles** d'événements, puis la liste **Mes événements**. Un bandeau indique que **les agents IA sont disponibles sur votre compte**. Pour préparer une séance, cliquez sur **Créer un événement**.

![Tableau de bord : bandeau des agents IA et bouton Créer un événement](wooclap-02-tableau-de-bord.png)

</div>

<!--
Étapes restant à rédiger (captures à recevoir) :
 3. Créer un événement
 4. Générer des questions avec l'IA à partir d'un document
 5. Relire et modifier les questions générées
 6. Rendre un schéma interactif (Légender une image)
 7. Lancer l'événement : vue participant (capture wooclap-07-participant.png prête)
 8. Classer et résumer les réponses avec l'IA
 9. Consulter les résultats après le cours
-->

## Ressources officielles

- [Centre d'aide de Wooclap](https://docs.wooclap.com/fr/) : prise en main, types de questions, intégrations.
- [Les agents IA de Wooclap](https://docs.wooclap.com/fr/articles/11872838-agents-ia-de-wooclap) : présentation des agents, accès, confidentialité.
- [Générateur de questions](https://docs.wooclap.com/fr/articles/8774298-generateur-de-questions) : créer des questions à partir d'un document.

## Points de vigilance

!!! warning "Données"
    Wooclap est une entreprise belge : les données sont hébergées en Europe, et Wooclap s'engage à ne pas entraîner de modèles d'IA avec vos contenus. Évitez malgré tout de déposer des documents confidentiels, et ne demandez jamais aux étudiants de répondre avec des informations personnelles.

!!! tip "Fiabilité"
    Relisez chaque question générée par l'IA : la bonne réponse, les distracteurs et la formulation. Une question ambiguë en direct fait perdre du temps et peut induire les étudiants en erreur.

!!! info "Licence de l'école"
    Connectez-vous toujours avec votre compte de l'école, et non avec un compte personnel : c'est lui qui donne accès à la licence et aux agents IA.

!!! note "L'IA prépare, vous animez"
    Les agents IA accélèrent la préparation et l'analyse, mais le choix des questions, le moment où les poser et l'exploitation des réponses restent votre travail pédagogique.
