Here's an enhanced version of your README:

---

# Skimlit

## Overview

Skimlit is a sequential sentence classification project aimed at analyzing and classifying medical abstracts from the PubMed dataset. By utilizing cutting-edge embeddings, including character, token, and positional encodings, Skimlit demonstrates high-performance models, particularly the Tribrid Pos Char Token Embed model. The models are evaluated on the PubMed 20k and PubMed 200k RCT datasets, highlighting significant advancements in text classification.

## Model Performance

### PubMed 20k Dataset

- **Baseline Model:**
  - Accuracy: 72.18% | Precision: 0.719 | Recall: 0.722 | F1 Score: 0.699

- **Custom Token Embed Conv1D:** 
  - Accuracy: 78.67% | Precision: 0.783 | Recall: 0.787 | F1 Score: 0.784

- **Pretrained Token Embed:** 
  - Accuracy: 78.67% | Precision: 0.783 | Recall: 0.787 | F1 Score: 0.784

- **Custom Char Embed Conv1D:**
  - Accuracy: 65.18% | Precision: 0.643 | Recall: 0.652 | F1 Score: 0.643

- **Hybrid Char Token Embed:** 
  - Accuracy: 73.21% | Precision: 0.733 | Recall: 0.732 | F1 Score: 0.730

- **Tribrid Pos Char Token Embed:** 
  - Accuracy: 83.42% | Precision: 0.834 | Recall: 0.834 | F1 Score: 0.833

### PubMed 200k Dataset

- **Best Model (Tribrid Pos Char Token Embed):**
  - Accuracy: 87.51% | Precision: 0.876 | Recall: 0.875 | F1 Score: 0.874

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/skimlit.git
   ```

2. **Navigate to the Project Directory:**
   ```bash
   cd skimlit
   ```

3. **Set Up Environment:**
   Install required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

4. **Train Models:**
   Refer to steps in notebook.

5. **Run Analysis:**
   Review metrics and model results outlined in `notebook.ipynb`.

## Folder Structure

```plaintext
├───skimlit_tribrid_model_200k
│   ├───assets
│   └───variables
├───skimlit_tribrid_model_20k
│   ├───assets
│   └───variables
└───__pycache__
```

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

## Contact

For any questions or feedback, reach out via [email](mailto:sallanrasheek@gmail.com).

---
