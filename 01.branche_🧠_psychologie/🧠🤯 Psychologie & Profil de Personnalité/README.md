# 🧠🤯 Psychologie & Profil de Personnalité — README.md (installation ultra-simple)

Objectif : créer le Projet ChatGPT du module, déposer les PDF dans Files, puis coller le métaprompt dans Modifier les instructions. Durée : 2–3 minutes.

## 0) Ce qu’il te faut sous la main

- Le métaprompt : `metaprompt_psychologie_FR.md` (dans ce dossier)
- Les PDF du module (téléchargeables depuis ce dossier GitHub) :
  - `🧠 🤯 Psychologie & Profil de Personnalité - Catalogue de jeux.pdf`
  - `🧠 🤯 Psychologie & Profil de Personnalité - Catalogue de fonctions.pdf`
  - `🧠 🤯 Psychologie & Profil de Personnalité - Guide de Lancement.pdf` (optionnel pour l’utilisateur)

_Remarque : les noms exacts peuvent contenir des espaces. Peu importe : uploade-les tels quels dans le Projet ChatGPT._

## 1) Créer le Projet ChatGPT

1. Ouvre ChatGPT → Projects (Projets)
2. Clique New project → nomme-le : `Olympus – Psychologie`
3. (optionnel) Langue : Français
4. Le projet est créé : tu vois les onglets Chat, Files, etc.

## 2) Déposer les PDF dans Files

1. Ouvre l’onglet Files du projet
2. Clique Upload (ou glisse-dépose) les PDF du module :
   - `🧠 🤯 Psychologie & Profil de Personnalité - Catalogue de jeux.pdf`
   - `🧠 🤯 Psychologie & Profil de Personnalité - Catalogue de fonctions.pdf`
   - `🧠 🤯 Psychologie & Profil de Personnalité - Guide de Lancement.pdf`
3. Attends la fin d’upload puis vérifie que les 2 catalogues apparaissent bien dans Files
   - Ces deux fichiers sont indispensables : le guide d’installation les prévoit explicitement `oai_citation:1‡🧠 🤯 Psychologie & Profil de Personnalité - Guide de Lancement.pdf`.

## 3) Coller le métaprompt dans Modifier les instructions

1. Reviens sur ce dépôt GitHub → ouvre `metaprompt_psychologie_FR.md`
2. Clique Raw (Brut) → Cmd/Ctrl+A → Cmd/Ctrl+C
3. Retourne dans ton Projet ChatGPT → en haut à droite ⋯ (trois points) → Modifier les instructions
4. Colle l’intégralité du texte dans le champ (remplace tout le contenu s’il y en a)
5. Clique Save / Enregistrer

_Important : c’est ici que vit la logique du module (métaprompt). Les fichiers PDF restent dans Files et sont chargés par l’IA pendant l’exécution, comme prévu dans ton guide `oai_citation:2‡🧠 🤯 Psychologie & Profil de Personnalité - Guide de Lancement.pdf`._

## 4) Lancer le module (calibration auto)

1. Va dans l’onglet Chat du projet
2. Envoie un simple message (“Bonjour” suffit) → Le test de calibration démarre automatiquement au premier message, conformément au guide `oai_citation:3‡🧠 🤯 Psychologie & Profil de Personnalité - Guide de Lancement.pdf`.
3. Si la calibration ne se lance pas (rare), envoie la commande : `/jeu`

## 5) Raccourcis utiles (à garder)

- Relancer le guide : `/guide`
- Passer à l’action immédiate : `/OMG` (fonction momentum, décrite dans le guide `oai_citation:4‡🧠 🤯 Psychologie & Profil de Personnalité - Guide de Lancement.pdf`)
- Catalogues : ils sont déjà dans Files (jeux + fonctions). Pas besoin d’y retoucher.

## 6) Mises à jour (UI qui change)

- L’emplacement ⋯ → Modifier les instructions peut bouger (l’UI a changé récemment)
- Règle d’or : cherche toujours le menu “projet” en haut à droite ; colle le métaprompt dans le champ d’instructions du projet puis Enregistrer
- Si tu remplaces un PDF (nouvelle version), ré-uploade simplement dans Files (même nom ou nouveau nom)

## 7) Dépannage minute

- Je ne vois pas mes PDF : retourne dans Files du projet et recharge la page ; si besoin, ré-uploade
- La calibration ne part pas : envoie `/jeu`
- L’IA n’utilise pas les catalogues : vérifie qu’ils sont bien présents dans Files du projet (pas seulement sur GitHub)

## 8) Où trouver les fichiers sur GitHub (si l’utilisateur veut les récupérer)

- Métaprompt (Markdown) : `./metaprompt_psychologie_FR.md`
- PDF (catalogues & guide) : dans ce même dossier

Bon décollage 🚀
