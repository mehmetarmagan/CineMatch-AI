# CineMatch-AI 🎬

CineMatch-AI; kullanıcının arattığı filmlere, seçtiği türlere ve "şöyle bir film olsun" diye yazdığı tariflere göre en uygun filmleri çıkartan web tabanlı bir film öneri uygulamasıdır. 

Sadece film adlarına bakmak yerine film özetlerini ve metinleri matematiksel benzerlik algoritmalarıyla (TF-IDF & Cosine Similarity) analiz ederek öneri yapar.

---## 🛠️ Neler Kullandık?- **Backend / Kod:** Python 3, Flask, Scikit-learn, Pandas- **Frontend / Arayüz:** HTML5, CSS3, Jinja2- **Veritabanı:** SQLite / SQL- **Test:** Pytest

---## 🚀 Projeyi Bilgisayarda Çalıştırma1. Projeyi indirin:
   git clone https://github.com/mehmetarmagan/CineMatch-AI.git
   cd CineMatch-AI

2. Gerekli paketleri kurun:
   pip install -r requirements.txt

3. Projeyi çalıştırın:
   python app.py

4. Tarayıcıdan giriş yapın:
   http://localhost:5000
