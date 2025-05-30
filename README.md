# 🎵 Clustering Music Genres with Machine Learning

Bu proje, şarkıların ses özelliklerine göre müzik türlerini kümelemek için makine öğrenmesi (K-Means) kullanır. Spotify veri seti ile çalışılmıştır.

## 📌 Kullanılan Veri Seti

- Dataset: `Spotify-2000.csv`
- İçerik: Şarkıların BPM, enerji, dans edilebilirlik gibi ses karakteristikleri

## 🔍 Yöntem

1. Veri Temizleme ve Dönüştürme
2. Sayısal Verilerin Ölçeklenmesi
3. K-Means Kümeleme
4. PCA ile Görselleştirme
5. Küme Analizi

## 📊 Kullanılan Kütüphaneler

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## ▶️ Nasıl Çalıştırılır?

```bash
pip install -r requirements.txt
```

Notebook'u çalıştır:
```
music_clustering.ipynb
```

## 📁 Proje Amacı

Bu proje müzik öneri sistemlerine katkı sağlar, şarkıların tür etiketlerine ihtiyaç duymadan benzerlik temelli kümelenmesini sağlar.
