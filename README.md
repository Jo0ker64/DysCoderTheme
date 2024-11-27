# README pour DysCoder
Voici une description combinée de mon projet.

## Recommandation de police

Ce thème est optimisé pour la police adaptée `OpenDyslexic`.

### Installer une police :
- Téléchargez et installez [OpenDyslexic](https://opendyslexic.org/). N'hésitez pas à soutenir le créateur de cette police. 
- Ajoutez ceci dans vos paramètres VS Code (`settings.json`) ou remplacez la police existante par :

```json
{
  "editor.fontFamily": "OpenDyslexic",
}
```

### Paramétrages supplémentaires : 
- Pour une meilleure lisibilité, vous pouvez ajuster la taille de la police dans les paramètres VS Code ('setting.json) qui se trouve généralement à cet emplacement C:\Users\"nom_utilisateur"\AppData\Roaming\Code\User\settings.json


```json
{
  "editor.formatOnSave": true,
  "python.formatting.provider": "black",
  "editor.fontSize": 16, 
  "editor.lineHeight": 24,                                                 
  "editor.fontLigatures": true,                                          
  "editor.cursorStyle": "block",                                       
  "editor.cursorBlinking": "smooth",
  "editor.lineNumbers": "relative",
  "editor.guides.bracketPairs": true,
  "editor.bracketPairColorization.enabled": true
}