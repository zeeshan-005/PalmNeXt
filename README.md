<H2>PalmNeXt: A ConvNeXt-Based Deep Learning Model for Pest Detection in Date Palm Leaves</H2>

PalmNeXt is a lightweight, transfer learning-based solution utilizing the ConvNeXt-Tiny architecture, fine-tuned on a RGB image dataset of date palm leaves categorized into four classes: Bug, Dubas, Healthy, and Honey. Our methodology enables efficient feature extraction and robust classification without the need for manual feature engineering.


The architecture of PalmNeXt is given in the following:

<img width="816" height="510" alt="proposed_model" src="https://github.com/user-attachments/assets/6d6828ef-e930-4f80-8976-b8f7243bba89" />

## TABLE: Overall Performance Comparison Across All Classes

| Model                 | Precision | Recall | F1-Score | Accuracy |
|------------------------|-----------|--------|----------|----------|
| CNN + Attention        | 0.75      | 0.74   | 0.74     | 0.74     |
| ResNet13 + Attention   | 0.77      | 0.78   | 0.77     | 0.78     |
| ViT                    | 0.73      | 0.72   | 0.71     | 0.70     |
| **Proposed Model**     | **0.89**  | **0.89** | **0.89** | **0.89** |

