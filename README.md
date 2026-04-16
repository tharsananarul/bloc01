# BTS Com' Edu - Guide d'installation locale

Cette application est une **Single Page Application (SPA)** construite avec **React**, **Vite** et **Tailwind CSS**. Elle ne peut pas être ouverte simplement en double-cliquant sur le fichier `index.html`. Elle nécessite un environnement Node.js pour fonctionner.

## 🚀 Installation et Lancement

Suivez ces étapes pour faire fonctionner l'application sur votre ordinateur :

### 1. Prérequis
Assurez-vous d'avoir **Node.js** installé sur votre machine.
- Téléchargement : [https://nodejs.org/](https://nodejs.org/) (Prenez la version LTS)

### 2. Extraction
- Téléchargez le projet depuis AI Studio (Menu **Settings** > **Export to ZIP**).
- Décompressez le fichier ZIP dans un dossier sur votre bureau.

### 3. Installation des dépendances
Ouvrez votre terminal (ou le terminal intégré de VS Code) dans le dossier du projet et tapez :
```bash
npm install
```

### 4. Lancement du serveur de développement
Une fois l'installation terminée, lancez l'application avec :
```bash
npm run dev
```

### 5. Visualisation
- Le terminal affichera une adresse (généralement `http://localhost:3000` ou `http://localhost:5173`).
- Copiez et collez cette adresse dans votre navigateur.

## 🛠️ Pourquoi le fichier index.html est vide ?

C'est le principe de **React** :
- Le fichier `index.html` n'est qu'une "coquille" vide.
- Le code JavaScript (dans `src/`) génère dynamiquement tout le contenu et le design au moment où la page s'affiche.
- **Vite** est l'outil qui compile tout ce code pour que le navigateur puisse le comprendre.

## 📂 Structure du projet
- `src/App.tsx` : Le cœur de l'interface.
- `src/data/content.ts` : **C'est ici que vous pouvez modifier ou ajouter des cours.**
- `src/index.css` : Le design et les couleurs.
