#  Humor Generation System – SemEval 2026 Submission

This repository contains the dataset, preprocessing pipeline, training implementation, and evaluation details for our participation in **SemEval 2026 – Humor Generation Task**.

The system is designed to generate creative, logically coherent, and instruction-compliant jokes using a structured output format.

---

## Overview

The objective of this system is to generate high-quality humorous content that:

- Follows strict formatting constraints  
- Maintains logical coherence  
- Demonstrates creativity and cleverness  
- Achieves perfect instruction adherence  

All generated outputs strictly follow the required format:

```
JOKE: <generated joke text>
```

The `JOKE:` prefix is enforced during both training and evaluation to ensure formatting compliance.

---

##  Repository Structure

```
├── final_dataset_fixed.tsv      # Cleaned and formatted training dataset
├── 4_epoch.ipynb                # Model training notebook (4-epoch configuration)
├── evaluation/                  # Evaluation details (if applicable)
├── training_scripts/            # Supporting scripts (if applicable)
└── README.md
```

---

##  Methodology

### Dataset Preparation

The dataset was preprocessed to ensure:

- Removal of malformed entries  
- Consistent formatting  
- Prefix enforcement (`JOKE:`)  
- Logical and structural clarity  

The final processed dataset is available as:

```
final_dataset_fixed.tsv
```

---

##  Training Configuration

| Parameter              | Value        |
|------------------------|-------------|
| Epochs                 | 4           |
| Final Training Loss    | ~1.65       |
| Dataset Format         | TSV         |
| Output Prefix          | `JOKE:`     |
| Instruction Compliance | 100%        |

The model was fine-tuned for 4 epochs to balance coherence and creativity while preventing overfitting.

---

##  Performance Summary

| Metric                  | Result                |
|--------------------------|------------------------|
| Training Loss            | ~1.65                  |
| Joke Quality             | Creative / Clever      |
| Instruction Following    | 100% (Perfect)         |
| Logic / Coherence        | High                   |
| Formatting Compliance    | Correct `JOKE:` Prefix |

The system demonstrates strong instruction adherence and consistently generates logically structured humorous outputs.

---

##  Reproducibility

### 1️ Clone the repository

```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
```

### 2️ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️ Run the training notebook

Open:

```
4_epoch.ipynb
```

and execute all cells.

---

## 📎 SemEval 2026 Submission

This repository accompanies our official submission to **SemEval 2026 – Humor Generation Task** and is referenced in the corresponding system paper.

All reported metrics in the paper correspond to the configuration provided in this repository.

---

##  Citation

If you use or reference this work, please cite:

```
@misc{abbas2026humor,
  title={Humor Generation System for SemEval 2026},
  author={Insa Abbas},
  year={2026},
  note={SemEval 2026 Submission},
  url={https://github.com/<your-username>/<your-repo>}
}
```

---

##  Author

**Insa Abbas**  
 Email: insaabbas675@gmail.com  

---

##  Notes

- This implementation prioritizes instruction adherence and formatting reliability alongside humor quality.
- The model was evaluated for creativity, coherence, and structural compliance.
- The repository is maintained for transparency, reproducibility, and academic reference.
