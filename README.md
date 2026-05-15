# Part 2: CNN Computer Vision

This submission frames the dataset as a **manufacturing surface inspection** problem using **binary image classification**.

## Problem summary

- **Input:** product surface image
- **Output:** `normal` or `defective`
- **Business use:** automate quality inspection and reduce manual review effort

For this prototype, the original defect types `scratch`, `dent`, and `stain` are grouped into a single `defective` class.

## Model summary

The solution uses a small CNN-style prototype trained from the provided image dataset. The model learns visual patterns from pixel data and predicts whether a surface is normal or defective.

## Repository contents

- `README.md`
- `notebook.ipynb`
- `requirements.txt`
- `sample_predictions/prediction_outputs.png`
- `results/accuracy_loss_curves.png`
- `results/confusion_matrix.png`

## Notes

- The strict folder structure here is for submission packaging.
- The larger source-data/project folder remains available separately as `part_2_cnn_computer_vision`.
"# cnn-computer-vision-kanha-gupta-2511261" 
