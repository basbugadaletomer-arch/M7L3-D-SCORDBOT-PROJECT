# 🤖 Discord Görüntü Sınıflandırma Botu

> Bu proje; Discord üzerinden kullanıcıların gönderdiği görselleri (fotoğrafları) yapay zeka modeliyle analiz ederek sınıflandıran, Python ve Discord.py tabanlı akıllı bir Discord botudur.

---

## 📌 İçindekiler
- [Proje Hakkında](#-proje-hakkında)
- [Kullanılan Teknolojiler](#-kullanılan-teknolojiler)
- [Komutlar ve Özellikler](#-komutlar-ve-özellikler)
- [Kurulum ve Çalıştırma](#-kurulum-ve-çalıştırma)
- [Dosya Yapısı](#-dosya-yapısı)
- [Geliştirici](#-geliştirici)

---

## 🎯 Proje Hakkında
Bu bot, kullanıcıların sohbete yükledikleri görselleri otomatik olarak yakalar, bilgisayara kaydeder ve özel olarak eğittiğimiz derin öğrenme modeli (`keras_model.h5`) aracılığıyla ne olduğunu tahmin eder. Discord üzerinden hızlı ve etkileşimli yapay zeka testleri yapmak için idealdir.

---

## 💻 Kullanılan Teknolojiler
* **Python 3.x** - Programlama dili
* **Discord.py** - Discord API entegrasyonu için bot kütüphanesi
* **TensorFlow / Keras** - Yapay zeka modelinin çalıştırılması
* **Model Dosyaları** (`keras_model.h5` & `labels.txt`) - Görüntü işleme ve sınıflandırma

---

## ⚙️ Komutlar ve Özellikler
Botun desteklediği komutlar ve önek (`₺`) listesi:
* `₺hello` - Botun çalıştığını ve selam verdiğini gösterir.
* `₺heh [sayı]` - Belirtilen sayıda "he" sesi çıkarır.
* `₺MERHABA [sayı]` - Matematiksel bir test komutudur.
* `₺check` *(Görsel ile birlikte)* - Kanala eklenen fotoğrafı indirir, yapay zeka modeline gönderir ve tahmin sonucunu ekrana yazdırır. Görsel eklenmezse uyarı verir.

---

## 🛠️ Kurulum ve Çalıştırma

Projeyi kendi bilgisayarınızda çalıştırmak için şu adımları izleyin:

1. **Depoyu klonlayın veya indirin:**
   ```bash
   git clone [https://github.com/KULLANICI_ADIN/PROJE_ADIN.git](https://github.com/KULLANICI_ADIN/PROJE_ADIN.git)
   cd PROJE_ADIN

   Gerekli kütüphaneleri yükleyin:

Bash
pip install discord.py tensorflow pillow
Gerekli dosyaların tam olduğundan emin olun:

main.py (Bot kodları)

model.py (get_class fonksiyonunu içeren dosya)

keras_model.h5 (Yapay zeka model dosyanız)

labels.txt (Model etiketleri)

Botunuzu Çalıştırın:main.py dosyasının en altındaki bot.run("BURAYA_TOKEN_GELECEK") kısmına kendi Discord Bot Token'ınızı yazın ve çalıştırın:

Bash
python main.py
📂 Dosya Yapısı
Plaintext
📦 Proje Klasörü
 ┣ 📜 main.py             # Ana Discord bot dosyası
 ┣ 📜 model.py            # Yapay zeka tahmin fonksiyonu
 ┣ 📜 keras_model.h5      # Eğitilmiş yapay zeka modeli
 ┗ 📜 labels.txt          # Sınıf etiketleri
👤 Geliştirici
ADALET ÖMER BAŞBUĞ 


---

Bu şablon doğrudan senin kodundaki komutlara (`hello`, `heh`, `MERHABA`, `check`) ve yapıya (`model.py`, `keras_model.h5`) uyarlanmıştır. GitHub'da `README.md` dosyası olarak yapıştırdığın anda mükemmel ve düzenli bir görünüme kavuşacaktır!
