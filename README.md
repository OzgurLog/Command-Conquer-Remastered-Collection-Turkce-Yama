# Command & Conquer Remastered Collection — Türkçe Yaması

![Platform](https://img.shields.io/badge/Platform-Steam-1b2838)
![Sürüm](https://img.shields.io/badge/S%C3%BCr%C3%BCm-v4-2ea44f)
![Dil](https://img.shields.io/badge/Dil-T%C3%BCrk%C3%A7e-red)
![Durum](https://img.shields.io/badge/Durum-Stabil-blue)
[![İndir](https://img.shields.io/badge/%C4%B0ndir-Releases-2ea44f)](../../releases/latest)

Command & Conquer Remastered Collection (Steam) için hazırlanmış, GLM 5.3 ile **tamamı sıfırdan yazılmış** Türkçe yerelleştirme yaması. Bu yamada makine çevirisi yok: oyunun **6.852 metninin tamamı**, orijinal CONFIG dosyasındaki 9 resmî dil karşılaştırılarak ve C&C evreninin yerleşik terminolojisi gözetilerek yeniden yazıldı. Hedef, seriyi ilk gününden beri oynayan eski oyuncuları da tatmin edecek gerçek bir Türkçe deneyimi sunmak.

| | |
| --- | --- |
| Çevrilen metin | **6.852 / 6.852** (%100) |
| Eksik kalan metin | 0 |
| Biçim hatası | 0 |
| Dokunulmayan oyun dosyası | 3.956 / 3.974 (orijinalle bayt bayt aynı) |

> **Güncel sürüm: v4** — [son sürümü buradan indirebilirsiniz](../../releases/latest). Sürüm geçmişi için [YAMA-NOTLARI.md](./YAMA-NOTLARI.md) dosyasına bakın.

## İçindekiler

- [Öne Çıkan Özellikler](#öne-çıkan-özellikler)
- [İndirme](#indirme)
- [Gereksinimler](#gereksinimler)
- [Kurulum](#kurulum)
- [Yamayı Kaldırma](#yamayı-kaldırma)
- [Sorun Giderme](#sorun-giderme)
- [Sıkça Sorulan Sorular](#sıkça-sorulan-sorular)
- [Hata Bildirimi ve Katkı](#hata-bildirimi-ve-katkı)
- [Ekran Görüntüleri](#ekran-görüntüleri)
- [Teknik Detaylar (Meraklısına)](#teknik-detaylar-meraklısına)
- [Yasal Not](#yasal-not)

## Öne Çıkan Özellikler

- **Tam kapsam.** Menüler, ayarlar, görev brifingleri, sinematik alt yazılar, ülke istihbarat dosyaları, EVA mesajları, başarımlar ve Bonus Galeri dâhil 6.852 metnin tamamı Türkçe.
- **Sıfırdan çeviri.** Eski yamadaki makine çevirisi tamamen kaldırıldı. "Bağlamalar" → "Tuş Atamaları", "o rafineriyi nakavt etmeliyiz" → "o rafineriyi yok etmeliyiz" gibi makine çevirisi hastalıkları kökten temizlendi.
- **Evrene sadık terminoloji.** Çeviri, CONFIG dosyasındaki 9 resmî dil referans alınarak yapıldı (İngilizce birincil kaynak; Almanca ve Fransızca resmî çevirileri anlam teyidi için). Türk Vikipedi ve oyuncu topluluğunun yerleşik kullanımı gözetildi. Kane, Tiberium, Red Alert, MiG, Tanya gibi evren adları olduğu gibi korunur; kurum adları Türkçeleşir: **Nod Kardeşliği**, **Küresel Savunma İnisiyatifi**.
- **Karakter dili.** Sovyet subayları "yoldaş" hitabıyla konuşur, Kane vaaz eder, EVA soğuk bir bilgisayar üslubuyla anons yapar.
- **Türkçeye oturan cümleler.** Uzun sinematik cümleler İngilizce dizilişi takip etmek yerine önce doğal Türkçeye çevrildi, sonra alt yazılar tümce sınırlarından yeniden bölündü — her parça tek başına anlamlı, sırayla okunduğunda akıcı bir Türkçe cümle.
- **Dublaj filtresi.** Ağır küfür sıfırlandı; televizyon dublajı üslubu korundu: "kahretsin", "lanet olsun", "alçak", "cadı"...
- **Dil ayarından bağımsız.** Türkçe metinler 9 dil dosyasının tamamına işlendi; Steam dil ayarınız ne olursa olsun oyun Türkçe görünür.
- **Kararlı yapı.** MEG arşivinin yapısı bütünlükle korundu, tüm CRC değerleri doğrulandı; 3.974 dosyanın 3.956'sı orijinalle bayt bayt aynı.

## Gereksinimler

| Gereksinim | Açıklama |
| --- | --- |
| Oyun | Command & Conquer Remastered Collection |
| Platform | Steam (Windows) |
| Ek yazılım | Gerekmez |

<a name="indirme"></a>
## İndirme

Yama, GitHub **Releases** sayfasında yayımlanır:

**[Son sürümü indirin](../../releases/latest)**

- İndirmeniz gereken dosya: en son sürüme eklenmiş **CONFIG.MEG** (bazı sürümlerde ZIP paketi içinde).
- Hangi sürümde ne değiştiğini görmek için [YAMA-NOTLARI.md](./YAMA-NOTLARI.md) dosyasına bakın.
- İndirme tamamlandığında [Kurulum](#kurulum) bölümünden devam edin.

<!-- Repo sahibi için: Yamanızı Releases yerine başka bir yerde barındıracaksanız (Google Drive vb.) bu bölümdeki bağlantıları kendi indirme bağlantınızla değiştirin. "../../releases/latest" bağlantısı depo kökünde otomatik çalışır. -->

## Kurulum

1. Oyunu kapatın (Steam tamamen kapalı olsun).
2. Yamayı kopyalayacağınız klasörü açın. En kolay yol: Steam → **Kitaplık** → Command & Conquer Remastered Collection → sağ tık → **Yönet → Yerel dosyalara göz at** → `CnCRemastered` klasörü → `Data` klasörü.
3. **Önerilir:** Klasördeki orijinal `CONFIG.MEG` dosyasını yedekleyin (ör. adını `CONFIG.MEG.ORG` olarak değiştirin ya da güvenli bir klasöre kopyalayın).
4. [İndirme](#indirme) bölümünden indirdiğiniz `CONFIG.MEG` dosyasını `Data` klasörüne kopyalayın (varsa üzerine yazın).
5. Oyunu Steam'den başlatın. Steam dil ayarınızı değiştirmeniz gerekmez — oyun her dil ayarında Türkçe açılır.

**Kurulum Videosu**
[![CnC Remastered Kurulumu](https://img.youtube.com/vi/gr_-64-XwVQ/maxresdefault.jpg)](https://www.youtube.com/watch?v=gr_-64-XwVQ)

Yama dosyasının gideceği tam yol:

```
C:\Program Files (x86)\Steam\steamapps\common\CnCRemastered\Data
```

Steam kitaplığınız başka bir diskte/konumdaysa:

```
<Sürücü>:\SteamLibrary\steamapps\common\CnCRemastered\Data
```

> **Not:** Steam'in "dosya doğrulama" özelliğini kullanırsanız veya oyun güncellenirse orijinal İngilizce `CONFIG.MEG` geri gelir. Yamayı tekrar kopyalamanız yeterlidir; başka bir işlem gerekmez.

## Yamayı Kaldırma

**Yöntem 1 — Yedekten geri yükleme**

1. Oyunu kapatın.
2. `Data` klasöründeki yamalı `CONFIG.MEG` dosyasını silin.
3. Yedeklediğiniz dosyayı geri yükleyin (`CONFIG.MEG.ORG` → `CONFIG.MEG`).

**Yöntem 2 — Steam dosya doğrulama**

1. Steam → **Kitaplık** → oyuna sağ tık → **Özellikler → Yerel Dosyalar → Oyun dosyalarının bütünlüğünü doğrula**.
2. Steam, değişen dosyaları otomatik olarak orijinal haline getirir.

## Sorun Giderme

| Sorun | Çözüm |
| --- | --- |
| Oyun açılışta çöküyor | Yamayı kaldırıp oyunu bir kez orijinal dosyalarla açın. Sorun yamayla ilgili görünüyorsa [Issues](../../issues) üzerinden bildirin. |
| Metinler Türkçe görünmüyor | `CONFIG.MEG` dosyasının `...\CnCRemastered\Data` klasöründe olduğunu kontrol edin. |
| Bazı metinler İngilizce kaldı | Şarkı adları ve evrene özel adlar bilinçli olarak İngilizcedir. Bunların dışındaysa eksik çeviridir; [Issues](../../issues) üzerinden bildirin. |
| Çeviride anlam bozukluğu var | [Issues](../../issues) üzerinden konum ve metinle birlikte bildirin. |

## Sıkça Sorulan Sorular

**Yamada makine çevirisi var mı?**

Hayır. v3 sürümüyle birlikte eski makine çevirisinin tamamı kaldırıldı ve 6.852 metnin tamamı sıfırdan yazıldı.

**Steam dil ayarımı değiştirmem gerekiyor mu?**

Hayır. Türkçe metinler, oyunun 9 dil dosyasının tamamına işlendi; Steam dil ayarınız ne olursa olsun oyun Türkçe görünür.

**Kayıtlı oyunlarım etkilenir mi?**

Hayır. Yama yalnızca metin verisini değiştirir; kayıt dosyalarınıza ve oynanışa dokunmaz.

**Çoklu oyunda yamayla oynayabilir miyim?**

Yama yalnızca metin içerdiğinden oynanışa etkisi yoktur. Çevrimiçi maçlarda beklenmedik bir uyumsuzluk görürseniz yamayı geçici olarak kaldırabilirsiniz.

**Neden Kane, GDI, Tiberium gibi adlar çevrilmedi?**

Kısaltmalar ve evren adları (Kane, Tiberium, Red Alert, MiG, Tanya...) serinin 30 yıllık geleneğine ve topluluğun yerleşik kullanımına uygun biçimde korunur. Kurumların tam adları ise Türkçedir: Nod Kardeşliği, Küresel Savunma İnisiyatifi.

**Şarkı adları neden İngilizce?**

Jukebox'taki parça adları orijinal adlarıyla korunur; yalnızca durum etiketleri çevrildi: "(Classic)" → "(Klasik)", "(Remastered)" → "(Yeniden Düzenlenmiş)".

**EA App (Origin) sürümüyle çalışır mı?**

Yama Steam sürümü için hazırlanmış ve test edilmiştir; diğer platformlar garanti edilmez.

**Yama düzenli olarak güncellenecek mi?**

Bu yama, kendim için hazırlayıp meraklılarla paylaştığım kişisel bir çalışmadır; belirli bir güncelleme takvimi yoktur. Geri bildirimleriniz her zaman hoş karşılanır — bildirilen hatalar not alınır ve vakit buldukça yeni sürümlerde ele alınır.

## Hata Bildirimi ve Katkı

Hatalı bir çeviri ya da anlam bozukluğu fark ederseniz [Issues](../../issues) sayfasında şu bilgilerle bildirim açmanız yeterli:

- **Konum:** Metni gördüğünüz yer (ör. *GDI 3. görev brifingi*, *ana menü → Ayarlar*, *sinematik sahnesi*)
- **Ekranda görünen metin**
- **Önerdiğiniz çeviri** (varsa)

> **Not:** Bu yama kişisel bir projedir ve belirli bir güncelleme takvimi yoktur. Bildirimler not alınır; vakit buldukça yeni sürümlerde değerlendirilir.

## Ekran Görüntüleri

<!-- Ekran görüntülerini repoda bir klasöre (ör. "images") yükleyip aşağıdaki tabloyu doldurun. -->

| Ana Menü | Görev Brifingi | Sinematik Alt Yazı |
| --- | --- | --- |
|  |  |  |

## Teknik Detaylar (Meraklısına)

<details>
<summary>MEG ve LOC formatı, doğrulama özeti (açmak için tıklayın)</summary>

- **MEG v4 formatı:** 24 bayt başlık + isim tablosu + 20 baytlık giriş tablosu (CRC32 bazlı sıralı) + sıkıştırmasız veri.
- **LOC formatı:** uint32 kayıt sayısı + 12 baytlık kayıtlar (CRC32(TEXT_ID), metin uzunluğu, ID uzunluğu) + UTF-16LE metin blobu + tek baytlık ID blobu.
- **Doğrulama:** 3.974 dosyanın tamamı yerinde; 3.956'sı orijinalle bayt bayt aynı; 9 dil dosyasında 6.852/6.852 kayıt doğrulandı; tüm CRC değerleri geçerli.
- **Türkçe karakterler** (ğ, ş, ı, İ, ç, ö, ü) UTF-16LE olarak korundu.
- **Biçim güvenliği:** ##0/##1/%s/%d biçim belirteçleri, \n satır yapıları, && kaçış dizileri ve baştaki/sondaki boşluklar kayıt kayıt doğrulandı (0 hata). Motoru bozabilecek "%45" desenleri "45%" biçimine dönüştürüldü.

</details>

## Yasal Not

Bu yama gönüllü bir topluluk çalışmasıdır; Electronic Arts veya Petroglyph Games ile resmî bir bağlantısı yoktur. *Command & Conquer*, Electronic Arts Inc.'in tescilli markasıdır. Yama ücretsizdir, yalnızca kişisel kullanım için dağıtılır ve satılamaz. Yamayı kullanabilmek için oyunun Steam'deki resmî bir kopyasına sahip olmanız gerekir.

---

C&C topluluğuna ve bu seriyi yıllardır yaşatan tüm eski oyunculara teşekkürler. Komutan, savaş alanında görüşmek üzere!
