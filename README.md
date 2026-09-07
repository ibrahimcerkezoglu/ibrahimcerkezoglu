# İbrahim Çerkezoğlu

Full Stack Developer — .NET Core & SQL Server odaklı, yapay zekâ entegrasyonlu web ve mobil sistemler geliştiriyorum.
Bilgisayar Mühendisliği (Lisans) · Uzaktan / Hibrit çalışmaya uygun · Türkçe (Ana Dil) · English (B1)

<p>
  <a href="https://ibrahimcerkezoglu.dev">
    <img src="https://img.shields.io/badge/🌐_Portfolyo_Sitem-Case_Study'ler_%7C_CV_%7C_İletişim-a855f7?style=for-the-badge&logoColor=white" alt="ibrahimcerkezoglu.dev" />
  </a>
</p>

Karmaşık iş süreçlerini (pazaryerleri, muhasebe/ödeme sistemleri, admin panelleri) ölçeklenebilir mimarilere dönüştürüyor, yapay zekâyı gerçek ürünlere entegre ediyorum. Aşağıdaki projelerin çoğu 3+ yıldır aktif geliştirdiğim, gerçek kullanıcıları olan sistemler — **detaylı case study'ler (mimari kararlar, istatistikler, öne çıkan mühendislik) için [ibrahimcerkezoglu.dev](https://ibrahimcerkezoglu.dev) adresine bakabilirsiniz.**

---

## Projeler

**Sosyal-Ticaret Pazaryeri**
Çok satıcılı bir e-ticaret pazaryeri: canlı yayın üzerinden satış, gerçek zamanlı açık artırma, influencer programı, kupon/cüzdan sistemi. 82 controller, 96 veritabanı migration'ı ve 3 SignalR hub (chat, auction, bildirim) üzerine kurulu. OpenAI embedding'leriyle çalışan bir ürün öneri motoru (vektör arama), ONNX Runtime ile otomatik arka plan kaldırma ve 3D/AR ürün önizleme içeriyor.
`ASP.NET Core` `Angular` `SignalR` `OpenAI Embeddings` `ONNX Runtime`

**Sosyal Medya/Oyun Coin Bayileri için Muhasebe & Ödeme Otomasyonu**
TikTok tarzı platformlarda kullanılan sanal (uygulama içi) coin bayileri için geliştirdiğim, ~70.000 satırlık bir muhasebe ve ödeme mutabakat sistemi. Banka makbuz tarayıcıları, ödeme sağlayıcıları ve e-fatura dahil 8 farklı dış servisle entegre çalışan arka plan worker'ları, gerçek zamanlı makbuz bildirimleri için bir SignalR hub'ı. 67+ aşamalı migration geçmişiyle uzun süredir aktif geliştiriliyor.
`ASP.NET Core` `EF Core` `SignalR` `Background Workers`

**AI Destekli Freelancer Pazaryeri**
TÜBİTAK 2209-A destekli bir girişimde geliştirdiğim, freelancer marketplace. İlan, teklif, sipariş, ödeme akışları; rol bazlı admin paneli; SignalR ile gerçek zamanlı mesajlaşma. Yerel LLM (Ollama, Qwen Coder) ile çalışan bir AI ilan koçu ve sohbet botu içeriyor. CSRF koruması ve geçici hata toleransı gibi kararlar kod içinde açıkça gerekçelendirilmiş.
`ASP.NET Core` `SignalR` `Local AI / Ollama` `Google OAuth`

**Aria — Yerel (Offline) Kişisel AI Asistanı**
Tamamen çevrimdışı çalışan, gizlilik odaklı bir kişisel asistan. 5 farklı yerel LLM modeli arasında görev tipine göre yönlendirme yapan bir router, ChromaDB tabanlı vektör hafıza (RAG), sesli komut (Whisper + Piper TTS) ve ekran görüntüsü analizi. Bilgisayarı sesle kontrol edebildiği için, tehlikeli komutları (`rm -rf`, `powershell -enc` vb.) engelleyen iki katmanlı bir güvenlik filtresi tasarladım.
`Python` `FastAPI` `Ollama` `ChromaDB` `Whisper`

**CellScope — Hücre Sinyali Geolocation Motoru**
Lisanslı, kapalı kaynak bir masaüstü uygulamasına gömülü modül olarak geliştirdiğim bir telekom sinyal analizi motoru. Sinyal gücü (RSRP) ağırlıklandırması, zaman avansı (TA) mesafe halkaları ve sektör açısı doğrulamasıyla 0-100 arası konum güven skoru üretiyor. Unit ve e2e testleri mevcut.
`Python` `FastAPI` `Polars` `DuckDB` `React` `Leaflet`

**Otomatik İlan Takip & Analiz Botu**
Bot tespitini aşan (stealth) tarayıcı otomasyonuyla ikinci el ilan sitelerini tarayan, her ilanı bir LLM ile ayrıştırıp (km, yıl, hasar kaydı, değişen parça) kullanıcı tanımlı kriterlere göre filtreleyen bir izleme sistemi. Yeni radar ekleme, kriter güncelleme gibi tüm ayarlar Telegram bot komutlarıyla, yeniden deploy gerekmeden yönetilebiliyor.
`Python` `Playwright` `LLM Parsing` `Telegram Bot`

**AI Destekli İş Takip Botu**
Serbest çalışma platformlarındaki iş fırsatlarını takip eden, GPT ile teklif taslakları hazırlayan ve müşteri sohbetlerini yöneten bir otomasyon botu. Botun ne zaman "sıkıştığını" (fiyat pazarlığı, teknik soru, iptal talebi) tespit edip konuşmayı otomatik olarak bana devrettiği bir karar mekanizması var; başarılı sonuçlanan konuşmalar da gelecekteki teklifler için örnek olarak hafızaya kaydediliyor.
`Python` `Playwright` `OpenAI API` `Telegram Bot`

**Gym Mobile — Spor Salonu Yönetim Uygulaması**
Antrenman takibi, diyet planı, ölçüm geçmişi, ödeme ve QR kod ile turnike giriş/çıkış entegrasyonu barındıran, iOS ve Android'de push bildirimleriyle (OneSignal) yayına hazır React Native uygulaması.
`React Native` `Redux` `OneSignal`

**CRM & WooCommerce Senkronizasyon Platformu**
Bir e-ticaret markası için geliştirdiğim arka ofis CRM'i: sipariş, stok, RMA, POS ve fatura yönetimi. WooCommerce ile çift yönlü sipariş/stok senkronizasyonu, kargo sağlayıcısı webhook entegrasyonu ve e-fatura API'si. Groq LLM ile günde iki kez otomatik blog içeriği üretip WordPress'e yayınlayan zamanlanmış bir iş de içeriyor. 71 migration ile uzun süredir aktif.
`ASP.NET Core` `EF Core` `Hangfire` `WooCommerce API` `Groq LLM`

**Perde Mağazaları için B2B Lisans & Tedarik Yönetimi**
Birden fazla mağaza, depo ve tedarikçiyi tek çatı altında yöneten bir B2B sistemi. Mağaza başına lisans kodu takibi ve süresi dolmadan 30/7 gün önce otomatik e-posta uyarısı gönderen zamanlanmış bir servis; tedarikçi fiyat değişikliği taleplerinin onay akışı; QR/barkod ile fiyat/stok sorgulama.
`ASP.NET Core` `EF Core` `Hangfire` `QRCoder`

**Restoran Sipariş & Rezervasyon Sistemi**
Menü yönetimi, online sipariş (PayPal + kapıda ödeme), sepet/checkout ve masa rezervasyonu barındıran, Angular (SSR) + ASP.NET Core ile geliştirdiğim bir restoran platformu.
`Angular (SSR)` `ASP.NET Core` `PayPal`

**SMS / WhatsApp Toplu Mesajlaşma Gateway'i**
Kurumsal toplu SMS ve WhatsApp mesajlaşması için admin panelli bir gateway. ASP.NET Core yönetim paneli, WhatsApp Web protokolü üzerinden çalışan ayrı bir Node.js köprü servisiyle koordineli çalışıyor.
`ASP.NET Core` `Node.js` `WhatsApp Bridge`

Bu liste sadece öne çıkanlar — **[ibrahimcerkezoglu.dev/#projects](https://ibrahimcerkezoglu.dev/#projects)** adresinde 28 projenin tamamı, kategoriye göre filtreleme ve her biri için ayrı case study sayfası var.

---

## Deneyim & Diğer Çalışmalar

- **Koresan.com / smart.koresan.com** — Çok kanallı e-ticaret altyapısını yönetiyorum: Trendyol, Hepsiburada ve WooCommerce/WordPress arasında ürün, stok ve sipariş senkronizasyonunu sağlayan API entegrasyonlarını kurdum ve sürdürüyorum.
- **Büyük ölçekli üretim/tedarik tesisi (IT Stajı)** — 1000+ çalışana 20 dakikada toplu SMS/WhatsApp gönderebilen rate-limitli bir mesajlaşma sistemi ve HSE için sertifika takip sistemi geliştirdim; 650+ cihazın domain geçiş operasyonuna destek verdim.
- **Freelance** — Perde mağazası, restoran ve elektrik servisi gibi farklı sektörlere özel CRM/admin panel sistemleri; bir markanın WooCommerce altyapısını Cloudflare + cache optimizasyonuyla hızlandırdım.
- **Kurumsal danışmanlık (PMO Stajı)** — Kurumsal GenAI/Copilot kullanım senaryoları üzerine araştırma ve sunum.

Ayrıca bir 3D model pazaryeri ve sertifikalı eğitim/uyumluluk platformu gibi tamamlanmış başka projelerim de var.

Detaylı iş deneyimi ve referanslar için [LinkedIn profilime](https://www.linkedin.com/in/ibrahimcerkezoglu/) göz atabilirsiniz.

---

## Teknolojiler

![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET_Core-512BD4?style=flat&logo=dotnet&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white)
![WordPress](https://img.shields.io/badge/WordPress_/_WooCommerce-21759B?style=flat&logo=wordpress&logoColor=white)
![Ollama](https://img.shields.io/badge/Local_AI_/_Ollama-000000?style=flat&logo=ollama&logoColor=white)

---

## İletişim

[![Website](https://img.shields.io/badge/Website-ibrahimcerkezoglu.dev-a855f7?style=flat&logo=googlechrome&logoColor=white)](https://ibrahimcerkezoglu.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ibrahimcerkezoglu/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:cerkezogluibrahim@gmail.com)
[![CV](https://img.shields.io/badge/CV_İndir-06b6d4?style=flat&logo=readdotcv&logoColor=white)](https://ibrahimcerkezoglu.dev/cv/ibrahim-cerkezoglu-cv.pdf)
