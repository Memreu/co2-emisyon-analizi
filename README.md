# 🌍 Küresel CO₂ Emisyonları Analizi — Türkiye Odaklı

Our World in Data'nın 1750–2024 CO₂ verisiyle hazırlanmış, **tamamen interaktif** (Plotly) bir JupyterLab veri analizi projesi.

👉 **İnteraktif hâliyle görüntüle:** [nbviewer](https://nbviewer.org/github/Memreu/co2-emisyon-analizi/blob/main/co2_emisyon_analizi.ipynb)
*(GitHub, Plotly grafiklerini notebook önizlemesinde göstermez; nbviewer ya da JupyterLab'de açın.)*

## İçerik

- 🗺️ Yıl kaydırıcılı, animasyonlu **dünya haritası** (kişi başı emisyon, 1990–2024)
- 📊 Toplam / kişi başı / kümülatif arasında geçiş yapılabilen **en büyük emitörler** grafiği
- 🇹🇷 Türkiye: kaynak kırılımı ve dünya, AB, Çin ile karşılaştırma
- 📈 Ülke seçilebilen **GSYİH vs CO₂ (decoupling)** analizi
- 🫧 Gapminder tarzı **animasyonlu balon grafik**
- 🤖 **K-Means** ile ülke kümeleme (siluet skoruyla k seçimi)
- 🔮 Bootstrap güven aralıklı **2030 projeksiyonu**

## Öne çıkan bulgular

- Küresel emisyon 2024'te **~38,6 milyar ton**, 1990'a göre **%70 fazla**; kömür hâlâ ilk sırada (%41).
- Türkiye dünyada **12. sırada**; emisyonu 1990'dan beri **3,3 kat** arttı.
- Türkiye'nin kişi başı emisyonu (**5,9 t**), dünya ortalamasını (4,7 t) ve AB'yi (5,4 t) geçti.
- Türkiye'de göreli ayrışma var: GSYİH ~4,9 kat, CO₂ ~2,9 kat büyüdü (1990–2022).
- Mevcut eğilim sürerse 2030'da **~559 Mt** (%90 aralık 540–579 Mt).

## Çalıştırma

```bash
git clone https://github.com/Memreu/co2-emisyon-analizi.git
cd co2-emisyon-analizi
pip install -r requirements.txt
jupyter lab
```

`co2_emisyon_analizi.ipynb` dosyasını açıp **Run ▸ Run All Cells** deyin. Veri seti (~14 MB) ilk çalıştırmada otomatik indirilir.

## Veri kaynağı

Our World in Data — *CO₂ and Greenhouse Gas Emissions*, [github.com/owid/co2-data](https://github.com/owid/co2-data) (CC BY 4.0)
