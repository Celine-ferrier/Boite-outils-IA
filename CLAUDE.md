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
- Chaque image du pas à pas doit se trouver **à l'intérieur d'un bloc `<div class="etape" markdown>`** : sinon la règle de taille ci-dessous ne s'applique pas et l'image s'affiche trop grande.

### Taille des images : règle à ne jamais modifier

La taille des captures est fixée dans `docs/extra.css` par la règle suivante. Elle doit rester **présente et identique** : ne pas changer la largeur, ne pas la supprimer, ne pas la déplacer dans un autre fichier.

```css
.md-typeset .etape img {
  display: block;
  width: 60%;
  margin: 0.4em auto 0;
  background: var(--imt-gris);
  cursor: zoom-in;
}
@media (max-width: 60em) {
  .md-typeset .etape img { width: 100%; }
}
```

Si une image paraît trop grande ou trop petite, recadrer la capture plutôt que modifier cette règle.

Comme toute capture est affichée à 60 % de la largeur, une capture étroite (un menu, une fenêtre) est agrandie et paraît énorme. Dans ce cas, **placer la capture au centre d'une marge gris bleuté `#EDF3F4`** (fichier image plus large que la capture), pour que son contenu s'affiche à une taille proche de sa taille réelle, sans rendre le texte illisible.

### Cadre gris des captures

Toutes les images ont un cadre gris pour ne pas se fondre dans le fond blanc. Il est défini dans `docs/extra.css` par la règle `.md-typeset img` (distincte de la règle de taille) : bordure de 6 px en gris bleuté (`var(--imt-gris)`) et liseré de bleu IMT transparent (`rgba(20, 34, 60, 0.15)`). Ne pas dessiner de cadre gris dans les fichiers image : il s'applique automatiquement.
