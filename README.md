# 🐱🐶 Kedi/Köpek Sınıflandırma Modeli

Bu proje, derin öğrenme teknikleri kullanarak kedi ve köpek resimlerini sınıflandıran bir Evrişimli Sinir Ağı (CNN) modeli oluşturur ve eğitir.

## 🚀 Özellikler

- TensorFlow ve Keras kullanarak oluşturulmuş CNN modeli
- 64x64 piksel boyutunda resimler için optimize edilmiş
- %99 üzerinde eğitim doğruluğu
- Eğitim ve test veri setleri için ayrı işleme

## 🛠️ Gereksinimler

- Python 3.x
- TensorFlow
- Keras
- NumPy
- Pillow

## 📂 Proje Yapısı

```
.
├── train/              # Eğitim resimleri
├── test1/              # Test resimleri
└── model_training.py   # Model eğitim scripti
```

## 🏃‍♂️ Nasıl Çalıştırılır

1. Gerekli kütüphaneleri yükleyin:
   ```
   pip install tensorflow numpy pillow
   ```

2. Eğitim ve test resimlerini ilgili klasörlere yerleştirin.

3. Scripti çalıştırın:
   ```
   python model_training.py
   ```

4. Eğitim tamamlandığında, model 'enson-1024Dense-64x64-nparray-098acc.keras' olarak kaydedilecektir.

## 🧠 Model Mimarisi

Model, aşağıdaki katmanları içerir:
- 4 Evrişim (Conv2D) katmanı
- 4 Maksimum Havuzlama (MaxPooling2D) katmanı
- Düzleştirme (Flatten) katmanı
- Seyreltme (Dropout) katmanı
- 2 Tam Bağlantılı (Dense) katman

Toplam parametre sayısı: 3,707,521

## 📊 Performans

Model, 50 epoch sonunda %99'un üzerinde eğitim doğruluğuna ulaşmıştır.

## 🔮 Gelecek Geliştirmeler

- Veri artırma tekniklerinin eklenmesi
- Daha büyük ve çeşitli bir veri seti kullanılması
- Farklı model mimarilerinin denenmesi
- Modelin web uygulamasına entegre edilmesi

## 👨‍💻 Geliştirici

[Yusuf Enes Budak]

## 📄 Lisans

Bu proje [MIT Lisansı](LICENSE) altında lisanslanmıştır.

---

🐾 Kedi/Köpek Sınıflandırma Modeli 🐾 © 2024
