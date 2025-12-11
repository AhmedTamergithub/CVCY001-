# AIFM - Age & Face Recognition Models

## 📄 Project Reports

### Main Report:

- **[CYCV001_Report.pdf](./CYCV001_Report.pdf)** - Detailed Aage Invariant Face Matching project report

---

## 📂 Project Structure

### Core Notebooks
- **AIFM_Dataset_Preparation.ipynb** - Dataset preparation and preprocessing
- **AIFM_Full_Finetuning.ipynb** - Fine-tuning pipeline
- **Adding_Datasets_to_UTKface.ipynb** - UTKface dataset integration

### Age Prediction Model
- **Age_Prediction_Model/** - ResNet-based age prediction models
  - `AIFM_Resnet_from_0_to_60_Regression_Best_Results.ipynb` - Best performing model
  - `FineTuned_Model_Testing.ipynb` - Model evaluation and testing
  - `test_images/` - Test images for me and celebrities for  inference

### MLP Head
- **MLP_Head/** - Multi-Layer Perceptron fine-tuning
  - `MLP_Dataset_Preprocessing.ipynb` - Data preparation for MLP
  - `MLP_Training.ipynb` - Training pipeline

### Preprocessing
- **Preprocessing_Pipeline/** - It contains Reusable preprocessing modules
  - `AIFM_Preprocessing_for_one_sample.ipynb` - The System Preprocessing Pipeline applied on one sample

