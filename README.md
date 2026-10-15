# 🎙️ Analyse de Données Langagières et Vocaux (Projet GSON)

## 🎯 Résultats clés

*(Détail de l'analyse : [`GSON.pdf`](GSON.pdf))*

Étude de **3 vocaux** du corpus *Les Vocaux* (projet ORALIDIA), réalisée **en binôme** :

- **Humain vs automatique :** sur ces 3 vocaux, *Whisper* fournit des transcriptions globalement stables, propres et syntaxiquement cohérentes.
- **Lissage de l'oral :** Whisper tend à normaliser la parole spontanée en gommant les hésitations (« euh »), les tics de langage et les amorces de mots interrompus.
- **Erreurs critiques :** le modèle produit parfois des « hallucinations » (mots ou phrases inventés), omet des mots réellement prononcés et ne gère pas les bips d'anonymisation. Une relecture humaine reste indispensable.


---

## 📝 Contexte du projet

Module **« Data Sciences et Langage »** de la Graduate School Orléans Numérique (GSON), Master 2 Mathématiques Appliquées et Statistiques, Université d'Orléans (2025-2026).
Objectif : relier science des données et analyse linguistique en comparant une segmentation manuelle sous *Praat* et une segmentation automatique avec *Whisper*.

1. **Constitution du corpus :** 3 vocaux contrastés de *Les Vocaux* (version 0.0.2).
2. **Segmentation manuelle :** écoute, harmonisation en binôme et découpage selon les unités syntaxiques et prosodiques.
3. **Évaluation de Whisper :** identification des écarts, omissions, hallucinations et traitement des tics de langage.

### 🛠️ Outils et technologies
- **Outils :** Praat (analyse acoustique et segmentation), Whisper [modèle et version utilisés non précisée]
- **Méthodes :** traitement automatique du langage, transcription comparative, analyse qualitative
- **Données :** corpus *Les Vocaux* (projet ORALIDIA)

### 📂 Contenu du dépôt
- 📄 [`GSON.pdf`](GSON.pdf) : rapport final.

> ⚠️ **Données :** les fichiers audio ne sont pas inclus, pour des raisons de confidentialité et de respect des consentements.

---

## ⚠️ Limites et pistes d'amélioration

**Limites**
- Échantillon de seulement 3 vocaux : les conclusions ne se généralisent pas.
- Analyse surtout qualitative.
- Dépôt limité au rapport : pas de code ni de données.

**Pistes d'amélioration** : élargir le corpus, mesurer un taux d'erreur de mots (WER) entre transcription manuelle et Whisper


---

<details>
<summary>🇬🇧 <b>English version</b></summary>

# 🎙️ Linguistic and Voice Data Analysis (GSON Project)

## 🎯 Key results

*(Full analysis: [`GSON.pdf`](GSON.pdf))*

Study of **3 voice messages** from the *Les Vocaux* corpus (ORALIDIA project), done **in pairs**:

- **Human vs automatic:** on these 3 messages, *Whisper* gives overall stable, clean and syntactically coherent transcriptions.
- **Smoothing of speech:** Whisper tends to normalize spontaneous speech by erasing hesitations ("uh"), verbal tics and cut-off words.
- **Critical errors:** the model sometimes "hallucinates" (invented words or phrases), omits spoken words and misses anonymization beeps. Human proofreading remains essential.

## 📝 Project context

"Data Sciences and Language" module, Graduate School Orléans Numérique (GSON), 2nd year Master's in Applied Mathematics and Statistics, University of Orléans (2025-2026).
Goal: bridge data science and linguistic analysis by comparing manual segmentation in *Praat* with automatic segmentation using *Whisper*.

### 🛠️ Tools
- **Tools:** Praat, Whisper [model and version non specified]
- **Methods:** natural language processing, comparative transcription, qualitative analysis
- **Data:** *Les Vocaux* corpus (ORALIDIA project)

### 📂 Repository content
- 📄 [`GSON.pdf`](GSON.pdf): final report.

> ⚠️ **Data:** audio files are not included, for confidentiality and consent reasons.

## ⚠️ Limitations and improvements

**Limitations**
- Only 3 voice messages: conclusions do not generalize.
- Mostly qualitative analysis.
- The repository only contains the report: no code or data.

**Possible improvements**: larger corpus, word error rate (WER) between manual transcription and Whisper



</details>
