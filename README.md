# FineTune_and_GradCam

This project uses a ResNet18 model to classify images from the Intel Image Classification dataset into six scene categories.  
GradCAM is also applied to visualize the important regions in the images that the model focuses on for its predictions.

---

## Dataset
- Source: [Intel Image Classification (Kaggle)](https://www.kaggle.com/datasets/puneet6060/intel-image-classification)  
- Classes: Buildings, Forest, Glacier, Mountain, Sea, Street  

---

## Steps
1. Download the dataset from Kaggle and extract it.
2. Train a ResNet18 model (pretrained on ImageNet, fine-tuned for 6 classes).
3. Save model checkpoints after each epoch.
4. Use GradCAM to generate heatmaps for interpretability.

---

## Results
- Model: ResNet18 (fine-tuned)  
- Accuracy: ~97% after 10 epochs  
- Visualization: GradCAM highlights regions used by the model for classification  

---

## Example GradCAM Output

GradCAM heatmaps show which areas of the image contributed most to the prediction. This helps understand and trust the model’s decision-making.

---

