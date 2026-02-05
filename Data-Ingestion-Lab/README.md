# Deep Learning 2025-26 - Sana Khan
# 29Jan Datasets Upload Methods

**Project Description**
This notebook demonstrates four distinct methods for Data Ingestion in a Google Colab environment. The goal was to test different pipelines for loading `.csv` data into Pandas DataFrames for Deep Learning tasks.

**Dependencies**
* Python 3.x
* Pandas
* Kagglehub
* Google Colab (Drive mounting)

---

### Implementation Details

**Method 1: Local Sample Data**
* Loaded the pre-existing MNIST digit dataset provided by the Colab runtime environment.
* Used standard `pd.read_csv()` for local path access.

**Method 2: Kaggle API (Small Dataset)**
* Utilized the `kagglehub` library to fetch the **Iris Species** dataset directly from Kaggle.
* Automated the file path retrieval to handle dynamic download locations.

**Method 3: Cloud Storage Integration (Google Drive)**
* Mounted Google Drive to the runtime (`/content/drive`).
* Accessed a custom dataset (`mnist_train_small.csv`) stored in a private Drive folder, simulating a real-world workflow where data is stored securely on the cloud.

**Method 4: Large Dataset Retrieval**
* Downloaded the **Credit Card Fraud Detection** dataset using `kagglehub`.
* Verified directory contents using `os.listdir()` to ensure correct file targeting before loading.

---
## 👩‍💻 Author
Sana Khan

GitHub: @KhanSana15
