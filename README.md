# hygd-glaucoma-detection
Glaucoma detection using HYGD fundus dataset
# HYGD Glaucoma Detection 👁️

Glaucoma (GON) detection using the Hillel Yaffe Glaucoma Dataset 
and deep learning.

---

## 📁 Dataset Setup

This project uses the **Hillel Yaffe Glaucoma Dataset (HYGD) v1.1.0**.

The dataset is **not included** in this repository due to PhysioNet 
data use restrictions. Please follow these steps to get it:

### Step 1 — Register & Download
1. Go to https://physionet.org/content/hillel-yaffe-glaucoma-dataset/1.1.0/
2. Create a free PhysioNet account
3. Sign the Data Use Agreement
4. Download the full dataset (ZIP file)

### Step 2 — Upload to Google Drive
1. Extract the ZIP file on your computer
2. Upload the extracted folder to your Google Drive
3. Your Drive should look like this:

MyDrive/
└── HYGD/
    ├── Images/
    │   ├── 1_0.jpg
    │   ├── 1_1.jpg
    │   └── ... (747 images total)
    └── Labels.csv

---

## 🚀 How to Run

1. Open the notebook in Google Colab:
   [Open in Colab](https://colab.research.google.com/drive/1VEgPvSmWm3xBew1ITOBbfsED5SuNBhe0#scrollTo=itkxksB1AV7t)

2. Mount your Google Drive when prompted

3. Update the dataset path in the notebook to match 
   your Drive folder

4. Run all cells top to bottom

---

## 📊 Dataset Info

| Property | Value |
|---|---|
| Total images | 747 |
| GON+ (Glaucoma) | 548 (73%) |
| GON- (Healthy) | 199 (27%) |
| Image format | JPG |
| Labels file | Labels.csv |

---

## 👥 Team
- [Aida]
- [Ain]
- [Ainin]
- [Aqilah]
