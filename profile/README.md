# ☕ Kafe Sadakat Sistemi

Kafeler ve yiyecek-içecek işletmeleri için hazırlanmış, **sunucu, alan adı ve markadan tamamen bağımsız** dijital damga kartı, QR/NFC ödül sistemi ve yönetim paneli şablonu.

## 📦 Ana Şablon Deposu

👉 **[`kafe-sadakat/cafe-loyalty-template`](https://github.com/kafe-sadakat/cafe-loyalty-template)**

## ✨ Neler İçerir?

- **Müşteri PWA Uygulaması:** Uygulama mağazası gerektirmeden telefona kurulabilen dijital damga kartı, menü ve kampanya ekranları.
- **Tek Kullanımlık QR / NFC Doğrulama:** Sabit QR suistimaline karşı korumalı tek seferlik damga açılışı, kasa QR ekranı ve NTAG 424 DNA NFC desteği.
- **Müdür & Kasiyer Panelleri:** Canlı damga/ödül işlemleri, kampanya gönderimi, Web Push bildirimleri ve Excel/PDF raporlama.
- **KVKK Uyumlu Altyapı:** Aydınlatma metni ile ticari ileti açık rızasını ayıran kayıt ve onay sürümleme akışı.
- **Sıfır Bağımlılık & Kolay Özelleştirme:** SQLite (`WAL` modu) ve `.env` tabanlı marka/renk/ödül yapılandırması.

## 🚀 `Use this template` ile 3 Adımda Kurulum

1. [`cafe-loyalty-template`](https://github.com/kafe-sadakat/cafe-loyalty-template) sayfasında **Use this template** düğmesiyle kendi hesabınıza kopyalayın.
2. `.env.example` dosyasını `.env` olarak kopyalayıp `SECRET_KEY`, `BUSINESS_NAME`, `ACCENT_COLOR`, `REWARD_NAME` ve `STAMP_TARGET` alanlarını doldurun.
3. `docker compose up -d --build` komutuyla çalıştırıp `http://localhost:8000` adresinden açın.

## 🤝 Katkıda Bulunanlar

Katkı ve geri bildirim kuralları için [CONTRIBUTING.md](../CONTRIBUTING.md) belgesine göz atabilirsiniz.
