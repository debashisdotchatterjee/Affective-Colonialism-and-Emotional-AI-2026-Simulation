# Affective-Colonialism-and-Emotional-AI-2026-Simulation

# Affective Colonialism and Emotional AI 2026 — Synthetic Demonstration Dataset

This repository contains a **synthetic dataset only** for demonstrating a proposed statistical and machine-learning framework for the project:

**Affective Colonialism and Emotional AI: A Study of Human--Algorithm Affective Drift through Poems of Tagore and Wordsworth**

The dataset is provided strictly for **methodological demonstration, reproducibility checking, and pipeline illustration**. It is not an empirical dataset.

## Important Disclaimer

The dataset in this repository is **entirely synthetic**.

It was **not generated from actual poems of Rabindranath Tagore or William Wordsworth**.
It was **not generated from real human participants**.
It was **not generated from real AI model responses**.
It does **not contain any actual textual response, copyrighted literary text, interview material, participant data, or real AI audit output**.

The synthetic scenarios were deliberately constructed to demonstrate how the proposed statistical pipeline can represent, visualise, and analyse different possible forms of affective drift. Therefore, the results obtained from this dataset must **not** be interpreted as evidence about:

* Rabindranath Tagore,
* William Wordsworth,
* human readers,
* Claude, DeepSeek, Llama, GPT, or any other actual AI system,
* affective colonialism,
* AI flattening,
* cultural drift,
* or model-specific instability.

The only valid conclusion from this dataset is methodological: it shows how the proposed analytical framework may be implemented once real human-response and AI-response data are generated during the actual project.

## Purpose of the Dataset

The synthetic dataset was created to demonstrate the following components of the proposed methodology:

1. construction of multidimensional affective-response vectors;
2. representation of lexical, syntactic, affective, embedding-based and Rasa/Bhava-oriented features;
3. baseline-referenced affective drift measurement;
4. computation of the Affective Drift Index;
5. comparison of synthetic human-like and AI-like response trajectories;
6. visualisation of response drift over ordered exposure checkpoints;
7. illustration of statistical modelling and distance-based testing strategies.

## Dataset Design

The synthetic design imitates the structure of the proposed project.

The simulated conditions include:

* two literary traditions:

  * Tagore,
  * Wordsworth;

* three affective axes:

  * Transcendental/Divine,
  * Relational/Loss/Yearning,
  * Environmental/Seasonal;

* six exposure checkpoints:

  * 0,
  * 3,
  * 6,
  * 9,
  * 12,
  * 15;

* three source/model categories:

  * Human,
  * Claude-like proprietary model,
  * Open-model-like system;

* four deliberately constructed simulation scenarios:

  * control/minimal drift,
  * human Tagore-linked cultural drift with AI flattening,
  * proprietary-model snapback with open-model sustained drift,
  * open-model unstable semantic drift.

These labels are used only as synthetic modelling labels. They should not be interpreted as factual claims about any real model or population.

## Feature Blocks

Each synthetic response profile is represented as a numerical feature vector. The features are grouped into the following blocks:

1. **Lexical features**
   Examples: lexical density, moving-average type-token ratio.

2. **Syntactic and pacing features**
   Examples: mean sentence length, punctuation rate.

3. **Affective VAD features**
   Examples: valence, arousal, dominance.

4. **Fine-grained emotion features**
   Examples: joy, sadness, awe, longing, devotion-like affect.

5. **Embedding-style semantic features**
   Artificial embedding coordinates are used to mimic semantic movement in a vector space.

6. **Rasa/Bhava-oriented cultural-affective features**
   Examples: shanta, bhakti, karuna, viraha-longing, monsoon affect.

These are synthetic numerical variables. They are not extracted from real text in this demonstration dataset.

## How the Synthetic Values Were Generated

For each synthetic unit, a baseline vector was generated artificially. The baseline vector was not obtained from any real poem, participant response, or AI output.

The synthetic baseline was created by combining:

```text
zero vector
+ axis-specific baseline effect
+ source/model-specific baseline effect
+ random unit-level noise
```

After baseline generation, controlled synthetic drift patterns were imposed across checkpoints. These drift patterns were designed differently across traditions, axes, source/model categories and simulation scenarios.

Thus, the dataset demonstrates the analytical structure of the proposed project after the feature-extraction stage. In the actual project, these numerical vectors will be extracted from real human-written and AI-generated textual responses.

## Affective Drift Index

The Affective Drift Index is a baseline-referenced distance measure. For a given synthetic unit, the response vector at checkpoint (k) is compared with its own baseline vector at checkpoint (0).

Conceptually:

```text
ADI at checkpoint k = distance between response vector at checkpoint k and baseline response vector
```

The baseline ADI is therefore zero by construction.

The ADI is used here only to demonstrate the proposed method for tracking affective-response drift over repeated exposure checkpoints.

## Intended Use

This repository may be used for:

* understanding the proposed statistical workflow;
* reproducing the synthetic demonstration;
* testing visualisation and modelling scripts;
* illustrating baseline-referenced affective drift;
* preparing methodological documentation for the project proposal.

This repository should **not** be used for substantive literary, cultural, psychological, or AI-behavioural conclusions.

## Ethical and Methodological Note

Since the dataset is fully synthetic, it does not involve human subjects or personal data. However, the future empirical project will require appropriate documentation of consent, anonymisation, confidentiality and institutional compliance before real human-response data are collected or shared.


