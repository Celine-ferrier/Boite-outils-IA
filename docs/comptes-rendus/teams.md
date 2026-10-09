# Teams

<span class="badge badge-hors-ue">Hors UE</span> <span class="badge badge-gratuit">Inclus avec le compte enseignant</span>

<p class="maj">Dernière vérification : à compléter</p>

**Microsoft Teams**, l'outil de visioconférence de l'école, peut **transcrire une réunion en direct** : chaque intervention s'affiche par écrit, avec le nom de la personne qui parle. À la fin de la réunion, la transcription reste disponible et peut être téléchargée, puis utilisée pour rédiger le compte rendu. Tous les enseignants disposent de la suite Office (Microsoft 365) avec leur compte enseignant : la fonction est déjà disponible, rien à installer.

!!! info "Fiche en cours de rédaction"
    Les captures d'écran du tutoriel seront bientôt ajoutées.

## À quoi ça sert dans le supérieur

- **Rédiger le compte rendu d'une réunion en visio** : réunion d'équipe pédagogique, comité de pilotage, réunion avec un partenaire à distance.
- **Savoir qui a dit quoi** : Teams indique le nom de chaque intervenant, grâce aux comptes des participants.
- **Permettre à un absent de prendre connaissance** de ce qui a été dit.

## Version gratuite

La transcription est **incluse** dans Teams avec votre compte enseignant (suite Office Microsoft 365) : aucun abonnement supplémentaire n'est nécessaire.

- La transcription est lancée par l'organisateur ou un participant de l'école ; **tous les participants sont prévenus** par un bandeau.
- Le **résumé automatique** de la réunion par Copilot (« récapitulatif intelligent ») est une fonction **payante**, non incluse : vous rédigerez le compte rendu vous-même ou avec un assistant IA (voir les cas d'usage).
- La transcription téléchargée s'ouvre dans **Word**, inclus dans la même suite Office : vous pouvez la relire et la corriger avant de rédiger le compte rendu.

## Cas d'usage

=== "Compte rendu de réunion"

    **Exemple** : une réunion en visio de l'équipe pédagogique d'un module de génie des procédés.

    Téléchargez la transcription, puis collez-la dans [ILaaS](../assistants/ilaas.md) ou [Mistral Vibe](../assistants/le-chat.md) avec cette consigne :

    ```
    Voici la transcription d'une réunion d'équipe pédagogique.
    Rédige un compte rendu structuré :
    - points abordés, avec un résumé de chacun ;
    - décisions prises ;
    - actions à mener, avec la personne responsable et l'échéance.
    Désigne les participants par leur fonction, sans leur nom.
    Reste fidèle à la transcription : n'ajoute aucune information.

    Transcription :
    [collez la transcription ici]
    ```

=== "Réunion avec un partenaire"

    **Exemple** : un point d'avancement en visio avec une entreprise qui accueille un projet étudiant.

    ```
    À partir de cette transcription, liste les engagements pris
    par chaque partie et les prochaines étapes, sous forme de
    tableau : action, responsable, échéance.

    Transcription :
    [collez la transcription ici]
    ```

## Pas à pas

:material-magnify-plus-outline: Cliquez sur une capture pour l'agrandir.
{ .astuce-zoom }

<!--
Étapes à rédiger à partir des captures (plan provisoire) :
 1. Pendant la réunion, ouvrir le menu Plus d'actions
 2. Enregistrer et transcrire > Démarrer la transcription
 3. Vérifier la langue parlée
 4. Arrêter la transcription
 5. Retrouver la transcription après la réunion
 6. Télécharger la transcription
-->

## Ressources officielles

- [Démarrer, arrêter et télécharger des transcriptions en direct dans les réunions Teams](https://support.microsoft.com/fr-fr/office/d%C3%A9marrer-arr%C3%AAter-et-t%C3%A9l%C3%A9charger-des-transcriptions-en-direct-dans-les-r%C3%A9unions-microsoft-teams-dc1a8f23-2e20-4684-885e-2152e06a4a8b) : aide officielle de Microsoft.

## Points de vigilance

!!! warning "Consentement des participants"
    Annoncez la transcription en début de réunion, même si Teams affiche un bandeau d'information. Chaque participant peut choisir de masquer son nom dans la transcription.

!!! warning "Données"
    La transcription est réalisée et stockée par Microsoft (hors Union européenne). Pour une réunion sensible (jury, situation d'un étudiant), préférez enregistrer et transcrire avec [noScribe](noscribe.md), sur votre ordinateur.

!!! tip "Fiabilité"
    Relisez la transcription avant de l'utiliser : les noms propres, les sigles et le vocabulaire technique sont souvent mal transcrits, surtout quand plusieurs personnes parlent en même temps.
