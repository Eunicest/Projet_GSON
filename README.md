# 🎙️ Analyse de Données Langagières et Vocaux (Projet GSON)

## 🎯 Résultats Clés
*(Pour le détail de l'analyse, consultez le rapport : `GSON.pdf`)*

- **Comparaison Humain vs Automatique :** L'étude de 3 vocaux du corpus *Les Vocaux* (projet ORALIDIA) montre que l'outil d'IA *Whisper* fournit des transcriptions globalement stables, propres et syntaxiquement cohérentes.
- **Le Lissage de l'Oral par l'IA :** Whisper a tendance à normaliser la parole spontanée en gommant systématiquement les hésitations (les "euh"), les tics de langage et les amorces de mots interrompus.
- **Limites et Erreurs Critiques :** Le modèle génère parfois des "hallucinations" (mots ou phrases inventés), omet de vrais lemmes prononcés, et rate les bips sonores d'anonymisation, confirmant qu'une relecture humaine reste indispensable.

---

## 📝 Contexte du projet
Projet réalisé dans le cadre du module **"Data Sciences et Langage"** de la Graduate School Orléans Numérique (GSON), Master 2 Mathématiques Appliquées et Statistiques à l'Université d'Orléans (2025-2026).  
L'objectif est d'articuler les méthodes de la science des données avec l'analyse linguistique en comparant une segmentation manuelle sous le logiciel *Praat* et une segmentation automatique via l'outil *Whisper*.

Le projet s'articule autour de :
1. **Constitution et Analyse d'un corpus :** Étude de 3 vocaux contrastés issus du corpus *Les Vocaux* (version 0.0.2).
2. **Segmentation manuelle :** Écoute, harmonisation en binôme et découpage fondé sur les unités syntaxiques et prosodiques.
3. **Évaluation de Whisper :** Identification des écarts, omissions, hallucinations et gestion des tics de langage.

### 🛠️ Outils et Technologies
- **Environnement & Outils :** Python / IA de transcription, Logiciel Praat (analyse acoustique et segmentation)
- **Méthodes :** Traitement automatique du langage naturel (TALN), transcription comparative, analyse qualitative
- **Données :** Corpus *Les Vocaux* (projet ORALIDIA)

### 📂 Structure du dépôt
- 📄 `GSON.pdf` : Le rapport final complet du projet.

> ⚠️ **Note sur les données :** Les fichiers audio originaux du corpus *Les Vocaux* ne sont pas inclus dans ce dépôt pour des raisons de confidentialité et de respect des consentements.

---
<br>

<details>
<summary>🇬🇧 <b>English version (Click to expand)</b></summary>

## 🎯 Key Results
*(For the full analysis, read the report: `GSON.pdf`)*

- **Human vs. Automatic Comparison:** Analyzing 3 voice messages from *Les Vocaux* corpus (ORALIDIA project) shows that the AI tool *Whisper* delivers overall stable, clean, and syntactically coherent transcriptions.
- **Spontaneous Speech "Smoothing":** Whisper tends to normalize speech by systematically erasing hesitations ("uh/euh"), verbal tics, and cut-off words.
- **Limitations & Critical Errors:** The model occasionally generates "hallucinations" (invented words or phrases), omits spoken lemmas, and fails to handle anonymization audio beeps, confirming that human proofreading remains essential.

---

## 📝 Project Context
Project carried out as part of the **"Data Sciences and Language"** module for the Graduate School Orléans Numérique (GSON) program, 2nd year Master's in Applied Mathematics and Statistics at the University of Orléans (2025-2026).  
The objective is to bridge data science methods with linguistic analysis by comparing manual segmentation using *Praat* with automatic segmentation via *Whisper*.

### 🛠️ Tools and Technologies
- **Environment & Tools:** Speech transcription AI, Praat software (acoustic analysis & segmentation)
- **Methods:** Natural Language Processing (NLP), comparative transcription, qualitative analysis
- **Dataset:** *Les Vocaux* corpus (ORALIDIA project)

### 📂 Repository Structure
- 📄 `GSON.pdf`: The complete final project report.
</details>