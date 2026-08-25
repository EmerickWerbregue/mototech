# Motothèque

Une encyclopédie moto, par un fan pour les fans.

**17 marques · 115 modèles · 178 générations · 439 repères historiques**

Fiches techniques détaillées, différences d'une année à l'autre, historique de
chaque modèle et comparateur jusqu'à 6 machines.

## Publication

Le site tient dans un seul fichier `index.html`, sans dépendance ni étape de
compilation. Il s'ouvre aussi bien en local qu'une fois hébergé.

## Modifier le contenu

Tout est dans le bloc `<script>` de `index.html` :

- `BRANDS` : les marques
- `CATEGORIES` : les familles de motos
- `MODELS` : les modèles, leurs générations et leurs caractéristiques

Pour ajouter une moto, copiez un bloc de `MODELS` et modifiez-le.
Pour afficher une photo à la place du schéma technique, renseignez le champ
`photo` du modèle avec une URL d'image.

## Crédits

Chiffres relevés dans les fiches constructeur au lancement de chaque
année-modèle. Ils varient selon le marché et doivent être vérifiés avant achat.
