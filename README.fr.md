<div align="center">

# Michaël Féré

**Docteur · 12 ans à la frontière de la physique et de l'IA moderne**
**Senior ML/AI Engineer — Physical AI · Deeptech industrielle**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/michael-fere-data-scientist)
[![Location](https://img.shields.io/badge/Aix--en--Provence-France-blue?style=flat-square)](https://www.google.com/maps/place/Aix-en-Provence)
[![Disponible](https://img.shields.io/badge/Disponibilité-immédiate-brightgreen?style=flat-square)]()
[![EN Version](https://img.shields.io/badge/🇬🇧-English_version-blue?style=flat-square)](README.md)

*Faire le pont entre les signaux physiques bruités et l'IA industrielle en production.*

</div>

---

## Profil

Senior Data Scientist avec **12 ans d'expérience** à la frontière des
sciences physiques et de l'IA moderne. **Docteur en traitement du
signal** (CNRS), spécialisé dans la transformation de données capteurs
bruitées et réelles en solutions industrielles robustes.

**Différenciation.** Je ne fais pas que nettoyer des CSV. Je comprends
la physique derrière les données pour construire des modèles qui
survivent au monde réel — dérive, bruit, contraintes embarquées,
dégradation des capteurs, variations de température.

**Domaines.** Architectures neuro-symboliques hybrides · MLOps pour la
science · Vision par ordinateur · Traitement du signal temporel et
spectral.

**Disponible pour.** IA industrielle · Deeptech · Edge ML · Capteurs
intelligents · Applications spectroscopie / chimiométrie. Entreprises
visées : Thalès (Toulon), Framatome (Cadarache), TOPNIR Systems, CEA.
Télétravail ou sur site en région PACA.

---

## Projets phares

### Lythéa — Architecture cognitive pour assistant conversationnel
*R&D personnelle · Vitrine publique sur GitHub*

Assistant conversationnel local avec une architecture multi-couche
neuro-inspirée : mémoire épisodique + sémantique (MHN + SDM +
ChromaDB + Knowledge Graph), RAG hybride avec re-ranking, et 8 modules
cognitifs activables indépendamment (théorie de l'esprit, inhibition,
planification, métacognition, cohérence temporelle, codage prédictif).

**Points forts d'ingénierie :**
- Architecture 3 couches modulaire, chaque module cognitif activable
  à la demande
- Auto-calibration empirique modèle-agnostique (basée sur les quantiles)
- 246 tests unitaires publics + ~350 privés + harnais E2E à 16 scénarios
- Validé in vivo sur Qwen 2.5 (3B / 7B) et Qwen 3 (4B Thinking)

**Stack :** `Python` `FastAPI` `PyTorch` `Hugging Face` `ChromaDB`
`sentence-transformers` `GLiNER` `Cross-encoder`

🔗 [github.com/<user>/lythea-light](#)

---

### EXALIA — Architecture neuronale hybride liquide
*Expérimental · Prototype avancé*

Architecture expérimentale combinant Large Language Models (LLMs) et
réseaux neuronaux à temps continu (Liquid Networks) pour du
raisonnement causal avancé.

**Approche ingénieur :**
- **Architecture** — Intégration de réseaux Closed-form Continuous-time
  (CfC) dans des Transformers backbones gelés.
- **Mécanisme** — Routage parcimonieux dirigeant la connaissance
  statique vers les couches pré-entraînées et les états dynamiques
  vers les réseaux liquides.
- **Hypothèse** — Adresser la limitation "logique statique" des LLMs
  en introduisant une dynamique temporelle pour le raisonnement
  multi-étapes.

**Stack :** `PyTorch` `Hugging Face (Qwen)` `Neural Circuit Policies`
`torchdiffeq`

---

## Expérience professionnelle

### Senior Data Scientist — SP3H *(2021 — Fév 2026)*
*Deeptech · IoT industriel · Spectroscopie NIR embarquée*

Lead modélisation IA pour capteurs intelligents miniaturisés (FluidBOX)
déployés sur véhicules commerciaux.

- **Défi ingénieur** — Modèles ML robustes aux contraintes physiques
  extrêmes (-20 °C à +85 °C, vibrations mécaniques).
- **Physics-informed AI** — Algorithmes adaptatifs de correction de
  baseline gérant la dérive instrumentale en temps réel.
- **Déploiement edge** — Modèles spectraux haute dimension optimisés
  pour environnements embarqués (mémoire faible, sans connectivité cloud).

### R&D Data Scientist — CEA Tech *(2019 — 2020)*
*AgriTech · Imagerie hyperspectrale · Vision par ordinateur*

Étude de faisabilité et développement d'une solution non invasive de
sexage utilisant l'imagerie hyperspectrale.

- **Stratégie de fusion** — Combinaison des données spatiales (vision)
  et spectrales pour la classification de cubes haute dimension.
- **Impact** — Validation d'une preuve de concept pour une alternative
  éthique dans l'industrie agroalimentaire.

### Doctorant — CNRS / Université de Reims *(2014 — 2018)*
*Santé · Traitement du signal · Spectroscopie multimodale*

**Thèse :** Diagnostic automatisé de leucémies par spectroscopie
multimodale.

- **Stratégie anti-overfitting** — Pipeline de double validation
  croisée répétée (100+ modèles) pour la robustesse clinique.
- **Système de décision** — Algorithmes de vote majoritaire pour
  diagnostic automatisé au niveau patient.

### Ingénieur de Recherche — CNRS MEDyC *(2012 — 2014)*
*Spectroscopie · Poste pré-thèse*

Deux ans de recherche appliquée en analyse de signaux spectroscopiques
avant la thèse — statistiques multivariées, chimiométrie, extraction
de caractéristiques sur échantillons biomédicaux.

---

## Stack technique

**Data Science & IA**
- **Langages :** Python (NumPy, Pandas, SciPy, scikit-learn), SQL.
- **Deep Learning :** PyTorch, TensorFlow/Keras, Hugging Face Transformers.
- **Domaines :** Traitement du signal, spectroscopie, vision par
  ordinateur, séries temporelles, chimiométrie (PLS, PCA, PLS-DA, LDA/QDA).

**Generative AI Engineering**
- **Architectures :** RAG (hybride sparse + dense + re-ranking),
  agents (LangChain), fine-tuning (LoRA / QLoRA).
- **Modèles :** Llama, Qwen (2.5 / 3), Mistral, Gemini, Claude (API).

**Engineering & MLOps**
- **Outils :** Docker, Git, Linux.
- **Déploiement :** Services FastAPI, monitoring de modèles (détection
  de drift).
- **Cloud :** AWS, Azure (familiarité opérationnelle).

---

## Certifications sélectionnées

- **IBM Generative AI Engineering** *(2024)*
- **IBM Data Science Specialization** *(2025)*
- **Deep Learning with Keras & TensorFlow** *(IBM)*
- **Nvidia Deep Learning Institute** *(2017)*
- **Scrum Master Certification** *(LearnQuest)*

---

<div align="center">

**Aix-en-Provence, France** · Télétravail · Français courant · Anglais technique

[![Contactez-moi](https://img.shields.io/badge/Contactez--moi-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/michael-fere-data-scientist)

</div>
