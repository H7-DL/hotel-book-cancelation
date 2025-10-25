# Hotel Booking Cancellation — Predictive Model

Portofolio project memprediksi pembatalan booking hotel (cancel / not cancel).
Model terpilih: Random Forest dengan operating threshold 0.300 (recall tinggi).

## Struktur
notebooks/Study_Case_Data_Science.ipynb
data/train.csv                # opsional; hapus bila repo publik
data/README.md
artifacts/                    # output model/metrics (jangan commit file besar)
reports/                      # letakkan deck presentasi (opsional)
requirements.txt
.gitignore
README.md
LICENSE

## Cara jalan (lokal)
python -m venv .venv && source .venv/bin/activate    # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook notebooks/Study_Case_Data_Science.ipynb
