Voici le contenu complet prêt à être collé dans ton fichier `README.md` à la racine du projet GitHub 👇

---

```markdown
# 🎓 Gestion et Suivi des Absences à ISM

## 👨‍🏫 Projet Encadré – Équipe ISM

Ce projet vise à développer une application **Web et Mobile** permettant la **gestion et le suivi des absences des étudiants à l’ISM**. Il implique plusieurs acteurs (vigile, étudiant, administrateur) et repose sur une architecture complète **Frontend Angular + Flutter + Backend Spring Boot**.

---

## 👋 Présentation du Chef de Projet

Ce travail est supervisé par **Baila Wane**, notre **Project Manager**, qui est chargé de coordonner les tâches, valider les pull requests et s'assurer de la bonne progression du projet dans le respect des exigences fonctionnelles et techniques.

---

## 🧑‍💻 Équipe & Répartition des Rôles

| Membre          | Rôle                            | Branche Git         | Dossier Projet             |
|------------------|----------------------------------|-----------------------|-----------------------------|
| **Patrick**        | Développeur Frontend (Angular)   | `dev/patrick`        | `/frontend-angular/`       |
| **Pinhas**         | Développeur Frontend (Angular)   | `dev/pinhas`         | `/frontend-angular/`       |
| **Babacar**        | Développeur Mobile (Flutter)     | `dev/babacar`        | `/frontend-flutter/`       |
| **MameDiarra**     | Développeuse Mobile (Flutter)    | `dev/mamediarra`     | `/frontend-flutter/`       |
| **Exauce Amour**   | Développeur Backend (Spring Boot)| `dev/exauce`         | `/backend-spring/`         |
| **Sydney**         | UX/UI Designer et Backend        | `dev/sydney`         | `/docs/`, `/backend-spring/` |
| **Salimatou**      | Développeuse Backend             | `dev/salimatou`      | `/backend-spring/`         |

---

## 📁 Structure du Dépôt

```

gestion-absences-ism/
├── backend-spring/        ← Backend Java Spring Boot
├── frontend-angular/      ← Application Web Angular (Admin, Étudiant)
├── frontend-flutter/      ← Application Mobile Flutter (Vigile, Étudiant)
├── docs/                  ← Diagrammes UML, maquettes Figma, charte ISM
└── README.md              ← Guide de collaboration (ce fichier)

````

---

## 🔄 Workflow Git – Guide de Collaboration

### 🔁 1. Cloner le Dépôt

```bash
git clone https://github.com/ton-user/gestion-absences-ism.git
cd gestion-absences-ism
````

---

### 🌿 2. Se placer sur sa branche personnelle

```bash
git checkout dev/mon_prenom
```

📌 Exemples :

```bash
git checkout dev/patrick
git checkout dev/salimatou
```

---

### ✍️ 3. Faire ses modifications

Travaillez uniquement dans votre dossier de projet :

* `/frontend-angular/` pour Angular
* `/frontend-flutter/` pour Flutter
* `/backend-spring/` pour Spring Boot

---

### 💾 4. Ajouter et valider ses changements

```bash
git add .
git commit -m "Ajout du composant login admin"
```

---

### 🚀 5. Pousser vers votre branche distante

```bash
git push origin dev/mon_prenom
```

---

### 🔃 6. Créer une Pull Request

Quand votre fonctionnalité est terminée :

1. Aller sur [le dépôt GitHub](https://github.com/ton-user/gestion-absences-ism)
2. Cliquer sur **"Compare & pull request"**
3. Rédiger un **titre clair** et une **description courte**
4. Choisir comme base : `main`
5. Créer la PR pour que **Baila Wane** puisse valider

---

## ✅ Exemple de Pull Request

**Titre :** Intégration du module de justification
**Description :** Composants Angular pour justifier une absence + service d’appel API.

---

## 📌 Bonnes Pratiques

* Ne pas travailler sur `main` directement
* Travailler dans **votre branche uniquement**
* Toujours faire `git pull origin dev/mon_prenom` avant de commencer
* Des commits fréquents avec des messages clairs
* Créer une pull request dès qu’un bloc est prêt

---

## 🗂 Planning et Répartition

* **Diagrammes UML** : Salimatou, Pinhas, MameDiarra
* **Maquettes UI/UX sur Figma** : Sydney
* **Initialisation Backend Spring** : Exauce
* **Initialisation Frontend Angular** : Patrick
* **Initialisation Mobile Flutter** : Babacar
* **Supervision** : Baila Wane

---

## 🧠 Objectif

Créer une application cohérente, responsive, modulaire, et fluide pour ISM. Chacun est responsable de sa partie, mais le succès est collectif 💪

---

```

