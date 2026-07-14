# ML Project — Fake News Detection

A small machine learning project for detecting fake news using text classification techniques.

## Contents

- Dataset: place your dataset files under `data/`.
- Notebooks: exploratory analysis and model experiments.
- Scripts: training, evaluation, and inference scripts.

## Requirements

- Python 3.8+
- Install dependencies:

```bash
pip install -r requirements.txt
```

## Quick Start

1. Prepare your dataset in `data/` (train/ and test/ splits).
2. Train a model:

```bash
python scripts/train.py --data_dir data/ --output_dir models/
```

3. Evaluate:

```bash
python scripts/evaluate.py --model_dir models/ --data_dir data/
```

4. Run inference on new texts:

```bash
python scripts/infer.py --model_dir models/ --text "Sample news text"
```

## Notes

Adjust script names and CLI flags to match the repository's actual scripts.

## License & Contact

Add license information here and contact details if desired.
