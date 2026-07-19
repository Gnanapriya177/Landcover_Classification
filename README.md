# Land Cover Classification using Satellite Imagery

Deep learning model to classify satellite images into 10 land cover 
categories using transfer learning on ResNet18.

## Dataset
EuroSAT (Sentinel-2 satellite imagery, 27,000 images, 10 classes)

## Approach
- Transfer learning using pretrained ResNet18
- Initial training with frozen backbone: 83.6% validation accuracy
- Fine-tuned by unfreezing final conv block (layer4): 99.16% validation accuracy

## Results
- Validation Accuracy: 99.16%
- Evaluated using confusion matrix and classification report (precision/recall/F1)

## Tech Stack
Python, PyTorch, torchvision, scikit-learn, matplotlib, seaborn

## How to run
Open `[notebook_name].ipynb` in Google Colab and run all cells (GPU runtime recommended).
