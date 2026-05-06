# Formation Developeur IA - Projet-4 - ModeTrends

**Formation Développeur IA - OpenClassrooms**

## 📝 Description

Ce projet consiste à intégrer des services d'Intelligence Artificielle via API pour l'application **ModeTrends**. L'objectif principal est de réaliser la segmentation d'images de vêtements en utilisant le modèle `segformer_b3_clothes` hébergé sur Hugging Face.

## 🛠️ Installation

### 1. Cloner le projet

```bash
git clone https://github.com/techerpierre/Formation-Developeur-IA--Projet-4--ModeTrends
cd Formation-Developeur-IA--Projet-4--ModeTrends
```

### 2. Créer l'environnement virtuel

Il est recommandé d'utiliser un environnement virtuel pour isoler les dépendances du projet.

```bash
pyrhon -m venv .venv
```

### 3. Activer l'environnement virtuel

- **Windows:**
    ```bash
    .venv\Scripts\activate
    ```

- **macOS / Linux:**
    ```bash
    source .venv/bin/activate
    ```

### 4. Installer les dépendances

```
pip install -r requirements.txt
```

## ⚙️ Configuration

Avant de lancer les scripts, vous devez configurer votre jeton d'accès (token) Hugging Face ainsi que ainsi que l'endpoint de l'API:

1. Créez un fichier `.env` à la racine du projet.
2. Ajoutez les variabes d'environements :
    ```bash
    HUGGING_FACE_ACCESS_TOKEN=votre_token_ici
    HUGGING_FACE_API_URL=endpoint_ici
    ```

**Toute les variabes d'environement sont décrites dans le fichier `.env.example`.**
**On y trouve également le endpoint de l'API**

## 🚀 Utilisation

Le code pour la segmentation d'images se trouve dans `src/image_segmentation.ipynb`.

## 📦 Gestion des dépendances

Si vous installez de nouvelles bibliothèques, n'oubliez pas de mettre à jour le fichier `requirements.txt`:

```bash
pip freeze > requirements.txt
```
