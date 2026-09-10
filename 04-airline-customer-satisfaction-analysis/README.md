# ✈️ Havayolu Müşteri Memnuniyeti Analizi

## Proje Hakkında

Bu projede, havayolu yolcularına ait müşteri memnuniyeti verileri **Microsoft Excel** kullanılarak analiz edilmiştir.

Analizin ana odağı:

- Business Class müşteri deneyimi
- Satisfaction Map analizi
- Uçuş mesafesi ve sınıf ilişkisi
- Yaş ve cinsiyet segmentasyonu
- Gecikme ve zaman uygunluğu analizi
- Business insight ve aksiyon önerileri

Bu çalışmada amaç yalnızca ortalama skorları hesaplamak değil, analiz sonuçlarını **iş kararlarına dönüştürülebilecek içgörülere** çevirmektir.

---

## Veri Seti

Veri setinde toplam **103.904 yolcu kaydı** bulunmaktadır.

Başlıca değişkenler:

- Gender
- Age
- Type of Travel
- Class
- Flight Distance
- Inflight Wi-Fi Service
- Departure / Arrival Time Convenience
- Ease of Online Booking
- Gate Location
- Food and Drink
- Online Boarding
- Seat Comfort
- Inflight Entertainment
- On-board Service
- Leg Room Service
- Baggage Handling
- Check-in Service
- Inflight Service
- Cleanliness
- Departure Delay
- Arrival Delay
- Satisfaction
- NPS

Business Class müşterileri ayrıca ayrı olarak detaylı incelenmiştir.

---

# Analizler ve Temel Bulgular

## 1. Business Class Memnuniyet Analizi

Business Class müşterilerinde en yüksek memnuniyet skorları:

| Hizmet Kriteri | Memnuniyet |
|---|---:|
| Baggage Handling | **%85,4** |
| Inflight Service | **%81,8** |
| Online Boarding | **%70,9** |
| On-board Service | **%70,2** |
| Leg Room Service | **%68,6** |

En düşük memnuniyet skorları:

| Hizmet Kriteri | Memnuniyet |
|---|---:|
| Inflight Entertainment | **%48,6** |
| Seat Comfort | **%48,8** |
| Departure / Arrival Time Convenience | **%50,3** |
| Ease of Online Booking | **%50,6** |
| Gate Location | **%51,8** |

### Business Insight

Operasyonel hizmetlerde memnuniyet güçlü görünmektedir.

Ancak Business Class deneyiminin premium algısını doğrudan etkileyen **Seat Comfort** ve **Inflight Entertainment** kriterleri en düşük memnuniyet alanları arasında yer almaktadır.

Bu durum, ana geliştirme fırsatının operasyonel süreçlerden çok **premium uçuş deneyiminde** olduğunu göstermektedir.

---

## 2. Satisfaction Map Analizi

Hizmet kriterleri iki boyutta değerlendirilmiştir:

- **Önem**
- **Memnuniyet**

### Öne Çıkan Bulgular

**Inflight Entertainment**

- Önem: **0,582**
- Memnuniyet: **%48,6**

Inflight Entertainment, yüksek önem ve düşük memnuniyet kombinasyonu nedeniyle öncelikli geliştirme alanlarından biri olarak öne çıkmaktadır.

### Business Insight

Her düşük memnuniyet skoru aynı önceliğe sahip değildir.

En kritik alanlar:

> **Yüksek Önem + Düşük Memnuniyet**

kombinasyonunda bulunan kriterlerdir.

Bu nedenle Inflight Entertainment, yalnızca düşük puan aldığı için değil, müşteri açısından yüksek önem taşıdığı için stratejik öncelik taşımaktadır.

---

## 3. Class ve Flight Distance İlişkisi

| Class | Kısa Uçuş | Orta Uçuş | Uzun Uçuş |
|---|---:|---:|---:|
| Business | %21,8 | %21,9 | **%56,3** |
| Economy | %43,7 | %44,2 | %12,1 |
| Economy Plus | %45,4 | %41,5 | %13,1 |

### Business Insight

Business Class müşterilerinin yarısından fazlası uzun mesafeli uçuşlarda yer almaktadır.

Economy ve Economy Plus müşterileri ise ağırlıklı olarak kısa ve orta mesafeli uçuşlarda yoğunlaşmaktadır.

Bu nedenle premium deneyim iyileştirmelerinin özellikle **uzun mesafeli Business Class uçuşlarında** önceliklendirilmesi daha yüksek iş değeri yaratabilir.

---

## 4. Yaş ve Cinsiyet Segmentasyonu

Analizde dört hizmet kriteri yaş ve cinsiyete göre karşılaştırılmıştır:

- Inflight Wi-Fi
- Inflight Entertainment
- Seat Comfort
- Cleanliness

### Genel Cinsiyet Sonuçları

| Kriter | Kadın | Erkek |
|---|---:|---:|
| Inflight Wi-Fi | 3,63 | 3,61 |
| Inflight Entertainment | 2,82 | 2,83 |
| Seat Comfort | 2,88 | 2,86 |
| Cleanliness | 3,48 | 3,49 |

### Business Insight

Kadın ve erkek müşterilerin memnuniyet skorları birbirine oldukça yakındır.

Bu nedenle cinsiyet, müşteri deneyimini açıklamada güçlü bir ayrıştırıcı değişken olarak görünmemektedir.

Yaş segmentleri ise daha anlamlı farklılıklar göstermektedir.

Ayrıca Inflight Entertainment ve Seat Comfort kriterlerinin farklı analizlerde tekrar düşük skor üretmesi, bu alanların önemini artırmaktadır.

---

## 5. Departure / Arrival Time Convenience Analizi

| Uçuş Tipi | Convenience Skoru | Departure Delay | Arrival Delay |
|---|---:|---:|---:|
| Kısa Uçuş | 54,8 | 14,22 dk | 14,87 dk |
| Orta Uçuş | **57,2** | **15,65 dk** | **15,99 dk** |
| Uzun Uçuş | **52,8** | 14,58 dk | 14,67 dk |

### Business Insight

Orta mesafeli uçuşlarda ortalama gecikme daha yüksek olmasına rağmen zaman uygunluğu memnuniyeti de en yüksek seviyededir.

Bu sonuç:

> **Gecikme süresinin tek başına müşteri tarafından algılanan zaman uygunluğunu açıklamadığını**

göstermektedir.

Müşteri algısında aşağıdaki faktörler de etkili olabilir:

- Kalkış saati
- Varış saati
- Bağlantı seçenekleri
- Uçuş programı esnekliği

---

# Çapraz Analiz

Projede en güçlü içgörü, farklı analizlerin birlikte değerlendirilmesiyle ortaya çıkmaktadır.

**Business Class**
→ müşterilerin önemli bölümü uzun uçuşlarda

**Uzun Uçuş**
→ müşteri uçakta daha uzun süre geçiriyor

**Business Class Memnuniyeti**
→ Seat Comfort ve Inflight Entertainment düşük

**Satisfaction Map**
→ Inflight Entertainment aynı zamanda yüksek önem taşıyor

### Ana Business Sonucu

> **En güçlü müşteri deneyimi geliştirme fırsatı, uzun mesafeli Business Class uçuşlarındaki premium kabin deneyimidir.**

Bu sonuç yalnızca tek bir Pivot Table'dan değil;

**Müşteri Segmenti + Uçuş Davranışı + Memnuniyet + Hizmet Önemi**

birlikte değerlendirilerek elde edilmiştir.

---

# İş Önerileri

## 1. Inflight Entertainment Deneyimini İyileştirme

- İçerik çeşitliliğini artırma
- Mobil cihaz erişimini geliştirme
- Yaş segmentlerine göre içerik kategorileri oluşturma
- Entertainment sisteminin kullanım kolaylığını iyileştirme

---

## 2. Seat Comfort İyileştirmesi

- Uçak ve koltuk tipi bazında memnuniyet analizi
- Koltuk ergonomisinin değerlendirilmesi
- Uzun mesafeli Business Class uçuşlarının önceliklendirilmesi
- İyileştirme sonrası skorların düzenli takip edilmesi

---

## 3. Long-Haul Business Deneyimine Odaklanma

Business Class müşterilerinin **%56,3'ünün uzun uçuşlarda** yer alması nedeniyle premium deneyim yatırımlarının ilk olarak long-haul uçuşlarda uygulanması önerilmektedir.

---

## 4. Yaş Bazlı Segmentasyon

Cinsiyet farklılıkları düşük olduğu için müşteri segmentasyonunda:

- Yaş
- Uçuş mesafesi
- Class
- Travel Type

değişkenlerinin birlikte değerlendirilmesi daha anlamlı olabilir.

---

## 5. Schedule Convenience Analizini Derinleştirme

Gecikme süresinin tek başına yeterli açıklayıcı olmaması nedeniyle gelecekte:

- Uçuş saatleri
- Bağlantı yapısı
- Hat özellikleri
- Kalkış / varış zamanları

gibi değişkenlerle analiz derinleştirilebilir.

---

# Kullanılan Araçlar ve Yöntemler

### Microsoft Excel

- Pivot Table
- Veri filtreleme
- Segmentasyon
- Memnuniyet skorlaması
- Satisfaction Map
- Tanımlayıcı analiz
- Veri görselleştirme
- Business insight üretimi

---

# Proje Dosyaları

```text
04-havayolu-musteri-memnuniyeti-analizi/
│
├── README.md
├── Airline_Customer_Satisfaction_Analysis.xlsx
└── Airline_Customer_Satisfaction_Executive_Deck.pdf
