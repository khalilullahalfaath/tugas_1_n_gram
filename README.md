# Tutorial Instalasi & Setup Proyek N-Gram

Jika memakai Google Colab, bisa langsung buka file `n_gram.ipynb` di Colab tanpa perlu instalasi.

## 1. Membuat Virtual Environment (venv)

Disarankan menggunakan virtual environment agar dependensi proyek terisolasi.

### Langkah-langkah

1. **Buka terminal di folder proyek**  
   Contoh:  

   ```
   cd "d:\2 Kuliah\S2 - Universitas Gadjah Mada\Semester 1\RPP\Tugas\tugas_1_n_gram"
   ```

2. **Buat virtual environment**  
    - **Windows:**
    
      ```
      python -m venv env
      ```

    - **Mac/Linux:**
        ```
        python3 -m venv env
        ```

   catatan: Ganti `env` dengan nama folder yang diinginkan untuk virtual environment.

3. **Aktifkan virtual environment**  
   - **Windows:**

     ```
     env\Scripts\activate.bat
     ```

     atau

     ```
     env\Scripts\activate
     ```
   
   - **Mac/Linux:**
     ```

     source env/bin/activate

     ```
## 2. Instalasi Library yang Dibutuhkan

Pastikan virtual environment sudah aktif sebelum menjalankan perintah berikut.

```
pip install -r requirements.txt
```

Library yang akan diinstal antara lain:

- numpy
- pandas
- pdfplumber
- scikit-learn
- dan lain-lain (lihat `requirements.txt`)

## 3. Menjalankan Notebook

Buka file `n_gram.ipynb` menggunakan Jupyter Notebook atau VS Code.

---

**Catatan:**  
Jika ada error instalasi, pastikan pip dan Python sudah versi terbaru.
