# Sık sorulan sorular

[← Tanıtıma dön](../README.md)

### Kaynak kod burada mı?

Hayır. Bu depo tanıtım, görseller, yayın dosyaları ve güncelleme akışı içindir. Uygulamanın kaynak kodu özel depoda tutulur. Bu depo uygulamaya açık kaynak lisansı vermez.

### “Source code” düğmesi neden var?

GitHub, her sürüm etiketi için o deponun ZIP/TAR arşivini otomatik oluşturur. Buradaki arşiv yalnızca **yayın deposunun** tanıtım dosyalarını, görsellerini ve akışını kapsar; uygulamanın Swift kaynaklarını içermez. Kurmak için DMG dosyasını indirin.

### Hangi Mac’lerde çalışır?

Apple Silicon işlemcili MacBook ve macOS 13 veya üzeri gerekir. Intel paketi yoktur. Apple’ın yerleşik şarj sınırı için ayrıca macOS 26.4 veya üzeri gerekir.

### Şarjı gerçekten durduruyor mu?

Bildirim hedefi yalnızca hatırlatmadır ve şarjı durdurmaz. **Koruma → Şarj sınırı ayarlarını aç** düğmesi macOS Pil ayarlarını açar. Şarj bilgi penceresi otomatik açılmazsa Pil bölümündeki Şarj satırının yanındaki **ⓘ** düğmesini seçin. Desteklenen Mac’lerde sınırı macOS yönetir; Wattelier bunu okumaz, değiştirmez veya zorla deşarj uygulamaz. Apple, kalibrasyon için zaman zaman %100'e şarj edebilir.

### Uygulamayı kapatırsam seçtiğim şarj sınırı kalkar mı?

Hayır. Seçim macOS’a ait bir tercihtir. Apple’ın Pil ayarlarından değiştirebilirsiniz. Wattelier bildirimleri ise uygulama açıkken çalışır.

### Watt ve uygulama tüketimleri kesin ölçüm mü?

Güç dağılımı ve uygulama enerji değerleri tahmin içerebilir. Bunlar priz tipi enerji sayacının veya laboratuvar ölçümünün yerine geçmez. Beta günlükteki Wh ve ortalama W değerleri de tahmini olarak etiketlenir.

### Beta ile kararlı sürüm arasındaki fark nedir?

Kararlı sürüm genel kullanım içindir. Yeni özellikler önce beta kanalına gelir. Ayarlardan beta’ya katılabilirsiniz; kapatmak yüklü sürümü otomatik olarak düşürmez. Ana sayfadaki birincil düğme en son kararlı sürüme yönelir; DMG indirmesi yayımlanan paketin Assets bölümündedir.

### Pil günlüğü nerede?

1.4.0 beta serisinde **Geçmiş → Pil günlüğü** altında. Kayıtlar bu Mac’te en fazla 30 gün tutulur. Aynı ekrandan kaydı duraklatabilir veya geçmişi silebilirsiniz. Eski günlerin verisi geriye dönük oluşturulmaz; uyku ve kapalı uygulama süreleri sayılmaz.

### Verilerim yükleniyor mu?

Wattelier pil ölçümlerini veya uygulama listesini sunucuya göndermez. Güncellemeler GitHub’dan denetlenir ve indirilir. Beta pil günlüğü yerel dosyada saklanır.

### Uygulama neden açılmıyor?

Mevcut dağıtım henüz Apple Developer ID / noter onayına sahip değildir. macOS ilk açılışı engelleyebilir. Ayrıntılar ve resmi Apple yönergesi [kurulum belgesinde](INSTALL.md).

### Sorun bildirmek için ne paylaşmalıyım?

[Bir sorun kaydı açın](https://github.com/Enes-Somuncular/Wattelier-Releases/issues/new/choose). Uygulama sürümü, macOS sürümü, Mac modeli ve tekrarlama adımları yeterli bir başlangıçtır. Ekran görüntülerindeki kişisel bilgileri paylaşmadan önce gizleyin. Bu depodaki sorun kayıtları herkese açıktır.
