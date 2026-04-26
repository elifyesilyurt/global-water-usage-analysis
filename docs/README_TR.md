# Küresel Su Kullanımı Analizi

**Küresel tatlı su çekimi modellerinin bölgeler ve ekonomik sektörler bazında, resmi FAO AQUASTAT verilerine dayanan kapsamlı veri analizi.**

Bu proje, **Ford Otosan "Gelecek Hayalim"** ve **Kodluyoruz** iş birliğiyle yürütülen **W-code 2.0** programının mezuniyet bitirme projesi olarak geliştirilmiştir. **Coda Nova** ekibi tarafından hazırlanan bu çalışma, 2019-2022 yılları arasındaki küresel su kullanımı trendlerinden sürdürülebilirlik odaklı, uygulanabilir içgörüler sunmaktadır.

🏆 *W-code 2.0 kapanış töreninde "Seçilen Proje" ödülüne layık görülmüştür.*

---

## İçindekiler
* [Temel Bulgular](#temel-bulgular)
* [Görselleştirmeler](#görselleştirmeler)
* [Teknoloji Yığını](#teknoloji-yığını)
* [Veri Kaynağı](#veri-kaynağı)
* [Proje Yapısı](#proje-yapısı)
* [Başlangıç](#başlangıç)
* [Ekip](#ekip)
* [Lisans](#lisans)

---

## Temel Bulgular
* **Tarım Küresel Lider:** Tarımsal su çekimi, dünya genelinde tatlı su kullanımının en büyük payını oluşturmaktadır; ancak sektörel dağılımda bölgeler arasında ciddi farklılıklar görülmektedir.
* **Türkiye Analizi:** Türkiye’deki tarımsal, belediye ve endüstriyel kullanım oranlarının karşılaştırmalı analizi, gelişmekte olan ekonomilerle tutarlı bir model sergilemektedir.
* **Bölgesel Zıtlıklar:** Doğu Asya tarım odaklıyken; Kuzey Amerika endüstri odaklıdır; Avrupa ise sektörler arasında daha dengeli bir dağılım göstermektedir.
* **Kişi Başına Kullanım:** Nüfus yoğunluğu ve sanayileşme düzeyi, ülkeler arasındaki kişi başı su tüketimi farklarını açıklayan temel faktörlerdir.
* **2019–2022 Trendleri:** Zamansal analiz, bu dönemde su kıtlığı çeken bölgelerde ortaya çıkan yeni stres noktalarını vurgulamaktadır.

---

## Görselleştirmeler
Not defteri (notebook), aşağıdaki etkileşimli ve statik grafikleri içermektedir:

| Grafik Türü | Kütüphane | Açıklama |
| :--- | :--- | :--- |
| **Sunburst (Güneş Patlaması)** | Plotly | Kıta → Ülke → Sektör bazında hiyerarşik kırılım |
| **Treemap (Ağaç Haritası)** | Plotly | Bölgesel su çekimi paylarının karşılaştırması |
| **Sütun Grafikleri** | Matplotlib / Seaborn | Bölge bazlı sektörel kullanım |
| **Zaman Serisi** | Matplotlib | 2019–2022 su çekimi trendleri |
| **Isı Haritası (Heatmap)** | Seaborn | Ülke düzeyinde kişi başına kullanım modelleri |

Tüm görselleştirmeleri incelemek için not defterini açın: 
👉 `Global_Water_Usage_Analysis.ipynb`

---

## Teknoloji Yığını
* **Dil:** Python 3.x
* **Veri Manipülasyonu:** Pandas, NumPy
* **Statik Görselleştirme:** Matplotlib, Seaborn
* **Etkileşimli Grafikler:** Plotly (Sunburst, Treemap)
* **Ortam:** Jupyter Notebook

---

## Veri Kaynağı
Tüm veriler, 2019-2022 yılları arasındaki küresel su kullanımını kapsayan resmi **FAO AQUASTAT** istatistiklerinden alınmıştır.

* **Resmi Veritabanı:** [FAO AQUASTAT Ana Veritabanı](https://www.fao.org/aquastat/en/databases/maindatabase/)
* **İşlenen Veri Seti:** `AQUASTAT Dissemination System.csv`

---

## Proje Yapısı
```text
global-water-usage-analysis/
├── AQUASTAT Dissemination System.csv   # FAO'dan alınan ham veri seti
├── Global_Water_Usage_Analysis.ipynb   # Ana analiz not defteri
├── requirements.txt                    # Python bağımlılıkları
└── README.md                           # Proje açıklaması

Başlangıç
Önkoşullar
Python 3.x

Jupyter Notebook veya JupyterLab

Kurulum
# Depoyu klonlayın
git clone [https://github.com/elifyesilyurt/global-water-usage-analysis](https://github.com/elifyesilyurt/global-water-usage-analysis)
cd global-water-usage-analysis

# Bağımlılıkları yükleyin
pip install -r requirements.txt

# Not defterini başlatın
jupyter notebook Global_Water_Usage_Analysis.ipynb



## Takım

| İsim | Rol | LinkedIn |
|------|------|----------|
| Elif Yeşilyurt | Data Analyst | [linkedin.com/in/elifyesilyurtt](https://www.linkedin.com/in/elifyesilyurtt/) |
| Ahsen Öztürk | Data Analyst | [linkedin.com/in/ahsen-ozturk](https://www.linkedin.com/in/ahsen-ozturk/) |
| Esmahan Didinir | Data Analyst | [linkedin.com/in/esmahan-didinir](https://www.linkedin.com/in/esmahan-didinir/) |
| Sedef Çakmak | Data Analyst | [linkedin.com/in/sedef-cakmak](https://www.linkedin.com/in/sedef-cakmak/) |

Özel Teşekkür: Program boyunca bizlere yol gösteren ve mentorluk yapan eğitmenimiz **[Müşerref Özkan'a](https://www.linkedin.com/in/muserrefozkan/)** teşekkürlerimizi sunarız.

*W-code 2.0 · Ford Otosan Gelecek Hayalim × Kodluyoruz · Takım Coda Nova*

---

## Lisans

MIT © 2026 Coda Nova — Elif Yeşilyurt, Ahsen Öztürk, Esmahan Didinir, Sedef Çakmak

---
