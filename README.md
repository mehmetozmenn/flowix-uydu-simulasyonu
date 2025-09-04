# 🌍 Flowix — Gerçek Zamanlı 3B Uydu Simülasyonu ve Yer İstasyonu Etkileşimi

![Flowix Banner](https://github.com/mehmetozmenn/flowix-uydu-simulasyonu/blob/main/Flowix.png?raw=true)
---

## 👥 Takım Bilgileri

**Takım Adı:** Flowix  
**Yarışma:** T.C. Çevre, Şehircilik ve İklim Değişikliği Bakanlığı — **TEKNOFEST Geleceğin Sürdürülebilir Şehirleri Hackathonu**  
**Alt Kategori:** Uydu Simülasyonu (CesiumJS): Uydu ve Yer İstasyonu Veri Alışverişi Modellemesi

**Takım Üyeleri:**
- 👨‍💻 İsmail Karaca – Maltepe Üniversitesi
- 👨‍💻 Mehmet Özmen – Harran Üniversitesi
- 👩‍💻 Berrin Karaca – Doğuş Üniversitesi
- 👨‍💻 Hasan Taşdemir – İstanbul Teknik Üniversitesi (İTÜ)

---

## 📌 Proje Demosu

🛰️ **Canlı Uygulama:** [https://flowix-e9xz.vercel.app/](https://flowix-e9xz.vercel.app/)  
🌐 Uygulama herhangi bir tarayıcıda çalışır. CesiumJS motoru yüklenene kadar birkaç saniye bekleyiniz.

---

## 📌 Projenin Amacı ve Tanımı

**Flowix**, küresel ve yerli uydu takımyıldızlarını 3 boyutlu olarak simüle eden, **konuma duyarlı** ve **veri alışverişi modellemesi** sağlayan modern bir web platformudur.

**CesiumJS** ve **satellite.js** teknolojileri ile geliştirilen Flowix, özellikle sürdürülebilir şehir planlamasında uzay teknolojilerinin rolünü artırmayı, konumlandırma ve veri aktarımına dayalı çözümler üretmeyi hedeflemektedir.

---

## 🛰️ Temel Özellikler

### 📡 1. Gerçek Zamanlı Uydu Takibi
- Starlink, Türksat, Galileo, GLONASS gibi büyük uydu takımyıldızlarının anlık hareketleri
- TLE (Two-Line Element) verileriyle doğruluk garantili yörünge hesaplamaları
- Her bir uydu için: adı, tipi, ülke kodu, görev amacı bilgileri

### 🗺️ 2. Yer İstasyonu Etkileşimi
- Belirli coğrafi noktalarda tanımlı yer istasyonları (örn. Ankara, Erzurum, İstanbul)
- Görüş hattı (line-of-sight) hesaplamaları
- Uydularla eşzamanlı iletişim penceresi simülasyonu (visibility window)
- Kapsama alanı modellemesi

### 🌐 3. **Konum Erişimi ve Dünya ile Etkileşim**
- Kullanıcının konumuna erişim (tarayıcı izinli)
- Harita üzerinde kendi konumunuzu gösterme ve ona göre uydu görünürlüğü
- Dünya üzerindeki tüm noktalarla uydu görünürlük etkileşimi (ör. New York, Tokyo, Adıyaman)
- Kamera kilitleme ve perspektif değiştirme seçenekleri
- **Zaman çizelgesi** ile geçmiş–gelecek senaryo simülasyonu

### 💬 4. Chatbot ve Eğitim Paneli
- Uydularla ilgili temel bilgileri veren bilgi penceresi
- "Bu uydu ne işe yarıyor?", "Starlink neden önemli?" gibi sık sorular
- Genç kullanıcılar ve öğrenciler için anlaşılır veri sunumu

### ☁️ 5. Hava Durumu ve Parlaklık Filtresi
- En parlak uyduları filtreleme (gözlemlenebilirlik için)
- Hava durumu katmanı ile kullanıcı lokasyonunda netlik değerlendirmesi
- Basit astronomi eğitimi için entegre veri katmanları

---

## ⚙️ Kullanılan Teknolojiler

| Teknoloji | Açıklama |
|----------|----------|
| **CesiumJS** | 3D dünya motoru (WebGL tabanlı) |
| **satellite.js** | TLE verilerinden yörünge hesaplama |
| **CelesTrak API** | TLE verilerinin güncel kaynağı |
| **JavaScript** | Ana programlama dili |
| **Webpack** | Modül paketleme sistemi |
| **HTML/CSS** | Kullanıcı arayüzü |
| **Vercel** | Deploy ve canlı sunum |

---

## 📍 Konum, Katman ve Etkileşim Detayları

- Kullanıcı konumuna göre özel uydu eşleşmesi
- Harita üstünde uydu–yer istasyonu–kullanıcı arasındaki çizgisel ilişki
- Zamanın ilerletilmesiyle senaryo bazlı test imkanı (ör. “yarın saat 20.00’de hangi uydu Ankara’dan geçiyor?”)
- Kamera navigasyonu ile belirli bir uyduya ya da istasyona odaklanma
- Konum bilgisiyle veri alışverişi analiz potansiyeli: afet, haberleşme, ulaşım

---

## 🌱 Katkı ve Toplumsal Yarar

Flowix, uzay teknolojilerini sadece bilimsel amaçlarla değil; **sürdürülebilir şehircilik**, **afet yönetimi**, **haberleşme altyapısı**, **kırsal alan dijitalleşmesi** gibi kritik alanlara entegre etmektedir.

### 🇹🇷 Yerli ve Milli Hedeflere Katkı:
- **Türksat** uydularının simülasyonla entegre edilmesi
- Türkiye’deki şehirler için konum-temelli analiz senaryoları
- Yerli yazılım altyapısıyla geliştirilen bir çözüm olarak katkı sağlama

---

## 💡 Potansiyel Geliştirmeler

- Yer istasyonları ile yük tahmini, bağlantı hızı tahmini gibi AI destekli analizler
- Uydular arası mesh bağlantı modellemesi
- 3B veri analiz panelleri ile şehir–uydu etkileşim haritaları
- Eğitim modülü: ortaokul/lise seviyesine uygun etkileşimli uydu keşif aracı

---

## 🙏 Teşekkür

Bu projede özveriyle çalışan ekip arkadaşlarımıza, desteklerini esirgemeyen mentorlarımıza ve bu güzel hackathonu organize eden kurumlara teşekkürü borç biliriz:

- **Takım arkadaşlarımıza:** İsmail, Mehmet, Berrin, Hasan  
- **CoderSpace** ekibine: Hackathon sürecinde sundukları altyapı ve destek için  
- **T.C. Çevre, Şehircilik ve İklim Değişikliği Bakanlığı’na:** Bu vizyoner yarışma için  
- **T3 Vakfı’na:** Gençlerin potansiyelini ortaya çıkaran destek yapısı için  
- **Mentorlarımıza:** Teknik ve stratejik rehberlikleri için

---

## 📬 İletişim

Her türlü soru, öneri veya iş birliği için bizimle iletişime geçebilirsiniz.  

---

## 📄 Lisans

Bu proje, TEKNOFEST yarışması kapsamında teslim edilmekte olup açık kaynak değildir. Kullanım ve geliştirme hakları proje ekibine ve yarışma şartnamesine tabidir.

---
