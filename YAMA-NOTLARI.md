# Yama Notları

Command & Conquer Remastered Collection — **Türkçe Yaması** sürüm geçmişi.

Kurulum yönergeleri için [README.md](./README.md) dosyasına bakabilirsiniz.

> **Güncel sürüm: v4** — Türkçe cümle dizilişi (özne/yüklem) revizyonu

<!-- Sürümlere tarih eklemek isterseniz başlıkları şu biçimde güncelleyin: ## v4 — 01.11.2026 -->

---

## v4 — Türkçe Cümle Dizilişi Revizyonu (Güncel Sürüm)

**Geri bildirim:** "Uzun cümlelerde alt yazı İngilizce konuşma düzenine göre ekrana geliyor; Türkçeye göre özne ve yüklem oturmuyor."

**Teşhis:** Sinematik alt yazıları, orijinal İngilizce dosyadaki parça sınırlarına göre satır satır çevrilmişti. Türkçe tümce yapısı (yüklem sonda) İngilizce dizilişiyle (yüklem ortada, belirteçler arkada) örtüşmediği için uzun cümleler ekranda anlamsızlaşıyor, bazı satırlar "-erek / -ip / -ken" gibi asılı zarf-fiillerle bitiyordu.

**Yapılan iş:**

- 112 sinematik sahnesinin tamamı (1.725 alt yazı satırı) İngilizce kaynakla karşılaştırmalı olarak tek tek gözden geçirildi.
- 75 sahnede İngilizce dizilişli cümle zinciri tespit edildi ve tamamı yeniden yazıldı (toplam **276 kayıt**, 0 biçim hatası).
- Yeni yöntem — "dublaj standardı": pasaj önce doğal Türkçeye çevrildi, sonra **aynı sayıda** alt yazı parçasına tümce sınırlarından yeniden bölündü. Her parça kendi başına okunabilir; okuma süresi orijinal parça uzunluklarıyla orantılı kaldı.

**Örnek düzeltmeler:**

| Eski (İngilizce dizilişi) | Yeni (Türkçe dizilişi) |
| --- | --- |
| Nod Kardeşliği, kadim ve gizli bir topluluk, güçlü bağlar sürdürür; dünya çapındaki terör örgütlerinin çoğuyla bağlantılıdır. | Nod Kardeşliği; dünya çapındaki terör örgütlerinin çoğuyla güçlü bağlar sürdüren kadim ve gizli bir topluluktur. |
| Tiberium bilim dünyasını şaşırtmaya devam ediyor; toprak minerallerini sünger gibi emerek. (asılı "-erek") | Tiberium; toprak minerallerini ve topraktaki besin maddelerini sünger gibi emerek bilim dünyasını şaşırtmaya devam ediyor. |

**Bu sürümde ayrıca:**

- Yüklemi önde, tanımlaması arkada kalan cümleler düzeltildi ("X'i yineledi, ... rağmen" → "... rağmen X'i yineledi").
- Asılı zarf-fiiller ("-erek", "-ip", "-ken") giderildi; yüklem cümle sonuna taşındı.
- Hitap tutarlılığı sağlandı: Kane ve Kukov "siz", Seth "sen", Carville sahne içinde tek biçim.
- Sahne etiketleri tek biçime bağlandı: (EKRAN DIŞI), [PARAZİT].
- Anlam bozulmaları düzeltildi (ör. özne karmaşası: "karışmıştı" → "karıştığına inanmış").
- "iğdiş edildi" → "etkisiz hale getirildi" (dublaj üslubu).
- Bonus Galeri'de İngilizce kalmış 3 kayıt çevrildi: "TAMAMLA: Patlatıcıyı Tahliye Edin", "TAMAMLA: FRANSA Suyu İçmeyin".

**Doğrulama:** 6.852/6.852 kayıt — biçim belirteçleri, satır sonları, boşluklar ve konuşmacı etiketleri birebir korundu (0 hata). Düzeltilen sahneler teslim edilen dosyadan geri okunarak satır satır doğrulandı. MEG yapısı: 3.974/3.974 dosya; CRC zinciri sağlam.

---

## v3 — Sıfırdan Yeni Çeviri

Yamanın en kapsamlı sürümü: eski makine çevirisinin tamamı bir kenara bırakıldı ve oyunun **6.852 metninin tamamı** (48 çeviri parçası, ~350.000 karakter) baştan çevrildi.

**Yöntem:**

- **Kaynak:** CONFIG-ORG.MEG içindeki 9 resmî dil dosyası (İngilizce, Almanca, Fransızca, İspanyolca, Korece, Lehçe, Rusça, Çince-Basitleştirilmiş, Çince-Geleneksel). İngilizce birincil kaynak; Almanca ve Fransızca resmî çevirileri anlam teyidi için kullanıldı (ör. "knock out" → Almanca "ausschalten" = etkisiz hale getirmek).
- **Jargon araştırması:** Türk Vikipedi (C&C maddeleri) ve Türk oyuncu topluluğunun kullanımı tarandı; sonuçlar terim sözlüğüne işlendi.
- **Üslup:** Eski oyuncu kitlesi hedeflendi; askeri ve akıcı Türkçe. Sovyet karakterler "yoldaş" der, Kane vaaz eder, EVA soğuk bilgisayar diliyle konuşur.

**Bildirilen hatalar düzeltildi:**

| Eski | Yeni |
| --- | --- |
| Bağlamalar | Tuş Atamaları (TUŞ ATAMASINI KALDIR, yeniden ata dâhil tüm terim ailesi tutarlı) |
| O rafineriyi nakavt etmeliyiz | O Rafineriyi yok etmeliyiz (görev adı dahil: "O Rafineriyi Yok Edin") |
| Options / Seçenekler karışıklığı | Ayarlar (tek biçim) |

**Terim sözlüğü oluşturuldu** (yapılar, birimler, arayüz, askeri fiiller): Cevher Rafinerisi, Savaş Fabrikası, Mamut Tankı, Tesla Bobini, Kronosfer, Çatışma (Skirmish), Tekrar (Replay), Müzik Kutusu (Jukebox)... Askeri fiillerde kural: "yok et" ve "imha et" — "nakavt" asla. Birim her zaman "birim"dir, asla "ünite" değildir.

**Dublaj filtresi** tüm metinlere uygulandı: ağır küfür 0; "Seni alçak domuz!", "cadı", "kahretsin", "lanet olsun", "cehennemi yaşatın", "bujinin üstüne tükürürdüm". Sansürlü "!@#$%" blokları (dublaj biplemesi) ve 3.917 kelimelik sohbet küfür filtresi sözlüğü aynen korundu.

**162 tutarlılık düzeltmesi:** ülke istihbarat dosyaları tek biçime bağlandı (HARCANABİLİRLİK, YÖNETİM YOLSUZLUĞU, GAYRİSAFİ YURT İÇİ HASILA...), "Özel Harekât", "Hasta ve Can Çekişen", "Kronosfer'i", "V2 Roketi", "AI: ORTA/ZOR/RASTGELE" gibi kalıplar tek biçime oturtuldu; Bonus Galeri kilit metinleri görev adlarıyla birebir hizalandı.

**Türkçe yazım kuralları** uygulandı: "her şey", "hiçbir", İ/ı büyük harf kuralı ("İPTAL", "SIL"), Türkçe sayı biçimi (2.728.000).

**Kalite güvencesi:** 6.852/6.852 kayıt otomatik doğrulamadan geçti — biçim belirteçleri (##0/##1/%s/%d), satır sayıları, && kaçış dizileri, boşluklar, konuşmacı etiketleri ve büyük harf [SES EFEKTLERİ]: **0 hata**. Motoru bozabilecek "%45" desenleri "45%" biçimine dönüştürüldü.

**Dosya doğrulaması:** 3.974/3.974 dosya yerinde; 3.956'sı orijinalle bayt bayt aynı; CRC zinciri sağlam; Türkçe karakterler UTF-16LE olarak korundu.

---

## v2 — Eksik Çeviriler

- Çevrilmemiş kalan bölümler Türkçeleştirildi. (Bu sürümde temel hâlâ makine çevirisiydi; asıl çözüm v3'te geldi.)

---

## v1 — İlk Çalışan Sürüm

- Eski yamanın yol açtığı açılış çökmesi (crash) giderildi; oyun Türkçe paketle sorunsuz başlatılır hale getirildi.

---

## Bilinen Notlar

- Steam "dosya doğrulama" veya oyun güncellemesi, orijinal İngilizce CONFIG.MEG'yi geri getirir; yamayı yeniden kopyalamanız yeterlidir.
- Şarkı adları (Jukebox) ve evrene özel adlar bilinçli olarak İngilizce kalır.
- Hata ve öneri bildirimleri için [Issues](../../issues) sayfasını kullanın; bildirimler vakit buldukça yeni sürümlerde değerlendirilir.
