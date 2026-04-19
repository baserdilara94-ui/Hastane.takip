# 🏥 NöbetZeka - Akıllı Klinik Vardiya Sistemi

NöbetZeka, sağlık çalışanları (hekimler, hemşireler, vb.) için tasarlanmış, modern ve etkileşimli bir klinik vardiya ve nöbet yönetim sistemidir. Sistem, kullanıcı dostu arayüzü ve akıllı yorgunluk algoritması ile nöbet süreçlerini daha güvenli ve düzenli hale getirmeyi amaçlar.

## 🌟 Özellikler

*   **📅 Dinamik Takvim Görünümü:** Tüm ayın vardiya düzenini renk kodlarıyla (gündüz, gece, icap) görselleştiren takvim arayüzü.
*   **📊 Analitik ve Yorgunluk Modülü:** Aylık toplam mesai saatlerini takip eder. Risk sınırları aşıldığında sistem otomatik "Glow (Parlama) Efekti" ile görsel alarm verir ve bilişsel risk seviyesini hesaplar.
*   **🤝 Nöbet Pazarı:** Çalışanların klinik içindeki nöbetlerini takas edebilmesi veya devredebilmesi için dijital duyuru/kabul platformu.
*   **📝 Klinik Teslim ve Triyaj Formu:** Vardiya bitiminde sonraki ekibe "Kırmızı, Sarı, Yeşil" alan durumlarına göre klinik teslim notlarını interaktif bir form ile kaydetme imkanı.
*   **🌓 Tema Desteği:** Sağ köşedeki butonla aktif edilebilen, göz yormayan Karanlık Tema (Dark Mode) ve Açık Tema (Light/Medical Mode) desteği.
*   **📱 Modern UI/UX:** Camsı (Glassmorphism) tasarım efektleri ile yumuşacık geçişler ve akıcı bir deneyim.

## 🛠️ Kullanılan Teknolojiler

Bu uygulama, karmaşık bağımlılıklara ihtiyaç duymadan **tek bir dosya** içerisinde çalışacak şekilde geliştirilmiştir.

*   **HTML5** (Semantik yapı)
*   **CSS3** (CSS Variables, Flexbox/Grid Layout, Keyframe Animations, Glassmorphism)
*   **Vanilla JavaScript** (DOM Manipülasyonu, Algoritmik hesaplamalar)
*   **Font Awesome** (İkon seti)
*   **Google Fonts - Inter** (Okunaklı modern tipografi)

## 🚀 Başlangıç & Kurulum

Proje sunucu gereksinimi olmayan, tamamen istemci tarafında (client-side) çalışan statik bir uygulamadır.

1.  Bu projedeki kaynak kodlarını sadece `.html` uzantısıyla bilgisayarınıza kaydedin (Örn: `index.html` veya `nobetzeka.html`).
2.  Kaydettiğiniz dosyaya çift tıklayarak favori tarayıcınızda (Chrome, Safari, Edge vb.) anında çalıştırabilirsiniz!
3.  *Geliştirme için herhangi bir Node.js veya npm bağımlılığı yoktur.*

## 💡 Kullanım Senaryoları

*   **Mesai Riskini Görmek:** Sol menüden "Analitik & Risk" sekmesine girip "Yoğun Mesai Simülasyonu Başlat" butonuna tıklayarak algoritmanın fazla mesailerde vereceği görsel reaksiyonu (kırmızı parlama efekti) test edebilirsiniz.
*   **Klinik Notu Bırakmak:** "Klinik Teslim" sekmesinde ilgili durumu seçip notunuzu kaydedin, alt kısımdaki dinamik listeye görsel etiketle birlikte anında yansıyacaktır.
*   **Karanlık Mod:** Gecesel vardiyalarda ekran parlaklığını azaltmak için üst bardaki ay ikonuna tıklayarak temayı hızla değiştirebilirsiniz.

---

*Sağlık çalışanlarının hayatını kolaylaştırmak için tasarlanmıştır.*
