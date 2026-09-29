# Consignes pour Claude — Boîte à outils IA (IMT Mines Alès)

Ce dépôt contient le site « Boîte à outils IA » destiné aux enseignants d'IMT Mines Alès : une fiche tutoriel par outil d'IA gratuit.

## Communication avec l'autrice

- Elle est ingénieure pédagogique et débute avec GitHub.
- Toujours expliquer ce que tu fais **en français simple, sans jargon** (ou en expliquant chaque terme technique).
- Proposer les modifications dans une **pull request** et attendre sa relecture avant toute validation.
- Ne jamais supprimer de fichier sans son accord explicite.

## Fonctionnement du site

- Site construit avec **MkDocs Material**.
- Publication automatique sur **GitHub Pages** par le workflow `.github/workflows/publication.yml`, à chaque modification de la branche `main`.
- Les versions des outils sont **figées** dans `requirements.txt` : ne pas les changer sans raison.
- Vérifier une modification en local : `pip install -r requirements.txt` puis `mkdocs build` (ne doit afficher aucun `WARNING`). Ne pas enregistrer le dossier `site/` produit par cette commande.

## Organisation

- **Menu du site** : section `nav` de `mkdocs.yml`. Toute nouvelle fiche doit y être ajoutée.
- **Pages** :
  - `docs/index.md` (accueil) et `docs/bonnes-pratiques.md` ;
  - quatre catégories, chacune avec sa page `index.md` : `docs/assistants`, `docs/creation`, `docs/recherche`, `docs/traduction`.
- **Feuille de style** : `docs/extra.css`, déclarée dans `mkdocs.yml` sous `extra_css: - extra.css`. C'est le seul fichier CSS utilisé par le site.

## Charte graphique

Seules **5 couleurs** sont autorisées (dans `docs/extra.css` comme partout ailleurs) :

| Nom | Code |
|---|---|
| Bleu IMT | `#14223C` |
| Rose | `#F14862` |
| Cyan | `#00B8DE` |
| Blanc | `#FFFFFF` |
| Gris bleuté | `#EDF3F4` |

Des transparences de ces couleurs (`rgba(...)`) sont acceptables ; aucune autre teinte.

## Modèle d'une fiche

Fiches de référence, terminées : `docs/recherche/notebooklm.md`, `docs/assistants/le-chat.md`, `docs/assistants/claude.md`. S'en inspirer pour toute nouvelle fiche.

1. **En-tête** :
   - titre `# Nom de l'outil` ;
   - badges d'hébergement : `badge-souverain`, `badge-ue`, `badge-hors-ue`, `badge-gratuit` (ex. `<span class="badge badge-hors-ue">Hors UE</span>`) ;
   - date de dernière vérification : `<p class="maj">Dernière vérification : mois année</p>` ;
   - courte présentation ;
   - bouton vers l'outil : `[Ouvrir l'outil](https://...){ .md-button .md-button--primary }`.
2. **`## À quoi ça sert dans le supérieur`** : liste d'usages.
3. **`## Version gratuite`** : seuls les outils gratuits sont présentés ; les fonctions payantes sont **signalées clairement**.
4. **`## Cas d'usage`** en onglets (`=== "Titre"`), avec des exemples ancrés dans les **disciplines d'une école d'ingénieurs** et des **consignes à copier** (blocs de code).
5. **`## Pas à pas`** :
   - chaque étape est un bloc :
     ```
     <div class="etape" markdown>

     ### <span class="etape-num">N</span> Titre de l'étape

     Texte…

     ![Description](outil-NN-description.png)

     </div>
     ```
   - **une étape = une action** ; les sous-actions sont numérotées (1., 2., 3.) ;
   - consignes très précises : « cliquez sur **Nom exact du bouton** », avec les intitulés **tels qu'ils s'affichent en français dans l'interface**.
6. **`## Ressources officielles`**, puis **`## Points de vigilance`** (encadrés `!!! warning`, `!!! tip`, `!!! info`, `!!! note`).

Ton et contenu :

- **Vouvoiement** des enseignants.
- **Jamais de données personnelles** (dans le texte, les exemples ou les captures d'écran : noms, adresses e-mail, favoris du navigateur, etc.).

## Captures d'écran

- **Fiches Recherche** : images dans `docs/recherche/images/`, référencées par `images/nom.png`.
- **Fiches Assistants** : images directement dans `docs/assistants/`, référencées par `nom.png`.
- **Nommage** : `outil-NN-description.png`, où `NN` est le numéro de l'étape sur deux chiffres (règle appliquée depuis la fiche Claude ; les fiches plus anciennes peuvent ne pas la respecter).
- Après tout ajout ou renommage, vérifier que chaque image référencée existe (`mkdocs build` signale les absentes).
