# Global Su Kullanımı Analizi

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)](https://plotly.com/)
[![FAO Verisi](https://img.shields.io/badge/Veri-FAO%20AQUASTAT-green)](https://www.fao.org/aquastat/en/)
[![Ödül](https://img.shields.io/badge/W--code%202.0-Seçilen%20Proje-gold)](https://kodluyoruz.org/)
[![Lisans](https://img.shields.io/badge/lisans-MIT-blue)]()

> FAO AQUASTAT resmi verilerine dayanan; bölgeler ve ekonomik sektörler genelinde küresel tatlı su çekimi örüntülerini kapsamlı biçimde analiz eden bir veri projesi.

Bu proje, Ford Otosan "Gelecek Hayalim" ile Kodluyoruz iş birliğiyle yürütülen **W-code 2.0** programının mezuniyet bitirme projesi olarak geliştirilmiştir. **Coda Nova** ekibi tarafından hazırlanan analizde, 2019–2022 yılları arasındaki küresel su kullanım trendlerinden elde edilen veriler, sürdürülebilirlik odaklı içgörülere dönüştürülmüştür.

🏆 W-code 2.0 kapanış töreninde **Seçilen Proje** olarak sunulmuştur.

---

## İçindekiler

- [Temel Bulgular](#temel-bulgular)
- [Görselleştirmeler](#görselleştirmeler)
- [Teknoloji Yığını](#teknoloji-yığını)
- [Veri Kaynağı](#veri-kaynağı)
- [Proje Yapısı](#proje-yapısı)
- [Başlarken](#başlarken)
- [Ekip](#ekip)
- [Lisans](#lisans)

---

## Temel Bulgular

- **Tarım küresel ölçekte baskın:** Tarımsal su çekimi, dünya genelinde tatlı su kullanımının en büyük payını oluşturmakta olup sektörel dağılım bölgeden bölgeye önemli farklılıklar göstermektedir.
- **Türkiye analizi:** Türkiye'deki tarımsal, kentsel ve endüstriyel kullanım oranlarının karşılaştırmalı analizi, gelişmekte olan ekonomilerle tutarlı bir örüntü ortaya koymaktadır.
- **Bölgesel farklılıklar:** Doğu Asya'da tarım ağırlıklı; Kuzey Amerika'da endüstri ağırlıklı; Avrupa'da ise sektörler arasında daha dengeli bir dağılım gözlemlenmektedir.
- **Kişi başı tüketimi etkileyen faktörler:** Ülkeler arasındaki kişi başı su tüketimi farklılıklarını açıklayan başlıca etkenler nüfus yoğunluğu ve sanayileşme düzeyidir.
- **2019–2022 trendleri:** Dönemsel analiz, su kıtlığı yaşanan bölgelerdeki baskı noktalarının bu süreçte nasıl şekillendiğini gözler önüne sermektedir.

---

## Görselleştirmeler

> Not defteri aşağıdaki etkileşimli ve statik grafikleri içermektedir:

| Grafik Türü | Kütüphane | Açıklama |
|-------------|-----------|----------|
| Güneş ışını grafiği | Plotly | Kıta → Ülke → Sektör hiyerarşik dağılımı |
| Ağaç haritası | Plotly | Bölgesel su çekimi pay karşılaştırması |
| Çubuk grafikler | Matplotlib / Seaborn | Bölgeye göre sektörel kullanım |
| Zaman serisi | Matplotlib | 2019–2022 su çekimi trendleri |
| Isı haritası | Seaborn | Ülke bazında kişi başı kullanım örüntüleri |

Tüm görselleştirmeleri incelemek için not defterini açın:
👉 [`Global_Water_Usage_Analysis.ipynb`](../Global_Water_Usage_Analysis.ipynb)

---

## Teknoloji Yığını

| Kategori | Araçlar |
|----------|---------|
| Dil | Python 3.x |
| Veri işleme | Pandas, NumPy |
| Statik görselleştirme | Matplotlib, Seaborn |
| Etkileşimli grafikler | Plotly (Güneş ışını, Ağaç haritası) |
| Not defteri ortamı | Jupyter |

---

## Veri Kaynağı

Tüm veriler, 2019–2022 yılları arasındaki küresel su kullanımını kapsayan resmi **FAO AQUASTAT** istatistiklerinden alınmıştır.

- **Resmi veri tabanı:** [FAO AQUASTAT Ana Veri Tabanı](https://www.fao.org/aquastat/en/databases/maindatabase)
- **İşlenmiş veri seti:** [`AQUASTAT Dissemination System.csv`](AQUASTAT%20Dissemination%20System.csv)

---

## Proje Yapısı

```
global-water-usage-analysis/
├── AQUASTAT Dissemination System.csv   # FAO'dan alınan ham veri seti
├── Global_Water_Usage_Analysis.ipynb   # Ana analiz not defteri
├── requirements.txt                    # Python bağımlılıkları
└── README.md
```

---

## Başlarken

### Ön Koşullar

- Python 3.x
- Jupyter Notebook veya JupyterLab

### Kurulum

```bash
# Depoyu klonlayın
git clone https://github.com/elifyesilyurt/global-water-usage-analysis
cd global-water-usage-analysis

# Bağımlılıkları yükleyin
pip install -r requirements.txt

# Not defterini başlatın
jupyter notebook Global_Water_Usage_Analysis.ipynb
```

### Bağımlılıklar

```
pandas
numpy
matplotlib
seaborn
plotly
jupyter
```

---

## Ekip

| İsim | Rol | LinkedIn |
|------|-----|----------|
| Elif Yeşilyurt | Veri Analisti | [linkedin.com/in/elifyesilyurtt](https://www.linkedin.com/in/elifyesilyurtt/) |
| Ahsen Öztürk | Veri Analisti | [linkedin.com/in/ahsen-ozturk](https://www.linkedin.com/in/ahsen-ozturk/) |
| Esmahan Didinir | Veri Analisti | [linkedin.com/in/esmahan-didinir](https://www.linkedin.com/in/esmahan-didinir/) |
| Sedef Çakmak | Veri Analisti | [linkedin.com/in/sedef-cakmak](https://www.linkedin.com/in/sedef-cakmak/) |

Program boyunca gösterdiği mentörlük için eğitmenimiz **[Müşerref Özkan](https://www.linkedin.com/in/muserrefozkan/)**'a özel teşekkürlerimizi sunarız.

*W-code 2.0 · Ford Otosan Gelecek Hayalim × Kodluyoruz · Coda Nova Ekibi*

---

## Lisans

MIT © 2026 Coda Nova — Elif Yeşilyurt, Ahsen Öztürk, Esmahan Didinir, Sedef Çakmak

---

> 🇬🇧 [English Documentation](../README.md)
