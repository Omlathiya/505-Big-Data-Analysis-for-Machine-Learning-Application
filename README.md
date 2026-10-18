# DS-505: Big Data Handling and Management for Machine Learning Applications
B.Sc. (Data Science & Analytics) - Semester V | 16 Practicals (Jupyter Notebooks)

Every notebook is **fully self-contained**: it generates its own synthetic data, so there are no
dataset files to download. Each notebook is organised as:

1. **Imports** (one separate code cell)
2. Task-wise steps - a markdown heading followed by its code cell

## Folder structure
```
DS505_Practicals/
├── README.md
├── requirements.txt
├── Unit1_Big_Data_Intro/        p01 - p04
├── Unit2_PySpark/               p05 - p08
├── Unit3_ML_Preparation/        p09 - p12
└── Unit4_LLM_Applications/      p13 - p16
```

## Run
```bash
pip install -r requirements.txt
jupyter notebook            # then open any .ipynb and use  Kernel > Restart & Run All
```
Works in JupyterLab, VS Code and Google Colab as well (upload the .ipynb file).

## Notes
- **Unit 2 (PySpark):** needs Java 8/11/17 (`java -version`). In Google Colab just run the `%pip install pyspark` cell.
  On Windows, writing Parquet (P08) may need winutils/Hadoop.
- **P04 / P08:** use temporary folders that are deleted in the last cell.
- **P15 / P16:** download pretrained models on first run (internet needed once). Uncomment the `%pip install` cell
  in Step 0 if `transformers`/`torch` are not installed.
- Notebooks are shipped without outputs - run them to produce outputs/screenshots for your journal.
