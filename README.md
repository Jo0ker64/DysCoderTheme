# DysCoder Universal Theme

Un thème conçu spécialement pour les développeurs atteints de **dyslexie**, de **TDAH**, ou recherchant simplement un environnement de développement clair, contrasté et ergonomique.  

Ce thème met l'accent sur :
- Une personnalisation adaptée aux besoins spécifiques des utilisateurs.
- Des contrastes optimaux pour une meilleure lisibilité.
- Une compatibilité avec une grande variété de langages.

---

## 🖋 **Recommandation de police**

Pour tirer le meilleur parti de DysCoder, nous recommandons d'utiliser la police [OpenDyslexic](https://opendyslexic.org/). Cette police est conçue pour améliorer la lisibilité et réduire la fatigue oculaire.

### Installation :
1. Téléchargez et installez **OpenDyslexic** depuis leur [site officiel](https://opendyslexic.org/).
2. Ajoutez ceci à votre `settings.json` dans VS Code :
   ```json
   {
     "editor.fontFamily": "OpenDyslexic"
   }
   ```

---

## ✨ **Configuration recommandée**

Pour une expérience optimale, nous vous recommandons d'ajouter les paramètres suivants dans votre `settings.json` :

```json
{
    "files.autoSave": "afterDelay",
    "explorer.confirmDelete": false,
    "explorer.confirmDragAndDrop": false,
    "git.autofetch": true,
    "git.enableSmartCommit": true,
    "git.confirmSync": false,
    "git.openRepositoryInParentFolders": "never",
    "workbench.iconTheme": "material-icon-theme",
    "security.workspace.trust.untrustedFiles": "open",
    "doublebot.showInlineKeybindingHint": "Never",
    "github.copilot.editor.enableAutoCompletions": true,
    "liveServer.settings.donotShowInfoMsg": true,
    "python.formatting.provider": "black",
    "editor.formatOnSave": true,
    "editor.fontFamily": "OpenDyslexic",
    "editor.fontSize": 16,
    "editor.lineHeight": 24,
    "editor.fontLigatures": true,
    "editor.guides.bracketPairs": true,
    "editor.bracketPairColorization.enabled": true,
    "editor.cursorStyle": "block",
    "editor.cursorBlinking": "smooth",
    "editor.stickyScroll.enabled": true,
    "editor.renderLineHighlight": "all",
    "editor.lineNumbers": "on",
    "editor.guides.highlightActiveIndentation": true,
    "terminal.integrated.fontFamily": "monospace",
    "terminal.integrated.fontSize": 18,
    "terminal.integrated.lineHeight": 1,
    "terminal.integrated.cursorBlinking": true,
}
```

### Pourquoi ces paramètres ?
- **Navigation fluide** : Suppression des confirmations inutiles dans l'explorateur.
- **Personnalisation de l'éditeur** : Réglages de police, taille, interligne et style adaptés.
- **Couleurs et icônes** : Thèmes de couleurs optimisés et utilisation d’icônes modernes.
- **Compatibilité avec les langages** : Associations configurées pour une grande variété de fichiers.

---

## 🎨 **Langages pris en charge**

Le thème DysCoder est compatible avec une large gamme de langages. Voici une liste non exhaustive :
- HTML, CSS, JavaScript, TypeScript
- Python, PHP, Ruby, Swift
- Java, C, C#, C++
- Kotlin, Go, SQL, R
- Markdown, Visual Basic, Assembly
- Frameworks comme Flutter, Unity, Elixir, Phoenix

---

## 🚀 **Installation**

### Étape 1 : Ajouter DysCoder
1. Placez le fichier de thème dans le dossier suivant :  
   - **Windows** : `C:\Users\%USERNAME%\.vscode\extensions\`
   - **macOS** : `~/.vscode/extensions/`
   - **Linux** : `~/.vscode/extensions/`

2. Redémarrez VS Code.

### Étape 2 : Activer DysCoder
1. Ouvrez la palette de commandes (`Ctrl+Shift+P` ou `Cmd+Shift+P`).
2. Recherchez `Preferences: Color Theme`.
3. Sélectionnez **DysCoder Universal Theme**.

---

## 📚 **Documentation en cours**

### Caractéristiques du thème
- **Contraste élevé** : Pour garantir la lisibilité même en cas de fatigue visuelle.
- **Couleurs unifiées** : Les éléments communs (variables, mots-clés, fonctions) ont des couleurs uniformes dans tous les langages.
- **Spécificités par langage** : Des couleurs personnalisées pour chaque type d’élément propre à un langage.

### Quelques détails techniques :
Le thème repose sur deux principales sections :
- **`semanticTokenColors`** : Définit les couleurs pour les éléments communs à tous les langages (commentaires, mots-clés, chaînes de caractères, etc.).
- **`tokenColors`** : Définit les couleurs spécifiques à chaque langage.

### Optimisation en cours
Nous continuons à affiner le thème pour inclure plus de langues et améliorer la compatibilité avec de nouvelles extensions.

---

## 📝 **Contribuer**

Vous avez une suggestion ou un retour à nous faire ?  
Ouvrez une issue sur notre [dépôt GitHub](https://github.com/votre-repo).

---

## ❤️ **Remerciements**

Merci à toutes les personnes qui soutiennent le projet DysCoder.  
Votre retour est essentiel pour améliorer ce thème.

---

## 🔄 **Mises à jour récentes**

**v1.0**
- Première version avec prise en charge des principaux langages.
- Ajustement des contrastes pour améliorer la lisibilité.
- Ajout de recommandations pour les utilisateurs dyslexiques.

---

## 🛠️ **Prochaines étapes**

- Ajouter une palette **clair** pour une utilisation dans des environnements lumineux.
- Prise en charge supplémentaire pour des langages moins courants comme Swift, Kotlin, et Assembly.
- Améliorer la compatibilité avec les extensions comme GitLens et Copilot.

---

## 📧 **Feedback**

Si vous avez des suggestions, des problèmes ou des idées d'amélioration, n'hésitez pas à ouvrir une issue sur GitHub ou à me contacter à [martel.jonathan64@gmail.com](mailto:martel.jonathan64@gmail.com).


---


Pour ajouter une image dans un fichier Markdown (`.md`), tu utilises la syntaxe suivante :

### 1. **Image avec chemin local**
```markdown
![Texte alternatif](chemin/vers/image.png)
```

- **Texte alternatif** : Décrit l'image (utile pour l'accessibilité ou si l'image ne charge pas).
- **chemin/vers/image.png** : Chemin relatif ou absolu vers l'image.

**Exemple** :
```markdown
![Logo DysCoder](images/dyscoder-logo.png)
```

### 2. **Image depuis une URL**
```markdown
![Texte alternatif](https://example.com/image.png)
```

**Exemple** :
```markdown
![Logo GitHub](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
```

### 3. **Taille d'une image avec HTML (Markdown ne supporte pas nativement la taille)**
Si tu veux redimensionner une image, tu dois utiliser du HTML intégré :
```html
<img src="chemin/vers/image.png" alt="Texte alternatif" width="300" />
```

**Exemple** :
```html
<img src="images/dyscoder-logo.png" alt="Logo DysCoder" width="200" />
```

### Où placer les images ?
- **Dans un dossier dédié** : Tu peux créer un dossier `images/` dans ton projet pour organiser tes ressources.
- **URL directe** : Pratique pour les images hébergées en ligne.
