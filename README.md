# Atelier GitHub Copilot (Version Française)

Bienvenue à l'Atelier GitHub Copilot ! Ce dépôt contient le matériel de formation pour apprendre à utiliser GitHub Copilot efficacement dans vos projets de développement.

## 🎯 À propos de l'atelier

Cet atelier vous guidera à travers les différentes fonctionnalités de GitHub Copilot, notamment :
- Comprendre les capacités de GitHub Copilot
- Utiliser GitHub Copilot Chat pour un dialogue interactif avec l'IA
- Développer une nouvelle application en utilisant le mode agent
- Expliquer et améliorer le code existant

**Durée estimée** : 4-5 heures

## 📋 Prérequis

Avant de commencer l'atelier, assurez-vous d'avoir :
- ✅ Visual Studio Code installé
- ✅ Une licence GitHub Copilot active
- ✅ Un compte GitHub
- ✅ Les extensions VS Code requises :
  - GitHub Copilot
  - GitHub Copilot Chat
  - Python (pour l'atelier pratique)

## 🚀 Accéder à l'atelier

### Option 1 : Accès en ligne (Recommandé)

Accédez directement à l'atelier via GitHub Pages :

**[🔗 Ouvrir l'atelier](https://apacfsteam.github.io/2025-Github-Copilot-Workshop-French/github-copilot-workshop/index.html)**

### Option 2 : Consultation locale

1. Clonez ce dépôt :
```bash
git clone https://github.com/apacfsteam/2025-Github-Copilot-Workshop-French.git
cd 2025-Github-Copilot-Workshop-French
```

2. Ouvrez le fichier HTML dans votre navigateur :
```bash
open github-copilot-workshop/index.html
```

Ou consultez le fichier Markdown source :
```bash
cat workshop.md
```

## 📚 Structure du dépôt

```
.
├── README.md                           # Ce fichier
├── workshop.md                         # Source Markdown de l'atelier
├── github-copilot-workshop/           # Atelier généré (HTML)
│   ├── index.html                     # Page principale de l'atelier
│   ├── codelab.json                   # Métadonnées de l'atelier
│   └── img/                           # Images et ressources
├── workshop_english_backup.md         # Version anglaise de référence
├── workshop_japanese_backup.md        # Version japonaise de référence
└── claat                              # Outil de génération Codelabs
```

## 🛠️ Modifier l'atelier

Pour modifier le contenu de l'atelier :

1. Éditez le fichier `workshop.md`
2. Régénérez l'atelier HTML avec l'outil claat :
```bash
./claat export workshop.md
```

3. Validez et poussez vos modifications :
```bash
git add .
git commit -m "Mise à jour du contenu de l'atelier"
git push
```

## 🔗 Dépôt d'exercices pratiques

L'atelier utilise un dépôt Python séparé pour les exercices pratiques :

**[2025-Github-Copilot-Workshop-Python](https://github.com/moulongzhang/2025-Github-Copilot-Workshop-Python)**

Les participants devront forker ce dépôt pour suivre les exercices pratiques.

## 📖 Langues disponibles

- 🇫🇷 **Français** (version actuelle)
- 🇬🇧 [Anglais](workshop_english_backup.md)
- 🇯🇵 [Japonais](workshop_japanese_backup.md)

## 🤝 Contribution

Les contributions sont les bienvenues ! Pour contribuer :

1. Forkez ce dépôt
2. Créez une branche pour votre fonctionnalité (`git checkout -b feature/amelioration`)
3. Committez vos changements (`git commit -m 'Ajout d'une amélioration'`)
4. Poussez vers la branche (`git push origin feature/amelioration`)
5. Ouvrez une Pull Request

## 📝 Licence

Ce projet est fourni à des fins éducatives dans le cadre des ateliers GitHub Copilot.

## 📧 Support

Pour toute question ou problème, veuillez ouvrir une issue dans ce dépôt.

---

**Développé avec ❤️ par l'équipe APAC FSTeam**
