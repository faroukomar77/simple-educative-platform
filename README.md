# Learn English Through Stories

Site web statique pour apprendre l'anglais à travers des histoires courtes et engageantes, organisées par niveaux CEFR (A1, A2, B1).

## Description

**Learn English Through Stories** est un projet de site web pédagogique qui permet d'améliorer son vocabulaire, sa grammaire, sa compréhension écrite et orale en anglais de manière naturelle et ludique.

Le principe est simple :
1. Lire une histoire correspondant à son niveau
2. Relire la même histoire 3 fois par jour
3. Écouter l'audio (quand disponible) tout en lisant
4. Répéter ce cycle quotidiennement pendant une semaine

Les histoires sont courtes, adaptées au quotidien, et accompagnées d'audios pour les niveaux A1 et A2.

> **Note** : Les versions audio pour toutes les histoires ainsi que les histoires de niveau B2 arrivent bientôt.

## Fonctionnalités

- Page d'accueil avec présentation du cours, niveaux et témoignages (feedbacks)
- Navigation vers les listes d'histoires par niveau (A1, A2, B1)
- Pages individuelles pour chaque histoire avec le texte complet
- Lecteur audio intégré pour les histoires A1 et A2
- Page Contact Us avec téléphone, email et carte
- Design responsive avec une navigation claire
- Utilisation de Font Awesome et Google Fonts (Poppins, Prompt, Cascadia Mono)

## Structure du projet

```
Projet_tp_dev_web/
├── home.html                  # Page d'accueil
├── Contact_us.html            # Page de contact
├── a1_stories.html            # Liste des histoires A1
├── a1_story1.html ... a1_story6.html
├── a2_stories.html
├── a2_story1.html ... a2_story6.html
├── b1_stories.html
├── b1_story1.html ... b1_story6.html
├── A1_audios/                 # Audios pour le niveau A1 (audio1.mp3 à audio6.mp3)
├── A2_audios/                 # Audios pour le niveau A2
├── style_home.css             # Styles de la page d'accueil
├── levels_style.css           # Styles des pages listes de stories
├── story_style.css            # Styles des pages d'histoires
├── contact_us_style.css       # Styles de la page contact
├── .vscode/settings.json      # Configuration Live Server
└── (images et screenshots)
```

## Technologies utilisées

- **HTML5**
- **CSS3** (Flexbox, styles personnalisés)
- **Audio HTML5** (`<audio controls>`)
- Font Awesome 6 (CDN)
- Google Fonts
- Google Maps (iframe sur la page contact)

## Comment lancer le projet

Ce projet est un site **entièrement statique**. Aucune installation ou serveur backend n'est nécessaire.

### Méthode simple
1. Ouvrez le fichier `home.html` directement dans votre navigateur web (Chrome, Firefox, Edge, etc.).

### Méthode recommandée (développement)
Utilisez l'extension **Live Server** de VS Code :
- Le projet est configuré pour le port **5503**
- Clic droit sur `home.html` → **Open with Live Server**

## Contenu disponible

| Niveau | Nombre d'histoires | Audio |
|--------|---------------------|-------|
| A1     | 6                   | Oui   |
| A2     | 6                   | Oui   |
| B1     | 6                   | Non (bientôt) |

## Contact

- **Email** : learnenglishthroughstories@gmail.com
- **Téléphone** : +212 5 66 23 54 00

---

**Projet TP Développement Web**  
Copyright © Learn English Through Stories
