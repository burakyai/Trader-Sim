# Trader Sim

Canlı akan bir borsada trader kariyeri. Tek dosyalık bir web oyunu; iPhone'da Safari'den açıp **Paylaş → Ana Ekrana Ekle** dersen uygulama gibi tam ekran çalışır.

**Oyna:** https://burakyai.github.io/Trader-Sim/

## Oyun Modu
- 10 kurgusal şirket, her saniye kendi kendine hareket eden fiyatlar, BIST kuralları (fiyat adımı, %10 taban/tavan, 10:00–18:00 seans)
- Bilanço, ihale, SPK, faiz kararı gibi haberler fiyatları sarsar
- İki hız: **Hızlı** (1 borsa günü = 8 dakika) ya da **Gerçek saat**
- Uygulama kapalıyken de piyasa işler; limit ve stop emirleri o arada gerçekleşir
- **Kariyer:** kuryelikten fon yöneticiliğine işler, her gün maaş; batarsan maaşla geri dönersin
- **Kaldıraç** (1x–10x, margin call) ve **banka kredisi** (faiz, icra, iflas)
- **Tahtacılık:** 50 milyon ₺ varlıkta açılır; ekip kur (sermayedar, bot hesapçı, fenomen, avukat, içerden adam), ortak havuzla topla, yürüt, haber yay, dağıt; SPK radarına yakalanma
- Rütbeler (Çaylak → Borsa Efsanesi) ve rozetler

## 👑 Ultimate Trader (Tanrı Modu)
Oyun Modu'nun ayrı kayıtlı bir kopyası; her şey senin elinde:
- Para ekle / nakdi ayarla, borçları sil, tahtacılığı aç, tecrübe ekle, SPK'yı temizle
- Zaman: duraklat, 1x / 4x / 16x hız, sonraki güne atla
- Kurallar: taban/tavan (±%5–50 ya da limitsiz), azami kaldıraç (100x'e kadar), piyasa yönü (ayı → çılgın boğa), haber sıklığı, SPK ve margin call aç/kapa, tahtacılık eşiği, faizler, komisyon
- Şirketler: ad, fiyat, oynaklık, trend, derinlik, beta düzenle; yeni şirket halka arz et, şirket çıkar
- Kendi haberini yaz: istediğin hisseyi ya da tüm piyasayı istediğin yüzde oynat

## Gerçek Piyasa modu
Gerçek BIST hisseleriyle (~15 dk gecikmeli) demo hesap. Veriyi Claude'daki borsa bağlayıcısından aldığı için yalnızca Claude içinde açıldığında çalışır; GitHub Pages sürümünde Oyun Modu oynanır.

## Notlar
- Kayıtlar tarayıcıda (localStorage) tutulur.
- Şirketler, haberler ve fiyatlar kurgusaldır. Tahtacılık gerçek hayatta suçtur; burada yalnızca bir oyun mekaniğidir. Yatırım tavsiyesi değildir.
