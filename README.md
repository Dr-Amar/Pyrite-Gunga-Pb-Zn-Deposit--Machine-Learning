# Pyrite-Gunga-Pb-Zn-Deposit--Machine-Learning
# Machine Learning-Driven Classification of Pb–Zn Ore Deposits Using Pyrite Geochemistry

This repository supports the research article:

**"Machine learning-driven classification of Pb–Zn ore deposits using pyrite trace elements and isotopic signatures: A case study of the Gunga deposit"**  
📝 *Published in Journal of Geochemical Exploration (2025)*  
🔗 [DOI: 10.1016/j.gexplo.2025.107771](https://doi.org/10.1016/j.gexplo.2025.107771)

---

## 📌 Study Summary

This study applies machine learning to in-situ **pyrite trace element** and **S–Pb isotope** data to classify the ore genesis of the Gunga Pb–Zn deposit, located in the Lasbela-Khuzdar Belt, Pakistan. 

Using four ML models (Random Forest, Gradient Boosting, Support Vector Machine, and Multilayer Perceptron), we performed **leave-one-group-out (LOGO) cross-validation** on a global dataset (n ≈ 3800) and achieved robust classification performance.

---

## 🧠 Machine Learning Models & Results

- ✅ **Models**: RF, GB, SVM, MLP  
- 🎯 **Target**: 5 deposit types (CD, SEDEX, MVT, Skarn, VMS)  
- 📈 **Best Accuracy**: 94.73% (MLP)  
- 🧪 **Validation**: LOGO (Leave-One-Group-Out) by deposit  
- 🔍 **Important Features**: Co, Ni, Sb, As, Tl, Se, Ge  

---

## 📁 Repository Structure

Pyrite-Gunga-Pb-Zn-Deposit--Machine-Learning/
│
├── paper/ → Published article (PDF)
├── data/ → Pyrite trace element and isotope data
├── figures/ → Confusion matrix, ternary, boxplots, feature importances
├── notebooks/ → ML training and LOGO evaluation scripts
├── models/ → Trained model files (.pkl or .h5)
├── LICENSE → License for use (MIT / CC BY 4.0)
└── README.md → This file

---

## 📊 Key Figures & Outputs

- Confusion matrices from LOGO validation  
- Ternary diagrams (Co–Ni–As, Co–Ni–Sb)  
- Feature importance plots (RF, GB)  
- S and Pb isotope variation across pyrite generations  

---

## 📚 Citation

Please cite this work as:

Gul, M. A., Zhang, H., Yang, Y., et al. (2025).
Machine learning-driven classification of Pb–Zn ore deposits using pyrite trace elements and isotopic signatures: A case study of the Gunga deposit.
Journal of Geochemical Exploration, 275, 107771.
https://doi.org/10.1016/j.gexplo.2025.107771 
---

## 🔓 License

- **Code**: MIT License  
- **Data & Figures**: CC BY 4.0 License  

---

## 📬 Contact

**Dr. Muhammad Amar Gul**  
Email: amar_geologist@yahoo.com  
Affiliations: University of Science and Technology of China 
