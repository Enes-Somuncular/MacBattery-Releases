# Wattelier · Marka Kimliği

> **Wattelier** = **Watt** + **Atelier**. Güç verilerini anlaşılır bir deneyime dönüştüren macOS enerji gözlem aracı.

## Marka özü

- **Konumlandırma:** Mac'in enerji kullanımını anlamak isteyenler için zarif, okunabilir, menü çubuğuna yerleşen güç analitiği.
- **Ürün vaadi:** *Pil yüzdesinin ötesini gör.*
- **İngilizce slogan:** *Power, clarified.*
- **Kısa açıklama:** *Wattelier, Mac'in güç akışını, pil sağlığını ve uygulama etkinliğini tek bakışta gösterir.*
- **Ses tonu:** Sakin, akıllı, açık. Abartılı performans ve kesinlik vaatlerinden kaçın.
- **Görsel kavram:** Enerji akışı + izleme. Elektrik çizgisiyle bütünleşen W monogramı.

## Renkler

| Kullanım | Renk | Hex |
| --- | --- | --- |
| Gece arka plan | Midnight | `#070C15` |
| Yüzey | Deep Slate | `#121D2B` |
| Ana metin | Porcelain | `#F4FAFC` |
| İkincil metin | Mist | `#A9C0CF` |
| Vurgu 1 | Mint | `#73E9D5` |
| Vurgu 2 | Citrus | `#D8FC7E` |

Yüksek kontrast ve erişilebilirlik önceliklidir. Renkler ölçüm kategorilerinde tek başına bilgi taşımaz; her zaman metin ve birim de kullanılır.

## Tipografi

- **Ürün / web:** macOS sistem fontu (SF Pro fallback'leriyle).
- **Değerler ve telemetri:** system monospace / tabular numbers.
- Harici font servislerine bağımlılık yok.

## Logo dosyaları

- [W monogramı](../site/assets/logo.svg) — SVG; şeffaf arka plan gerekmeden küçük boyutta okunur.
- [GitHub tanıtım görseli](../site/assets/hero.svg) — SVG; uygulama ekranı **temsili**, gerçek ekran görüntüsü değildir.

## İsimlendirme ve geçiş notları

- Marka / web adı **Wattelier**.
- Teknik repo, uygulama paketi, kurulum dosyaları, `CFBundleIdentifier`, güncelleme URL'leri ve mevcut kullanıcıların kurulu sürümü **MacBattery** olarak kalır. Bu aşama yalnızca web / tanıtım kimliğidir.
- İleride uygulama adı değiştirilecekse güncelleme kanalları, release asset isimleri, bundle yolu ve mevcut kurulumların geçiş planı birlikte ele alınmalıdır; ayrı bir sürüm çalışması gerekir.
- İsim için hızlı web taraması yapıldı; **marka tescili, alan adı ve App Store isim uygunluğu hukuki olarak doğrulanmış değildir.**

## Görsel dil / kullanım kuralları

1. İri başlık ve sakin boşluklar; enerji verisi net olmalı.
2. Renkli metrikler kontrollü kullanılmalı; gösterişli ama yanıltıcı gerçek zamanlılık iddiaları yapılmamalı.
3. Uygulama başına güç değerleri **tahmindir**; donanımdan doğrudan ölçülmüş gibi sunulmamalı.
4. İndirme bağlantıları GitHub Releases üzerinden kalmalı; kararlı ve beta kanalları açıkça ayrılmalı.

© Wattelier — Enes Somuncular. İsim ve görsel kimlik taslak çalışmasıdır.


## Yayın deposu

Bu depoda [kararlı sürümler](https://github.com/Enes-Somuncular/MacBattery-Releases/releases/latest) ve [beta sürümleri](https://github.com/Enes-Somuncular/MacBattery-Releases/releases) bulunur. İndirilebilir kararlı paket: `v1.4.1`; beta: `v1.4.1-beta.2` (18 Ekim 2026 itibarıyla). `appcast-beta.xml` imzalı güncelleme akışıdır ve markalama amacıyla değiştirilmemelidir.
