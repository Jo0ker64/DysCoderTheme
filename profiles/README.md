# Profil DysCoder — Lecture

[English version](README.en.md)

Le thème DysCoder change les couleurs de Visual Studio Code. Ce profil facultatif complète le thème avec des réglages de confort : code plus aéré, repères d'indentation visibles et arborescence de projet plus facile à parcourir.

Le profil ne remplace pas vos préférences sans votre accord. Vous pouvez copier tous les réglages ou uniquement ceux qui vous conviennent.

## Réglages inclus

- Police à `16` px, avec un interligne de `28` px.
- Léger espacement des caractères (`0.4`).
- Ligne active visible et minimap désactivée.
- Guides d'indentation et de paires d'accolades renforcés.
- Dossiers de l'Explorateur affichés séparément, sans compression.
- Dossiers affichés avant les fichiers.
- Indentation de l'arborescence réglée à `30`.
- Fil d'Ariane activé pour toujours voir le chemin du fichier ouvert.

## Installation

1. Installez et activez le thème **DysCoder Universal**.
2. Ouvrez le fichier [`DysCoder-Reading.settings.json`](DysCoder-Reading.settings.json).
3. Dans VS Code, ouvrez la palette de commandes avec `Ctrl+Shift+P`.
4. Lancez `Preferences: Open User Settings (JSON)`.
5. Copiez les réglages que vous souhaitez conserver depuis le fichier du profil.
6. Enregistrez : VS Code applique les changements immédiatement.

## Police

Le profil ne force aucune police. Vous pouvez tester [OpenDyslexic](https://opendyslexic.org/), Atkinson Hyperlegible Mono ou toute police monospace avec laquelle vous lisez confortablement.

Après avoir installé une police, ajoutez-la éventuellement à vos préférences :

```json
{
  "editor.fontFamily": "OpenDyslexic, Consolas, monospace"
}
```

## Adapter le profil à votre lecture

Les valeurs proposées sont un point de départ, pas une règle. Ajustez sans hésiter :

- `editor.fontSize` si le texte est trop petit ou trop grand ;
- `editor.lineHeight` si les lignes sont trop rapprochées ou trop éloignées ;
- `editor.letterSpacing` si les caractères sont trop serrés ;
- `workbench.tree.indent` si l'arborescence a besoin de plus ou moins d'espace.

Si un réglage gêne votre façon de travailler, supprimez-le simplement de vos préférences.
