<div align="center">
  <img src="https://image.noelshack.com/fichiers/2026/39/6/1790421074-appicon.png" alt="Logo Cahka" width="128"/>
  <h1>Cahka</h1>
</div>

Cahka est une interface graphique (GUI) macOS pour `yt-dlp` et `ffmpeg`. Elle permet de télécharger des médias et de les importer directement dans un projet de montage, sans avoir à utiliser le terminal.

## Fonctionnalités

* Téléchargement de vidéos (de la 4K à la 720p) et extraction audio (MP3).
* Définition d'un dossier de destination personnalisé.
* Importation automatique du fichier téléchargé dans l'onglet "Projet" d'Adobe Premiere Pro.

## Installation

Cahka est compatible uniquement avec macOS.

| Fichier | Description |
|---------|-------------|
| `Cahka.app.zip` | Application macOS (Compatible Apple Silicon & Intel). |

1. Téléchargez la dernière version dans l'onglet [Releases](lien-vers-releases).
2. Décompressez l'archive téléchargée.
3. Déplacez le fichier `Cahka.app` dans votre dossier **Applications**.

## Fonctionnement technique

L'application est autonome et intègre directement les outils nécessaires sous le capot. Aucune installation manuelle de paquets n'est requise :

* **yt-dlp** : pour la récupération des flux vidéo et audio.
* **ffmpeg** : pour l'assemblage (multiplexage) des formats haute résolution et l'encodage MP3.

*Note : Pour que l'importation directe fonctionne, Adobe Premiere Pro doit être en cours d'exécution sur votre machine.*

---

**À propos de ce projet**
L'intégralité de cette application (code, interface et documentation) a été conçue et développée de A à Z par Intelligence Artificielle.
