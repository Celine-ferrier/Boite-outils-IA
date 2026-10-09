# noScribe

<span class="badge badge-souverain">Sur votre ordinateur</span> <span class="badge badge-gratuit">Gratuit et open source</span>

<p class="maj">Dernière vérification : à compléter</p>

**noScribe** est un logiciel gratuit et open source qui **transcrit un enregistrement audio** (réunion, entretien) en texte, **directement sur votre ordinateur** : aucun fichier n'est envoyé sur internet. Il a été conçu par un chercheur en sciences sociales pour transcrire des entretiens. Il **distingue les différents intervenants** (« qui a dit quoi ») et fournit un éditeur pour relire et corriger la transcription en réécoutant l'enregistrement.

[Télécharger noScribe](https://github.com/kaixxx/noScribe){ .md-button .md-button--primary }

!!! info "Fiche en cours de rédaction"
    Le tutoriel complet sera bientôt disponible.

## À quoi ça sert dans le supérieur

- **Rédiger le compte rendu d'une réunion sensible** : conseil de perfectionnement, jury, réunion d'équipe pédagogique, sans que l'enregistrement quitte votre ordinateur.
- **Transcrire des entretiens** : suivi de projet étudiant, entretien avec un partenaire industriel, recherche en sciences humaines.
- **Garder une trace écrite** d'une séance de retour d'expérience ou d'un atelier.

## La chaîne complète, de l'enregistrement au compte rendu

1. **Enregistrer** la réunion avec un dictaphone ou un téléphone, après avoir informé les participants.
2. **Transcrire** le fichier avec noScribe, sur votre ordinateur.
3. **Relire et corriger** la transcription dans l'éditeur de noScribe.
4. **Rédiger le compte rendu** : collez la transcription dans [ILaaS](../assistants/ilaas.md) ou [Mistral Vibe](../assistants/le-chat.md) avec une consigne de compte rendu (voir les cas d'usage).

## Version gratuite

noScribe est **entièrement gratuit** et open source : pas de compte, pas d'abonnement, pas de limite de durée. Il fonctionne sur Windows, Mac et Linux.

Deux limites à connaître :

- **La transcription est longue** : sur un ordinateur ordinaire, elle prend souvent **plus de temps que la durée de l'enregistrement**. Lancez-la et laissez l'ordinateur travailler (pendant une pause, en fin de journée).
- **Le premier téléchargement est volumineux** : noScribe installe sur votre ordinateur les modèles d'IA de reconnaissance vocale. Prévoyez de la place sur le disque et une bonne connexion pour l'installation.

## Cas d'usage

=== "Compte rendu de réunion"

    **Exemple** : la réunion d'équipe pédagogique d'un département de génie mécanique.

    Après avoir transcrit et corrigé l'enregistrement avec noScribe, collez la transcription dans ILaaS avec cette consigne :

    ```
    Voici la transcription d'une réunion d'équipe pédagogique.
    Rédige un compte rendu structuré :
    - participants (désignés par leur fonction, sans nom) ;
    - points abordés, avec un résumé de chacun ;
    - décisions prises ;
    - actions à mener, avec la personne responsable et l'échéance.
    Reste fidèle à la transcription : n'ajoute aucune information.

    Transcription :
    [collez la transcription ici]
    ```

=== "Synthèse d'entretiens"

    **Exemple** : des entretiens de suivi avec des étudiants en projet de fin d'études.

    ```
    Voici la transcription d'un entretien de suivi de projet.
    Résume en 10 lignes : l'avancement, les difficultés
    rencontrées et les prochaines étapes convenues.

    Transcription :
    [collez la transcription ici]
    ```

=== "Relevé de décisions"

    **Exemple** : un conseil de perfectionnement de formation.

    ```
    À partir de cette transcription, liste uniquement les décisions
    prises et les points reportés à une prochaine réunion, sous forme
    de tableau à deux colonnes.

    Transcription :
    [collez la transcription ici]
    ```

## Pas à pas

:material-magnify-plus-outline: Cliquez sur une capture pour l'agrandir.
{ .astuce-zoom }

<!--
Étapes à rédiger à partir des captures (plan provisoire) :
 1. Télécharger et installer noScribe
 2. Choisir le fichier audio et le fichier de transcription
 3. Régler la langue et l'identification des intervenants
 4. Lancer la transcription
 5. Ouvrir la transcription dans l'éditeur
 6. Relire et corriger en réécoutant un passage
 7. Renommer les intervenants
 8. Enregistrer et copier la transcription
-->

## Ressources officielles

- [noScribe sur GitHub](https://github.com/kaixxx/noScribe) : téléchargement, mode d'emploi et questions fréquentes (en anglais).

## Points de vigilance

!!! warning "Consentement des participants"
    Informez toujours les participants avant d'enregistrer une réunion et obtenez leur accord. Supprimez l'enregistrement une fois la transcription vérifiée.

!!! warning "Données"
    noScribe fonctionne sur votre ordinateur : l'enregistrement et la transcription ne quittent pas votre poste. En revanche, si vous collez la transcription dans un assistant IA pour rédiger le compte rendu, choisissez **ILaaS** pour une réunion sensible, et retirez les noms des personnes.

!!! tip "Fiabilité"
    L'identification des intervenants n'est pas parfaite : noScribe peut confondre deux voix proches ou compter plus d'intervenants qu'en réalité. Relisez toujours la transcription dans l'éditeur avant de l'utiliser.

!!! info "Qualité de l'enregistrement"
    Plus l'enregistrement est clair, meilleure est la transcription : placez le dictaphone ou le téléphone au centre de la table, évitez les bruits de fond et demandez aux participants de ne pas parler en même temps.
