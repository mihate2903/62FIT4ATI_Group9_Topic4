# 62FIT4ATI_Group9_Topic4

## 📌 Project Overview
**Subject:** 62FIT4ATI - Advanced Technology in IT
**Group:** 9
**Topic:** 4 - Tweet Sentiment Extraction

This project aims to solve the **Sentiment Extraction** problem: Given a tweet and a sentiment label, the model extracts the specific substring that supports that sentiment using **RoBERTa**.

## 👥 Team Members
1. **Lê Anh Quân (2201140071) (Leader)**
2. **Đỗ Tuấn Dũng (2201140018)**
3. **Tạ Hải Long (2101140049)**

---

## 📂 Repository Structure
- `62FIT4ATI_Group 9_Topic 4.ipynb`: Source code (Data processing, Training, Inference).
- `62FIT4ATI_Group 9_Topic 4_Report.docx`: Written Report (Methodology & Results).
- `README.md`: Setup instructions (this file).
- `train.csv`: Training dataset (Required input).
- `test.csv`: Test dataset (Required input).
- `best_model.bin`: Trained weights (Output) (Drive link: https://drive.google.com/file/d/1DHthHO9DHfD9yyGCgIKgE46OsEmajYd9/view?usp=drive_link)
- `submission.csv`: Inference results (Output).

---

## 🛠️ Requirements
- Python 3.x
- Libraries: `transformers`, `torch`, `pandas`, `numpy`, `scikit-learn`

## 🚀 How to Run
1. Open `62FIT4ATI_Group 9_Topic 4.ipynb` in Google Colab.
2. Upload dataset files (`train.csv` and `test.csv`) to the runtime.
3. Run all cells sequentially.

## 📊 Results
- **Metric:** Jaccard Score (~0.70)
- **Technique:** RoBERTa + Linear Scheduler + Neutral Post-processing.
