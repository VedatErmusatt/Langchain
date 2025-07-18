# 📚 LangChain Fundamentals

Bu depo, LangChain kütüphanesinin temel bileşenlerini öğrenmek ve deneyimlemek amacıyla hazırlanmış Jupyter defterlerinden oluşur. Her `.ipynb` dosyası, LangChain'in farklı bir yönünü ele alır.

---

## 🧠 İçerikler

- **First.ipynb:** LangChain’e giriş, temel kavramlar ve kurulum
- **Project.ipynb:** Mini bir uygulama veya demo proje çalışması
- **Agents.ipynb:** LangChain `Agents` modülünün kullanımı
- **RAG.ipynb:** Retrieval-Augmented Generation uygulaması

---

## 🚀 Gereksinimler

Aşağıdaki paketler `requirements.txt` içinde sabitlenmiştir:

```txt
langchain==0.3.25
langchain-core==0.3.60
python-dotenv==1.1.0
langchain-google-genai==2.1.4
```

> Gerekli tüm kütüphaneleri yüklemek için:

```bash
pip install -r requirements.txt
```

---

## 🧪 Nasıl Kullanılır

1. Bu repoyu klonlayın:

```bash
git clone https://github.com/VedatErmusatt/langchain-fundamentals.git
cd langchain-fundamentals
```

2. Sanal ortam oluşturup aktive edin (önerilir):

**Windows:**
```bash
python -m venv venv
venv\Scripts\activate
```

**macOS / Linux:**
```bash
python3 -m venv venv
source venv/bin/activate
```

3. Gereksinimleri yükleyin:

```bash
pip install -r requirements.txt
```

4. Jupyter Notebook başlatın:

```bash
jupyter notebook
```

---

## 🧩 Notlar

- `langchain-google-genai` modülünü kullanabilmek için bir `GOOGLE_API_KEY` gerekir. `.env` dosyasına bu anahtarı ekleyin:
  ```env
  GOOGLE_API_KEY=your_api_key
  ```
- Gerekirse ayrıca `openai`, `faiss-cpu`, `tiktoken` gibi modüller de ileride projeye dahil edilebilir.

---

## 🧑‍💻 Geliştirici

📛 Vedat Ermusatt  
📅 2025 — Yapay Zekâ Geliştirici Eğitim Günlüğü  
🔗 GitHub: [VedatErmusatt](https://github.com/VedatErmusatt)

---

## 📄 Lisans

Bu çalışma kişisel öğrenim ve deneysel amaçlar içindir. Gönüllü olarak MIT Lisansı ile sunulabilir.
