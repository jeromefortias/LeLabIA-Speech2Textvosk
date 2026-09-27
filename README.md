# LeLabIA - Reconnaissance Vocale (Vosk) & Connexion à un LLM 🎙️🤖

Bienvenue dans le dépôt officiel du tutoriel **LeLabIA** consacré à la mise en place d'un système de reconnaissance vocale en local avec **Vosk** et sa connexion à un Modèle de Langage (LLM).

---

## 📺 Tutoriel Vidéo

Découvrez l'explication complète et le pas-à-pas dans la vidéo :

[![Reconnaissance vocale Vosk (+ connexion à un LLM)](https://img.youtube.com/vi/6mqEe5x867s/maxresdefault.jpg)](https://www.youtube.com/watch?v=6mqEe5x867s "Regarder la vidéo sur YouTube")

> 💡 *Cliquez sur l'image ci-dessus pour lancer la vidéo sur YouTube.*

---

## 📋 Aperçu du Projet

Dans ce projet, nous voyons comment :
1. **Capturer le flux audio** du microphone en Python.
2. **Transcrire l'audio localement avec Vosk** (Speech-to-Text rapide et hors-ligne).
3. **Envoyer la transcription à un LLM** pour générer une réponse.
4. **Traiter le retour** sous forme de texte ou de voix.

---

## 🚀 Prérequis et Installation

### Prérequis

- **Python** 3.10 ou supérieur
- Un microphone fonctionnel
- Un modèle Vosk (ex: modèle français `vosk-model-fr-0.22` ou `vosk-model-small-fr-0.22`)

### Installation

1. **Cloner le dépôt**
   ```bash
   git clone https://github.com/jeromefortias/LeLabIA-Speech2Textvosk.git
   cd LeLabIA-Speech2Textvosk
   ```

2. **Créer et activer un environnement virtuel**
   ```bash
   python -m venv venv
   # Sur Linux/macOS :
   source venv/bin/activate  
   # Sur Windows :
   .\venv\Scripts\activate   
   ```

3. **Installer les dépendances**
   ```bash
   pip install -r requirements.txt
   ```

4. **Télécharger le modèle Vosk**
   Téléchargez un modèle adapté depuis le site officiel de Vosk et extrayez-le à la racine du projet dans un dossier nommé `model`.

---

## 🛠️ Utilisation

Lancez le script principal pour démarrer l'écoute vocale :

```bash
python main.py
```

---

## 👥 Auteur & Liens

- **Vidéo Youtube** : [Reconnaissance vocale (+ connexion à un LLM)](https://www.youtube.com/watch?v=6mqEe5x867s)
- **Chaîne YouTube** : [Le Lab IA](https://www.youtube.com/@lelabia)
- **GitHub** : [@jeromefortias](https://github.com/jeromefortias)

---

⭐ N'hésitez pas à ajouter une étoile au dépôt si ce tutoriel vous a été utile !# sources
