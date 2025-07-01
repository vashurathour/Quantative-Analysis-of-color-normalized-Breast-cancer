# Color-Normalization-Breast-Cancer-


## Brief of Work

<img width="656" alt="Process of Normalization" src="https://user-images.githubusercontent.com/88971930/216353467-abbbaf9b-3532-418a-ae94-f32f2785f596.png">


## Normalization Results (Sample)

<img width="500" alt="Process of Normalization" src="https://user-images.githubusercontent.com/88971930/216359982-5a478642-65a3-4934-b181-373ee1f0d49a.png">



> ⚙️ How to Use


1.Install dependencies:
              pip install -r requirements.txt
2.Normalize your images:

python src/normalize.py --input data/raw/ --output data/normalized/

3.Extract features and run analysis:

python src/extract_features.py --input data/normalized/ --output reports/features.csv
python src/run_analysis.py --features reports/features.csv --labels data/labels.csv --output reports/analysis_results

4.View visual outputs in reports/.






                                 
