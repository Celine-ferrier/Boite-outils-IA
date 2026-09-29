# Mistral Vibe (ex-Le Chat)

<span class="badge badge-ue">Entreprise UE</span> <span class="badge badge-gratuit">Gratuit, compte conseillé</span>

<p class="maj">Dernière vérification : septembre 2026</p>

**Mistral Vibe** est l'assistant conversationnel de l'entreprise française Mistral AI. Il s'appelait **Le Chat** jusqu'en mai 2026 : l'adresse, le compte et l'historique restent les mêmes. Vous lui décrivez ce que vous voulez obtenir en langage courant, et il rédige, reformule, analyse vos documents ou cherche sur le web. Pour des tâches plus complexes, il découpe le travail en étapes et vous montre sa progression.

[Ouvrir Mistral Vibe](https://chat.mistral.ai){ .md-button .md-button--primary }

## À quoi ça sert dans le supérieur

- **Préparer une séance** : plan, activités, timing, supports.
- **Créer des exercices** corrigés et adaptés à différents niveaux.
- **Construire des outils d'évaluation** : grilles critériées, questions d'examen, barèmes.
- **Exploiter vos propres documents** : résumer un polycopié, interroger un corpus de cours.
- **Rédiger et reformuler** : consignes, courriels, fiches de présentation de cours, traductions.

## Version gratuite

Un compte gratuit donne accès aux modèles de Mistral sur le web et sur mobile, à la recherche web, à l'analyse de fichiers, à la génération d'images, aux projets et aux bibliothèques de documents. La version gratuite limite le **nombre de messages par jour**, le nombre d'images générées et les recherches approfondies (**5 par mois**). Certaines fonctions avancées, comme l'exécution de code, sont réservées à l'abonnement Pro.

## Cas d'usage

=== "Préparer une séance"

    **Exemple** : une séance de travaux dirigés sur l'amélioration continue (lean) en génie industriel.

    ```
    Je suis enseignant dans une école d'ingénieurs. Prépare une
    séance de TD de 2 heures sur la méthode SMED pour des élèves
    de 2e année. Propose : les objectifs d'apprentissage, un
    déroulé minuté, une étude de cas réaliste en atelier de
    production, et 3 questions pour vérifier la compréhension
    en fin de séance.
    ```

    Poursuivez la conversation pour ajuster : « rends l'étude de cas plus courte », « ajoute un travail en binôme »…

=== "Créer des exercices"

    **Exemple** : des exercices de thermodynamique de difficulté croissante.

    ```
    Rédige 3 exercices sur le premier principe de la
    thermodynamique appliqué aux systèmes ouverts, de difficulté
    croissante, pour des élèves ingénieurs de 1re année. Pour
    chacun, donne l'énoncé, les données numériques, la correction
    détaillée et les erreurs fréquentes des étudiants.
    ```

    !!! warning "À vérifier"
        Refaites toujours les calculs des corrigés : les erreurs numériques sont fréquentes.

=== "Grille d'évaluation"

    **Exemple** : l'évaluation d'un projet d'équipe en génie de l'environnement.

    ```
    Construis une grille d'évaluation critériée pour un projet
    d'équipe d'élèves ingénieurs : diagnostic environnemental
    d'un site industriel. 5 critères maximum, 4 niveaux de
    maîtrise décrits par des comportements observables, et une
    pondération sur 20. Présente-la sous forme de tableau.
    ```

=== "Exploiter vos documents"

    **Exemple** : une foire aux questions à partir de votre polycopié de mécanique des fluides.

    Joignez votre polycopié (bouton **+**), puis demandez :

    ```
    À partir de ce polycopié, rédige une FAQ de 15 questions que
    se posent souvent les étudiants, avec une réponse courte et
    la référence de la section du polycopié concernée.
    ```

    Pour réutiliser vos supports dans plusieurs conversations, rangez-les plutôt dans une **Bibliothèque** (voir le pas-à-pas).

=== "Actualiser un cours"

    **Exemple** : intégrer les évolutions récentes de la réglementation dans un cours sur les risques industriels.

    ```
    Recherche sur le web les évolutions de la réglementation
    française sur les installations classées (ICPE) depuis 2024.
    Présente-les dans un tableau : texte, date, changement
    principal, source.
    ```

    Pour une synthèse plus complète, choisissez le mode **Recherche** dans le menu **Rapide**. Vibe cite ses sources : ouvrez-les pour vérifier chaque information.

## Pas à pas

:material-magnify-plus-outline: Cliquez sur une capture pour l'agrandir.
{ .astuce-zoom }


<div class="etape" markdown>

### <span class="etape-num">1</span> Choisir le bon outil

Sur le site [mistral.ai](https://mistral.ai/fr/), le bouton **Se connecter** en haut à droite propose trois outils. Pour enseigner, c'est **Vibe** qu'il vous faut.

| Outil | À quoi il sert | Pour qui |
|---|---|---|
| **Vibe** | L'assistant conversationnel : rédiger, analyser des documents, chercher sur le web | Tous les enseignants : **c'est l'outil de cette fiche** |
| **Vibe for Code** | Un assistant de programmation qui écrit et modifie du code, dans le terminal, un éditeur de code ou sur GitHub | Enseignants en informatique, projets de développement |
| **Studio** | La plateforme des développeurs : clés d'accès aux modèles (API), tests et paramétrage | Création d'applications, par exemple pour intégrer un modèle Mistral dans un autre logiciel |

Cliquez sur **Se connecter**, puis sur **Vibe**. Vous pouvez aussi aller directement sur [chat.mistral.ai](https://chat.mistral.ai).

![Menu Se connecter du site de Mistral](images/mistral-01-acces.png)

</div>

<div class="etape" markdown>

### <span class="etape-num">2</span> Créer un compte

Sur la page de Vibe, cliquez sur **S'inscrire** et créez votre compte avec votre **adresse e-mail de l'école** (@mines-ales.fr). Vous séparez ainsi votre usage professionnel de vos comptes personnels. Le compte est gratuit et conserve l'historique de vos conversations.

![Page de connexion](images/mistral-02-connexion.png)

</div>

<div class="etape" markdown>

### <span class="etape-num">3</span> Découvrir l'interface

L'écran se compose de deux parties.

- **À gauche, la barre latérale.** En haut, vérifiez que l'onglet **Chat** est sélectionné (l'onglet **Code** correspond à Vibe for Code). En dessous : **Nouveau chat** pour démarrer une conversation, **Agents** pour vos assistants personnalisés, **Contexte** pour vos souvenirs, connecteurs, bibliothèques et instructions, puis la rubrique **Projets** et l'historique de vos conversations. L'icône de **loupe** en haut permet de rechercher dans vos anciennes conversations, et l'icône de **panneau** masque ou affiche la barre.
- **Au centre, la zone de saisie**, sous le message de bienvenue. Elle contient le bouton **+** pour ajouter des fichiers, des sources et des outils, un indicateur du nombre d'**outils** activés (par exemple **3/4**), le menu **Rapide** pour régler la profondeur de réponse, et le **micro** pour dicter votre demande.

![Interface de Mistral Vibe](images/mistral-03-interface.png)

</div>

<div class="etape" markdown>

### <span class="etape-num">4</span> Formuler une demande

Cliquez dans la zone de saisie (« Tapez / pour un accès rapide ») et décrivez ce que vous voulez obtenir. Une bonne demande précise quatre éléments : le **résultat attendu**, les **sources** à utiliser, le **public** visé et les **contraintes** (longueur, ton, format). Pour envoyer, appuyez sur **Entrée** ou cliquez sur la **flèche noire** qui apparaît à droite dès que vous commencez à écrire. Poursuivez ensuite la conversation pour affiner le résultat.

![Rédaction d'une demande](images/mistral-04-demande.png)

</div>

<div class="etape" markdown>

### <span class="etape-num">5</span> Choisir le mode de réponse

Dans la zone de saisie, cliquez sur le menu **Rapide** pour choisir parmi trois modes :

- **Rapide** : des réponses immédiates, pour une question simple ou une reformulation ;
- **Réflexion** : pour une tâche complexe (préparer une séance complète, analyser plusieurs documents). Vibe découpe le travail en étapes et affiche sa progression ;
- **Recherche** : une analyse approfondie qui croise plusieurs sources web et produit un rapport. La version gratuite en permet **5 par mois** ; le compteur s'affiche sous l'option.

Pendant que Vibe travaille, le bouton **carré noir**, qui remplace le micro, arrête la tâche à tout moment.

![Menu des modes Rapide, Réflexion et Recherche](images/mistral-05-mode.png)

</div>

<div class="etape" markdown>

### <span class="etape-num">6</span> Découvrir le menu +

Cliquez sur le bouton **+** à gauche de la zone de saisie. Il donne accès à toutes les ressources que Vibe peut utiliser pour votre demande :

| Option | À quoi elle sert |
|---|---|
| **Télécharger des fichiers** | Joindre un document à la conversation (voir l'étape suivante) |
| **Connecteurs** | Relier Vibe à d'autres services (espace de stockage, messagerie…), avec votre autorisation |
| **Outils** | Activer ou désactiver les outils que Vibe peut utiliser, comme la recherche web ou la génération d'images |
| **Projets** | Rattacher la conversation à l'un de vos projets |
| **Bibliothèques** | Appuyer la réponse sur une de vos bibliothèques de documents |
| **Workflows** | Lancer un processus prédéfini, lorsque votre espace de travail en propose |
| **Agents** | Utiliser un assistant personnalisé |
| **Réinitialiser l'entrée** | Vider la zone de saisie et retirer les éléments ajoutés |

![Menu du bouton +](images/mistral-06-menu.png)

</div>

<div class="etape" markdown>

### <span class="etape-num">7</span> Joindre un document

Cliquez sur le bouton **+**, puis sur **Télécharger des fichiers**, et sélectionnez votre document : PDF, Word, PowerPoint, tableur ou image. Le fichier apparaît au-dessus de la zone de saisie : posez ensuite votre question à son sujet. Un fichier joint n'est disponible que dans la conversation en cours.

</div>

<div class="etape" markdown>

### <span class="etape-num">8</span> Activer le Canvas

Le **Canvas** est un éditeur de texte qui s'ouvre à côté de la conversation. Il est idéal pour un document long que vous voulez retoucher : plan de cours, consignes d'un projet, fiche d'exercices. Il est **désactivé par défaut** : il suffit de l'activer une fois.

Dans la zone de saisie, cliquez sur l'icône **Outils** (celle qui affiche **3/4**), puis cochez **Canvas**. Le compteur passe à **4/4**. Vous pouvez aussi passer par le bouton **+**, puis **Outils**.

![Menu Outils avec l'option Canvas](images/mistral-07-canvas-activer.png)

</div>

<div class="etape" markdown>

### <span class="etape-num">9</span> Rédiger un document dans le Canvas

1. **Ouvrir un Canvas** : écrivez votre demande en ajoutant « dans un canvas », par exemple : « Rédige dans un canvas les consignes d'un projet de 4 semaines sur le dimensionnement d'une installation photovoltaïque ». Le document s'affiche dans un panneau à droite. Dans la conversation, une **vignette** portant le titre du document permet de le rouvrir si vous fermez le panneau.
2. **Modifier le texte** : cliquez directement dans le document pour corriger ou compléter, comme dans un traitement de texte. Pour faire retravailler un passage par Vibe, sélectionnez-le et tapez votre consigne (« simplifie ce paragraphe », « ajoute un exemple de calcul »).
3. **Utiliser les actions rapides** : la barre d'icônes verticale, à droite du document, propose des retouches en un clic (modifier, ajuster la longueur, adapter le niveau, traduire…). Survolez chaque icône pour afficher son nom.
4. **Récupérer le document** : en haut à droite du panneau, cliquez sur l'icône de **téléchargement** (flèche vers le bas) pour enregistrer le document, ou sur l'icône de **copie** pour le coller dans votre traitement de texte. L'icône à double flèche affiche le Canvas en plein écran, et la **croix** en haut à gauche le ferme.

![Document ouvert dans le Canvas](images/mistral-07b-canvas-utiliser.png)

</div>

<div class="etape" markdown>

### <span class="etape-num">10</span> Créer une bibliothèque de documents

Une **bibliothèque** rassemble vos documents de référence (polycopiés, supports, articles) pour que Vibe puisse s'en servir dans toutes vos conversations, sans les joindre à chaque fois.

1. Dans la barre latérale, cliquez sur **Contexte**, puis sur **Bibliothèques**. La page affiche vos bibliothèques et celles partagées avec vous.
2. Cliquez sur **+ Nouvelle bibliothèque** en haut à droite. Une bibliothèque nommée « Nouvelle bibliothèque » apparaît dans la liste.
3. Cliquez dessus pour l'ouvrir, renommez-la avec un nom explicite (par exemple le nom de votre cours), puis ajoutez vos fichiers.
4. Dans une conversation, cliquez sur **+**, puis sur **Bibliothèques**, et choisissez la vôtre : Vibe répond en s'appuyant sur vos documents et cite les passages utilisés.

Le bouton **Indexer un site web**, à côté, permet d'ajouter le contenu d'une page web à vos sources.

![Page des bibliothèques](images/mistral-08-bibliotheque.png)

</div>

<div class="etape" markdown>

### <span class="etape-num">11</span> Regrouper son travail en projets

Dans la barre latérale, repérez la rubrique **Projets** et créez un nouveau projet, par exemple un par cours. Pour y rattacher une conversation, cliquez sur **+**, puis sur **Projets**. Les conversations, fichiers et instructions d'un projet restent regroupés et partagent le même contexte : vous n'avez pas à tout réexpliquer à chaque nouvelle conversation.

![Liste des projets](images/mistral-09-projets.png)

</div>

<div class="etape" markdown>

### <span class="etape-num">12</span> Définir des instructions personnalisées

Dans la barre latérale, cliquez sur **Contexte**, puis sur **Instructions**. Décrivez-y ce qui vaut pour toutes vos demandes, par exemple : « Je suis enseignant en école d'ingénieurs. Réponds en français, de façon structurée, et signale toujours les points à vérifier. » Vibe en tiendra compte dans toutes vos conversations.

</div>

<div class="etape" markdown>

### <span class="etape-num">13</span> Utiliser une conversation temporaire

Pour une demande que vous ne souhaitez pas conserver, cliquez sur l'**icône de conversation temporaire**, en haut à droite de l'écran : elle n'est pas enregistrée dans votre historique et n'est pas utilisée pour entraîner les modèles de Mistral.

</div>

## Ressources officielles

- [Documentation de Mistral Vibe](https://docs.mistral.ai/vibe) : présentation générale et nouveautés (en anglais).
- [Bien démarrer une tâche](https://docs.mistral.ai/vibe/work/get-started) : comment formuler une demande et suivre sa progression.
- [Les bibliothèques de documents](https://docs.mistral.ai/vibe/work/libraries) : créer et utiliser une bibliothèque.

## Points de vigilance

!!! warning "Données"
    Mistral AI est une entreprise française soumise au RGPD, ce qui en fait un bon choix pour vos supports de cours. Ne déposez pas pour autant de données personnelles d'étudiants (noms, notes, copies). Dans les paramètres de votre compte, vérifiez l'option d'utilisation de vos conversations pour l'entraînement des modèles, et désactivez-la si vous le souhaitez.

!!! tip "Fiabilité"
    Vibe peut se tromper avec aplomb : calculs, dates, références bibliographiques. Relisez tout contenu avant de le transmettre à vos étudiants, en particulier les corrigés d'exercices et les chiffres.

!!! info "Relire avant d'utiliser"
    Mistral le recommande lui-même : considérez chaque résultat comme un brouillon. Vérifiez les faits, les tableaux et les sources, et demandez une révision si le ton, la structure ou le niveau ne conviennent pas.

!!! note "Une interface qui évolue vite"
    L'assistant a changé de nom en mai 2026 et d'organisation en septembre 2026. Si un intitulé de ce tutoriel ne correspond plus à ce que vous voyez, cherchez la fonction équivalente dans la barre latérale ou derrière le bouton **+**.
