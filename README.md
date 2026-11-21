# ⚛️ Physics Study OS (L1)

> **Tableau de bord de suivi d'études en physique (1ère année / L1)**, optimisé pour être hébergé gratuitement en 1 minute sur **GitHub Pages**.

![Status](https://img.shields.io/badge/Status-Vierge%20%26%20Pr%C3%AAt-cyan?style=for-the-badge)
![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-blue?style=for-the-badge&logo=github)
![Tech](https://img.shields.io/badge/Stack-HTML5%20%7C%20TailwindCSS%20%7C%20Vanilla%20JS-0891b2?style=for-the-badge)

---

## 🎨 Identité Visuelle & Ergonomie

- **Thème Sombre Cosmique Glassmorphism** : Fond profond bleuté (`#070a12`, `#0d1322`), panneaux en verre dépoli translucide avec flou d'arrière-plan (`backdrop-filter: blur(14px)`), halos lumineux aux accents quantiques.
- **Espace 100% Vierge & Personnalisable** : Les 6 modules sont initialisés sans chapitres pré-remplis pour permettre à l'étudiante d'organiser ses révisions et ses cours exactement selon son programme universitaire.
- **Raccourci Clavier `Ctrl + K`** : Barre de recherche instantanée pour retrouver un chapitre, une formule, une note de TP ou une date de partiel.

---

## 📐 Les 6 Modules au Programme

Chaque matière affiche **strictement** les sections qui lui sont autorisées (aucune section inutile n'est affichée) :

| Module | Code | Sections Autorisées | Rendu dynamique | Thème Couleur |
| :--- | :--- | :--- | :--- | :--- |
| **Mécanique** | `MECA` | `Cours`, `TD`, `TP` | Grille **3 colonnes** (`Cours` + `TD` + `TP`) | Ambre / Énergie |
| **Structure of matter** | `MATTER` | `Cours`, `TD`, `TP` | Grille **3 colonnes** (`Cours` + `TD` + `TP`) | Cyan / Quantique |
| **Analysis** | `MATH` | `Cours`, `TD` | Grille **2 colonnes** (`Cours` + `TD`) | Indigo / Mathématiques |
| **History of science** | `HIST` | `Cours` | Grille **1 colonne** (`Cours` seul) | Émeraude / Histoire |
| **English** | `ENG` | `Cours` | Grille **1 colonne** (`Cours` seul) | Rose / Langues |
| **ICT** *(Info & Comm. Tech)* | `ICT` | `Cours` | Grille **1 colonne** (`Cours` seul) | Fuchsia / Informatique |

---

## 🚀 Fonctionnalités Clés

1. **Création Dynamique de Chapitres** :
   - Cliquez sur **`+ Nouveau Chapitre`** dans n'importe quelle matière.
   - Les sous-fenêtres correspondantes (`Cours`, `TD`, `TP`) sont générées instantanément.
   - Cliquez sur le titre du chapitre pour le renommer à tout moment.

2. **Sous-Tâches & Notes de Révision** :
   - **Notes intégrées** : Notez les formules indispensables, théorèmes, constantes physiques ou consignes d'enseignants.
   - **Ajout rapide** : Tapez votre sous-tâche et validez avec `Entrée`.
   - **Édition en direct** : Cliquez sur le texte d'une tâche pour corriger son libellé.

3. **Deadlines & To-Do List Spécifique Sciences** :
   - Catégories adaptées : *Compte-Rendu de TP (CR TP)*, *Examen / Partiel*, *Contrôle Continu TD*, *Devoir Maison (DM)*.
   - Badges de compte à rebours dynamique (*"Aujourd'hui !"*, *"Demain"*, *"Dans 4j"*, *"En retard"*).
   - Bouton **"Nettoyer terminées"** pour vider en 1 clic les devoirs déjà rendus.

4. **Sauvegarde & Synchronisation Sécurisée** :
   - Clé `localStorage` indépendante (`physics_study_os_v1_data`) : ne rentre jamais en conflit avec d'autres dashboards.
   - Boutons **"Exporter"** et **"Importer"** JSON pour faire des sauvegardes régulières.

---

## 🌐 Déploiement sur GitHub Pages (Guide en 3 étapes)

Le fichier `index.html` est 100% autonome et ne nécessite aucune compilation.

### Étape 1 : Créer le dépôt GitHub
1. Connectez-vous sur [GitHub](https://github.com).
2. Créez un nouveau dépôt public (ex: `physics-study-os`).

### Étape 2 : Uploader les fichiers
Dans le terminal du dossier `physics-study-os` (ou par glisser-déposer sur GitHub) :
```bash
git init
git add index.html README.md
git commit -m "feat: initial commit Physics Study OS"
git branch -M main
git remote add origin https://github.com/<PSEUDO>/physics-study-os.git
git push -u origin main
```

### Étape 3 : Activer GitHub Pages
1. Dans le dépôt, allez dans **Settings** > **Pages**.
2. Sous **Build and deployment**, choisissez **Source** : `Deploy from a branch`.
3. Sélectionnez la branche `main` et le dossier `/ (root)`, puis cliquez sur **Save**.
4. Le site sera disponible en ligne sur :
   ```
   https://<PSEUDO>.github.io/physics-study-os/
   ```
