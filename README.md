# 🩸 BloodCell Detective

**An interactive machine learning laboratory for exploring and classifying peripheral blood cells.**

BloodCell Detective is an educational machine learning project focused on the classification of white blood cells using computer vision and artificial intelligence.

The goal is to combine classical machine learning, deep learning and explainable AI into an interactive application that makes blood-cell morphology easier to explore and understand.

## Project Objectives

- Explore and understand a real-world blood-cell image dataset.
- Build and evaluate classical machine learning classification models.
- Develop a deep learning model for image classification.
- Compare model performance using appropriate evaluation metrics.
- Explore model interpretability using explainable AI techniques.
- Develop an interactive application for visualizing predictions and learning about cell morphology.
- Experiment with retrieval-augmented generation (RAG) for an educational hematology assistant.

## Planned Features

- [ ] Dataset exploration and preprocessing
- [ ] Exploratory data analysis and class distribution
- [ ] Classical ML baseline
- [ ] CNN-based image classification
- [ ] Model evaluation and comparison
- [ ] Explainability with Grad-CAM
- [ ] Interactive image classification interface
- [ ] Educational hematology assistant
- [ ] Flashcards and morphology quizzes

## Technologies

| Area | Technologies |
|---|---|
| Programming | Python |
| Data analysis | NumPy, Pandas |
| Visualization | Matplotlib, Seaborn |
| Classical ML | Scikit-learn |
| Computer vision | Pillow, PyTorch |
| Deep learning | PyTorch |
| Interactive application | Streamlit (planned) |
| Version control | Git and GitHub |

## Project Structure

```text
BloodCell-Detective/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
├── src/
├── models/
├── app/
├── docs/
├── requirements.txt
├── README.md
└── .gitignore
```

## Dataset

The project will use the [Peripheral Blood Cell Images dataset](https://data.mendeley.com/datasets/snkd93bnjr/1).

Dataset exploration, class selection, preprocessing and splitting strategies will be documented as part of the project.

## Getting Started

Clone the repository:

```bash
git clone https://github.com/stoicaluanagabriela/bloodcell-detective.git
cd bloodcell-detective
```

Create and activate a virtual environment:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Disclaimer

This is an educational machine learning project. It is not intended for clinical diagnosis, medical decision-making or patient care.

## Project Status

<code>In development — initial setup completed.</code>

More documentation, experiments and application features will be added as the project progresses.