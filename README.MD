# 🎤 Parler TTS Web Application

Bienvenue sur **Parler TTS Web Application** ! 🎉

Ce projet est un site web qui permet aux utilisateurs de générer de la voix à partir de texte (Text-to-Speech) en anglais uniquement, avec la possibilité de choisir le type de voix (masculine ou féminine). 🗣️

## 📝 Description du Projet

Cette application web offre une interface simple et conviviale pour convertir du texte en parole en anglais. Les utilisateurs peuvent :

- Entrer le texte qu'ils souhaitent convertir en audio.
- Choisir entre une voix masculine ou féminine.
- Écouter l'audio généré directement depuis le navigateur.

## 🚀 Démarrage Rapide

Suivez les étapes ci-dessous pour lancer le projet en local.

### Prérequis

- **Python 3.7+** avec un environnement virtuel configuré (`parler_env`).
- **Node.js** et **npm** installés sur votre machine.

### ⚙️ Installation

1. **Cloner le dépôt du projet**.

2. **Configurer l'API Python** :

   ```bash
   cd parler_api
   ```

   - Activer l'environnement virtuel :

     ```bash
     .\parler_env\Scripts\activate
     ```

   - Installer les dépendances requises :

     ```bash
     pip install -r requirements.txt
     ```

3. **Configurer le Frontend JavaScript** :

   ```bash
   cd parler_front
   ```

   - Installer les dépendances :

     ```bash
     npm install
     ```

### 💻 Lancer l'Application

**Terminal 1 (API Python)** :

```bash
cd parler_api
.\parler_env\Scripts\activate
uvicorn main:app --host 0.0.0.0 --port 8000
```

**Terminal 2 (Frontend JavaScript)** :

```bash
cd parler_front
npm run dev
```

## 📌 Utilisation

- Ouvrez votre navigateur et accédez à `http://localhost:3000`.
- Entrez le texte en anglais que vous souhaitez convertir en audio.
- Sélectionnez le type de voix (masculine ou féminine).
- Cliquez sur **Valider** et attendez que l'audio soit généré et lu.

## ⚠️ Problèmes Connus

- **Temps de Génération** : Le temps de génération de l'audio est actuellement d'au moins **2 minutes** ⏳. Nous travaillons à optimiser les performances pour réduire ce délai. Ce temps peut être plus court si vous possedez un GPU.

## 📞 Support

Si vous rencontrez des problèmes ou avez des questions, n'hésitez pas à ouvrir une issue ou à nous contacter directement. 🤝

## 🛠️ Technologies Utilisées

- **Python** avec **FastAPI** pour l'API backend.
- **Parler TTS** pour la génération de la voix.
- **Node.js** et **Next.js** pour le frontend.
- **Tailwind CSS** pour le style.
- **TypeScript** pour une meilleure qualité de code.

---

Merci d'utiliser **Parler TTS Web Application** ! Nous espérons que vous apprécierez cette application. 🙌