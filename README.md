# 📚 Kitap Köşesi

Kitap Köşesi, kitapseverlerin kolayca kitap satın alabileceği, favorilerini kaydedebileceği ve siparişlerini yönetebileceği modern bir e-ticaret web uygulamasıdır.

## 🌟 Özellikler

### 📖 Kitap Yönetimi
-Sistemde hangi kitapların olduğunu arama kutusu yardımıyla bulabilirsiniz.
-Kitapların Stok durumuna kıolaylıkla erişebilsiniz.
- Kitapları isterseniz favorilerinize ekleyebilsiniz, isterseniz sepetinize ekleyip satın alabilirsiniz

### 👤 Kullanıcı İşlemleri
- Kullanıcı kaydı ve girişi
- Şifre sıfırlama
- Profil yönetimi
- Sipariş durumunuzu ister mail ister site üzerinden görüntüleme

### ❤️ Favoriler
- Kitapları favorilere ekleme
- Favori kitapları listeleme
- Favorilerden kitap kaldırma

### 🛒 Sepet İşlemleri
- Sepete kitap ekleme
- Sepetteki kitapların miktarını güncelleme
- Sepetten kitap kaldırma
- Toplam tutarı görüntüleme

### 📦 Sipariş Yönetimi
- Sipariş oluşturma
- Sipariş geçmişini görüntüleme
- Sipariş detaylarını inceleme

## 🛠️ Teknolojiler

- **Backend**: ASP.NET Core MVC
- **Veritabanı**: Firebase Firestore
- **Frontend**: 
  - HTML5
  - CSS3
  - JavaScript
  - Bootstrap
  - jQuery
- **Kimlik Doğrulama**: Session-based Authentication
- **Email Servisi**: SMTP entegrasyonu

## 🚀 Kurulum

1. Projeyi klonlayın:
```bash
git clone [proje-url]
```

2. Gerekli NuGet paketlerini yükleyin:
```bash
dotnet restore
```

3. Firebase yapılandırmasını ayarlayın:
   - Firebase konsolundan bir proje oluşturun
   - Firestore veritabanını etkinleştirin
   - Kimlik bilgilerini `appsettings.json` dosyasına ekleyin

4. Projeyi çalıştırın:
```bash
dotnet run
```

## 📝 Yapılandırma

`appsettings.json` dosyasında aşağıdaki ayarları yapılandırın:

```json
{
  "Firebase": {
    "ProjectId": "your-project-id",
    "CredentialPath": "path/to/firebase-credentials.json"
  }
}
```

## 🔒 Güvenlik

- Kullanıcı şifreleri güvenli bir şekilde hashlenmiştir
- Session-based kimlik doğrulama kullanılmaktadır
- HTTPS protokolü desteklenmektedir
- Cross-Site Request Forgery (CSRF) koruması mevcuttur

## 📱 Responsive Tasarım

Uygulama, Bootstrap framework'ü kullanılarak tamamen responsive olarak tasarlanmıştır:
- Mobil cihazlara uyumlu
- Tablet ve masaüstü görünümleri optimize edilmiş
- Modern ve kullanıcı dostu arayüz

## 🤝 Katkıda Bulunma

1. Fork'layın
2. Feature branch oluşturun (`git checkout -b feature/YeniOzellik`)
3. Değişikliklerinizi commit edin (`git commit -m 'Yeni özellik eklendi'`)
4. Branch'inizi push edin (`git push origin feature/YeniOzellik`)
5. Pull Request oluşturun

## 📄 Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Daha fazla bilgi için `LICENSE` dosyasına bakın.

## 📞 İletişim

Sorularınız veya önerileriniz için [email-adresi] adresinden bize ulaşabilirsiniz.

---
Developed with ❤️ by [your-name]
