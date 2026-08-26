# Motothèque

Une encyclopédie moto, par un fan pour les fans.

**17 marques · 206 modèles · 269 générations · 439 repères historiques**

Fiches techniques détaillées, différences d'une année à l'autre, histoire de
chaque modèle, comparateur jusqu'à six machines et estimation du coût d'usage.

## Ce que contient le site

- **206 modèles**, dont 91 finitions traitées comme des machines à part entière
- **22 caractéristiques** par année-modèle, renseignées à 99 %
- **269 générations**, chacune avec sa liste de ce qui change
- **115 historiques rédigés** et 439 repères datés, de 1901 à 2025
- Un **glossaire de 39 termes** expliqués en français courant
- Une version **anglaise** accessible par un bouton

## Les pages

| Page | Rôle |
|---|---|
| Accueil | Recherche instantanée sur les noms, les marques et les caractéristiques |
| Marques | Les 17 constructeurs, leur origine et leur gamme complète |
| Catalogue | Filtres par catégorie, marque, permis A2, hauteur de selle et budget |
| Modèle | Fiche technique, frise des générations, histoire, coût d'usage |
| Comparateur | Jusqu'à six motos côte à côte, adresse partageable |
| Chronologie | Les 439 repères de toutes les marques, filtrables par décennie |
| Glossaire | Le vocabulaire technique du site, sans jargon |

## Publication

Le site tient dans un seul fichier `index.html`, sans dépendance ni étape de
compilation. Il s'ouvre aussi bien en local qu'une fois hébergé, et fonctionne
sur GitHub Pages sans configuration particulière.

## Modifier le contenu

Tout est dans le bloc `<script>` de `index.html` :

| Tableau | Contenu |
|---|---|
| `BRANDS` | Les marques |
| `CATEGORIES` | Les familles de motos |
| `MODELS` | Les modèles, leurs générations et leurs caractéristiques |
| `FINITIONS` | Les déclinaisons, écrites en différentiel du modèle de base |
| `GLOSSAIRE` | Les définitions |
| `TRAD_UI`, `TRAD_SPECS` | Les traductions anglaises |

Pour ajouter une moto, copiez un bloc de `MODELS` et modifiez-le. Pour ajouter
une finition, il suffit d'écrire ce qui change par rapport au modèle de base :
le reste est recopié automatiquement.

Pour afficher une photo à la place du schéma technique, renseignez le champ
`photo` du modèle avec une URL d'image.

**Les compteurs du site se mettent à jour tout seuls.** Les chiffres affichés en
page d'accueil, dans le catalogue et dans la chronologie sont recalculés à
chaque chargement. Seuls ceux de ce fichier sont écrits à la main : pensez à les
corriger ici après un ajout important.

## Auteur et droits

Site créé par **Emerick Wbg**.

© 2026 Emerick Wbg. Tous droits réservés. Les textes et les schémas techniques
de ce site sont des créations originales protégées par le droit d'auteur.
Toute reproduction, même partielle, est soumise à autorisation.

## Crédits

Chiffres relevés dans les fiches constructeur au lancement de chaque
année-modèle. Ils varient selon le marché et doivent être vérifiés avant achat.
Le coût d'usage est une estimation calculée pour 8 000 km par an, dont toutes
les hypothèses sont affichées sur les fiches.
