# DropForge · installeurs

Studio de **drops DJ** : tu écris ton texte, tu choisis un style, et DropForge
crée un drop prêt à jouer (voix, effets, sons FX, beat) à télécharger en MP3 ou WAV.

Ce dépôt contient uniquement les installeurs de DropForge (le code de l'outil est privé).

## Télécharger

👉 **[Dernière version](https://github.com/Fulberitodesign/dropforge-releases/releases/latest)**

- Windows : [`DropForge-Setup.exe`](https://github.com/Fulberitodesign/dropforge-releases/releases/latest/download/DropForge-Setup.exe)
- Mac : [`DropForge-Setup.dmg`](https://github.com/Fulberitodesign/dropforge-releases/releases/latest/download/DropForge-Setup.dmg)

## Installer

1. Télécharge l'installeur et lance-le. Une icône **DropForge** apparaît sur le Bureau.
2. L'appli n'est pas signée :
   - **Windows** : si « Windows a protégé votre ordinateur » s'affiche, clique
     **Informations complémentaires** puis **Exécuter quand même**.
   - **Mac** : fais un clic droit sur DropForge dans Applications → **Ouvrir** → **Ouvrir**.
     Si le Mac dit que l'appli est « endommagée », ouvre le Terminal et tape :
     `xattr -cr /Applications/DropForge.app` puis relance DropForge.

## Utiliser

1. Clique sur **⚙️** (en haut à droite) et choisis ta voix :
   - **Voix Windows** : gratuites, illimitées, sans Internet, rien à configurer.
   - **Gemini (gratuit)** : crée une clé sur
     [aistudio.google.com/apikey](https://aistudio.google.com/apikey) et colle-la dans DropForge.
   - **ElevenLabs / OpenAI** (payants, optionnels) : colle ta clé API.
2. Choisis un **style**, écris ton texte (ou prends un **template**).
3. Clique **GÉNÉRER LE DROP**, écoute, puis **⬇ MP3**.

Les clés API restent sur ton ordinateur et ne sont envoyées qu'au service de voix choisi.
