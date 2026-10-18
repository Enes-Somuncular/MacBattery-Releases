# Wattelier kurulumu

[← Tanıtıma dön](../README.md) · [English](#english)

## 1. Doğru dosyayı indirin

[En güncel kararlı yayını açın](https://github.com/Enes-Somuncular/Wattelier-Releases/releases/latest) ve **Assets** altından `Wattelier-….dmg` dosyasını seçin. Daha eski kararlı sürümlerin paket adı `MacBattery-….dmg` olabilir.

“Source code (zip/tar.gz)” Wattelier uygulaması değildir. GitHub bu dosyaları yayın deposunun içeriğinden otomatik oluşturur.

## 2. Uygulamalar’a taşıyın

DMG’yi açın. DMG içindeki `MacBattery.app` uygulamasını **Uygulamalar / Applications** klasörüne sürükleyin. Görünen ürün adı Wattelier'dir; iç paket dosyası uyumluluk nedeniyle bu adı taşır. Daha eski bir kurulum varsa önce uygulamadan çıkın ve yeni kopyayla değiştirin. Ardından uygulamayı **Uygulamalar** klasöründen çalıştırın.

## 3. Menü çubuğundan açın

Wattelier Dock yerine menü çubuğunda görünür. Pil/güç göstergesine tıklayarak paneli açın. Bildirimler ve oturum açılışında başlatma isteğe bağlıdır; ayarlardan etkinleştirilir.

## macOS uygulamayı engellerse

Mevcut paketler **ad-hoc imzalıdır**; Apple Developer ID imzası ve notarization henüz yoktur. Bu nedenle ilk açılış engellenebilir. Dosyayı bu resmi yayın deposundan indirdiğinizi doğrulayın ve [Apple’ın Mac’te uygulamaları güvenli açma yönergelerini](https://support.apple.com/en-us/102445) inceleyin. Güvendiğiniz bir uygulama için macOS **Sistem Ayarları → Gizlilik ve Güvenlik** bölümünde açma seçeneği sunabilir. Wattelier sistem güvenliğini kapatmanızı isteyen bir kurulum komutu kullanmaz.

Sparkle’ın Ed25519 güncelleme imzaları dosya bütünlüğünü ve yayıncı anahtarını doğrular; bunlar Apple’ın uygulama noter onayından farklıdır.

## Güncellemeler

Uygulama içinden **Güncellemeleri Denetle…** seçeneğini kullanın. Beta için **Ayarlar → Güncellemeler → Beta güncellemelerini al** seçeneğini açın. Beta’yı kapatmak yüklü sürümü düşürmez; daha yeni kararlı sürüm çıktığında ona geçilir.

## Dosya bütünlüğü

Her yayında ZIP ve DMG için `SHA256SUMS` bulunur. İndirilen dosyanın SHA-256 değeri bununla karşılaştırılabilir. Kontrol toplamı tek başına Apple noter onayı anlamına gelmez.

## English

Requires an Apple Silicon MacBook and macOS 13 or later. Download the DMG from the [latest stable release](https://github.com/Enes-Somuncular/Wattelier-Releases/releases/latest), open it, drag the included MacBattery.app (display name Wattelier) to Applications, and launch the copy in Applications. The app lives in the menu bar, not the Dock.

Current builds are ad-hoc signed and are not yet Developer ID signed or notarized. macOS may block the first launch. Confirm that you downloaded the app from this official distribution repository and follow [Apple’s safe-opening guidance](https://support.apple.com/en-us/102445). Do not disable system security globally.

The auto-generated Source code archives are documentation archives, not app installers. Use the DMG. Subsequent updates can be installed from the app. Ed25519 update signatures are separate from Apple notarization.
