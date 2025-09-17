# 🧠🤯 Psychologie & Profil de Personnalité — README.md (installation ultra-simple)

Objectif : créer le Projet ChatGPT du module, déposer les PDF et JSON dans Files, puis coller le métaprompt dans Modifier les instructions. Durée : 2–3 minutes.

## 0) Ce qu’il te faut sous la main

- Le métaprompt : `metaprompt_psychologie_FR.md` (dans ce dossier)
- Les fichiers du module (téléchargeables depuis ce dossier GitHub) :
  - `🧠 🤯 Psychologie & Profil de Personnalité - Catalogue de jeux.pdf`
  - `🧠 🤯 Psychologie & Profil de Personnalité - Catalogue de fonctions.pdf`
  - `🧠 🤯 Psychologie & Profil de Personnalité - Guide de Lancement.pdf` (optionnel pour l’utilisateur)
  - `catalogue_jeux.json` (version JSON enrichie avec le Voyage Intérieur)
  - `catalogue_fonctions.json` (version JSON multilingue)

_Remarque : les noms exacts peuvent contenir des espaces. Peu importe : uploade-les tels quels dans le Projet ChatGPT._

## 1) Créer le Projet ChatGPT

1. Ouvre ChatGPT → Projects (Projets)
2. Clique New project → nomme-le : `Olympus – Psychologie`
3. (optionnel) Langue : Français
4. Le projet est créé : tu vois les onglets Chat, Files, etc.

## 2) Déposer les fichiers dans Files

1. Ouvre l’onglet Files du projet
2. Clique Upload (ou glisse-dépose) les fichiers PDF et JSON du module :
   - `🧠 🤯 Psychologie & Profil de Personnalité - Catalogue de jeux.pdf`
   - `🧠 🤯 Psychologie & Profil de Personnalité - Catalogue de fonctions.pdf`
   - `🧠 🤯 Psychologie & Profil de Personnalité - Guide de Lancement.pdf`
   - `catalogue_jeux.json`
   - `catalogue_fonctions.json`
3. Attends la fin d’upload puis vérifie que tous les fichiers apparaissent bien dans Files
   - Ces fichiers sont indispensables : le guide d’installation prévoit explicitement que l’IA charge les JSON et PDF en mémoire.

## 3) Coller le métaprompt dans Modifier les instructions

1. Reviens sur ce dépôt GitHub → ouvre `metaprompt_psychologie_FR.md`
2. Clique Raw (Brut) → Cmd/Ctrl+A → Cmd/Ctrl+C
3. Retourne dans ton Projet ChatGPT → en haut à droite ⋯ (trois points) → Modifier les instructions
4. Colle l’intégralité du texte dans le champ (remplace tout le contenu s’il y en a)
5. Clique Save / Enregistrer

_Important : c’est ici que vit la logique du module (métaprompt). Les fichiers PDF et JSON restent dans Files et sont chargés par l’IA pendant l’exécution, comme prévu dans ton guide._

## 4) Lancer le module (calibration auto)

1. Va dans l’onglet Chat du projet
2. Envoie un simple message (“Bonjour” suffit) → Le test de calibration démarre automatiquement au premier message, conformément au guide.
3. Si la calibration ne se lance pas (rare), envoie la commande : `/jeu`

## 5) Raccourcis utiles (à garder)

- Relancer le guide : `/guide`
- Passer à l’action immédiate : `/OMG`
- Catalogues : ils sont déjà dans Files (PDF et JSON). Pas besoin d’y retoucher.

## 6) Mises à jour (UI qui change)

- L’emplacement ⋯ → Modifier les instructions peut bouger
- Règle d’or : colle le métaprompt dans le champ d’instructions du projet puis Enregistrer
- Si tu remplaces un PDF ou JSON (nouvelle version), ré-uploade simplement dans Files (même nom ou nouveau nom)

## 7) Dépannage minute

- Je ne vois pas mes fichiers : retourne dans Files du projet et recharge la page ; si besoin, ré-uploade
- La calibration ne part pas : envoie `/jeu`
- L’IA n’utilise pas les catalogues : vérifie qu’ils sont bien présents dans Files du projet (pas seulement sur GitHub)

## 8) Où trouver les fichiers sur GitHub (si l’utilisateur veut les récupérer)

- Métaprompt (Markdown) : `./metaprompt_psychologie_FR.md`
- PDF et JSON (catalogues & guide) : dans ce même dossier

Bon décollage 🚀
