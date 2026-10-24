# Antibiyotik Direncinin Yıllara Göre Değişiminin İncelenmesi

## Proje Özeti
Bu araştırmanın amacı, seçilen antibiyotiklere karşı *Escherichia coli* direnç oranlarının yıllara göre nasıl değiştiğini açık gözetim verileri üzerinden incelemektir. Çalışma, Araştırma Yöntem ve Teknikleri dersi kapsamında hazırlanmış bir araştırma önerisidir; analiz sonuçları henüz elde edilmemiştir.

## Problem Tanımı
Antibiyotik direnci, bakteriyel enfeksiyonların tedavisini zorlaştırabilen önemli bir halk sağlığı sorunudur. Bakterilerin antibiyotiklere karşı direnç oranları zaman içinde değişebilir. Açık erişimli gözetim verileri, belirli bakteri-antibiyotik kombinasyonlarındaki zamansal değişimlerin incelenmesine olanak tanır. Bu araştırmada, seçilen veri kaynağından elde edilen *Escherichia coli* direnç verilerinin Python kullanılarak incelenmesi ve direnç oranlarındaki zamansal eğilimlerin belirlenmesi amaçlanmaktadır.

## Araştırma Sorusu
Seçilen antibiyotiklere karşı *Escherichia coli* direnç oranları, incelenen yıllar boyunca nasıl değişmiştir?

## Hipotez
- **H0:** Seçilen dönemde *E. coli*'nin seçilen antibiyotiğe karşı direnç oranında istatistiksel olarak anlamlı bir zamansal eğilim yoktur.
- **H1:** Seçilen dönemde *E. coli*'nin seçilen antibiyotiğe karşı direnç oranında istatistiksel olarak anlamlı bir zamansal eğilim vardır.

Hipotez, veri seti ve uygun analiz yöntemi kesinleştirildikten sonra değerlendirilecektir.

## Planlanan Veri Seti
**Öncelikli kaynak:** European Centre for Disease Prevention and Control (ECDC), European Antimicrobial Resistance Surveillance Network (EARS-Net).

- ECDC veri ve rapor sayfası: https://www.ecdc.europa.eu/en/antimicrobial-resistance/surveillance-and-disease-data
- EARS-Net hakkında: https://www.ecdc.europa.eu/en/about-us/networks/disease-networks-and-laboratory-networks/ears-net-data
- Veri portalı açıklaması: https://data.europa.eu/data/datasets/antimicrobial-resistance-data

Veri seti, *E. coli* için seçilen antibiyotik grubuna ve yıllara ait karşılaştırılabilir direnç oranlarını içerecek şekilde seçilecektir. Kullanılacak yıl aralığı ve antibiyotik grubu, indirilebilir veriler kontrol edildikten sonra kesinleştirilecektir.

### Planlanan değişkenler
- Yıl
- Bakteri türü
- Antibiyotik / antibiyotik grubu
- Direnç oranı (%)
- Ülke veya bölge
- Varsa örnek/izolat sayısı

## Kullanılacak Yöntem ve Teknolojiler
- Python
- Pandas: veriyi temizleme, düzenleme ve özetleme
- Matplotlib: yıllara göre çizgi grafikleri oluşturma
- Keşifsel Veri Analizi (EDA)
- Verinin yapısına uygun istatistiksel eğilim analizi

## İş Planı
1. ECDC veri portalından uygun veri tablosunu bulmak ve veri kullanılabilirliğini doğrulamak.
2. Bakteri, antibiyotik grubu, coğrafi kapsam ve yıl aralığını kesinleştirmek.
3. Eksik değerleri, örnek sayısını ve yıllar arasındaki yöntem/raporlama farklılıklarını kontrol etmek.
4. Yıllara göre direnç oranlarını özetlemek ve grafiklerle göstermek.
5. Uygun istatistiksel eğilim analizini uygulamak.
6. Bulguları akademik kaynaklarla karşılaştırmak ve sınırlılıkları açıklamak.

## Sınırlılıklar
EARS-Net verileri belirli klinik örneklerden ve katılımcı laboratuvarların bildirimlerinden oluşur. Örnek sayısı, ülke kapsamı ve laboratuvar değerlendirme ölçütleri zaman içinde değişebileceğinden sonuçlar dikkatli yorumlanacaktır. Zamansal bir ilişki, tek başına antibiyotik kullanımının değişime neden olduğunu kanıtlamaz.

## Ön Akademik Kaynaklar
1. Aliabadi, S. et al. (2022). *Exploring temporal trends and risk factors for resistance in Escherichia coli-causing bacteraemia in England between 2013 and 2018: an ecological study.* Journal of Antimicrobial Chemotherapy, 77(3), 782–792. https://doi.org/10.1093/jac/dkab440
2. GBD 2021 Antimicrobial Resistance Collaborators. (2024). *Global burden of bacterial antimicrobial resistance 1990–2021: a systematic analysis with forecasts to 2050.* The Lancet, 404(10459), 1199–1226. https://doi.org/10.1016/S0140-6736(24)01867-1
3. Goleanu Vasiloiu, C. D. et al. (2025). *Trends in Antibiotic Resistance of Escherichia coli Strains Isolated from Clinical Samples (2019–2023): A Hospital-Based Retrospective Analysis.* Pathogens, 14(9), 927. https://doi.org/10.3390/pathogens14090927

## Sonraki Adımlar
- Veri setini ve lisans/kullanım koşullarını doğrulamak.
- README güncellemesini ve araştırma önerisini haftalık ilerlemeye göre düzenlemek.
- Veri indirme ve analiz adımlarını ilerleyen haftalarda eklemek.
