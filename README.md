# ReisulQurra

**Kur'an okuma, dinleme ve ezber uygulaması. Ücretsiz, reklamsız.**

ReisulQurra; mushaf okuma, farklı kârîlerden dinleme, kişiye göre ezber planı ve ezber çalışması, hafızlık testleri ile tecvid derslerini tek uygulamada toplar. Reklam yoktur, ücret yoktur, hesap açmak gerekmez.

> Bu depo yalnızca masaüstü uygulamasının **kurulum dosyalarını** barındırır; kaynak kod içermez.

## İndir

| Sistem | İndirme |
|---|---|
| **Windows 10 / 11** (64-bit) | [ReisulQurra-Setup.exe](https://github.com/KULLANICI_ADIN/reisulqurra-releases/releases/latest/download/ReisulQurra-Setup.exe) |
| **Pardus** (64-bit) | [ReisulQurra-linux-x64.deb](https://github.com/KULLANICI_ADIN/reisulqurra-releases/releases/latest/download/ReisulQurra-linux-x64.deb) |

Tüm sürümler: [Releases](https://github.com/KULLANICI_ADIN/reisulqurra-releases/releases)

**Kurulum:** Windows'ta dosyayı çalıştırın, kurulum ekranındaki koşulları okuyup kabul edin. Pardus'ta `.deb` dosyasına çift tıklayın veya `sudo apt install ./ReisulQurra-linux-x64.deb` yazın.

**Windows "bilinmeyen yayıncı" uyarısı:** Uygulama henüz kod imzalı olmadığı için Windows ilk açılışta uyarı verebilir. **Ek bilgi → Yine de çalıştır** deyin. İsterseniz indirdiğiniz dosyanın SHA-256 özetini her sürümün açıklamasındaki değerle karşılaştırabilirsiniz.

## Neler var?

- **Mushaf okuma:** KFGQPC V1 / V2 ve Diyanet mushafı; Kâlûn, Warş, Dûrî ve Şu'be rivayetleri; sayfa, sure, cüz ve ayete gitme; tekrar ve hız ayarı.
- **Dinleme:** 12 kârî seçeneği, ayet / sayfa / aralık dinleme, ters tertip (son ayetten başlama), ses indirip çevrimdışı dinleme.
- **Ezber planı:** 10 ezber yöntemi (Osmanlı Sarmal, Güney Asya, Mısır, Mufassal Önceliği ve diğerleri), 6-4-4-6 gibi tekrar taktikleri, günlük hedef, kişiye özel yöntem önerisi.
- **Ezber çalışması:** Tek Tek, Toplu, Taktik ve Zincirleme modlar; ayet aralığıyla küçük parçalar halinde çalışma.
- **Hafızlık testleri:** Eksik kelime, sıradaki ayet, kelime sıralama, karma ve mushaf hafızası; yanlışlarından özel test.
- **Öğrenme:** Tashih dersleri, tecvid ve Secâvend (vakıf işaretleri).
- **Takip:** Günlük seri, ilerleme ağacı, istatistikler, Hatalarım.
- **Kişiselleştirme:** Tema, yazı tipi ve yazı boyutu seçenekleri; 24 dil dosyası.
- **Sesli okuma (yalnızca Windows):** Ezber sırasında okuduğunuzu bilgisayar üzerinde tanır. Ses **hiçbir yere gönderilmez**, çalışırken internet gerekmez.

## Gizlilik

Sesli okuma özelliği tamamen cihazınızda çalışır; mikrofon sesi internete gönderilmez. Uygulama, yeni sürüm olup olmadığını denetlemek için internete bağlanabilir.

## Sistem gereksinimi

64-bit işlemci (2 çekirdek veya üzeri), 4 GB RAM, yaklaşık 1 GB boş disk. Sesli okuma için mikrofon gerekir. Ekran kartı gerekmez.

## Teşekkür ve atıflar

- Kur'an verileri ve sesleri için Tarteel Quran API, Quran.com ve MP3Quran.net altyapılarına teşekkürler.
- Sesli okuma: [Tilawa](https://github.com/yazinsai/tilawa) (MIT) ve NVIDIA `stt_ar_fastconformer_hybrid_large_pcd_v1.0` modelinin Tilawa tarafından uyarlanmış sürümü ([CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)). Kur'an metni: [Tanzil](https://tanzil.net).
- Üçüncü taraf bileşenlerin tam listesi için: [THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt)

## Lisans ve sorumluluk

Kullanım şartları için [LICENSE](LICENSE) dosyasına bakın. Uygulama "olduğu gibi" sunulur. Sesli tanıma sonuçları hatalı olabilir ve Kur'an öğretmeninin yerini tutmaz; tecvid ve okuyuş doğruluğu için bir hocaya danışın.

---

# English

**ReisulQurra** is a free, ad-free Quran app for reading, listening, memorization planning and practice, memorization tests and tajweed lessons.

- **Download:** [Windows (.exe)](https://github.com/KULLANICI_ADIN/reisulqurra-releases/releases/latest/download/ReisulQurra-Setup.exe) · [Pardus / Debian (.deb)](https://github.com/KULLANICI_ADIN/reisulqurra-releases/releases/latest/download/ReisulQurra-linux-x64.deb)
- Mushaf editions (KFGQPC V1/V2, Diyanet), four riwayat, 12 reciters, offline audio.
- 10 memorization methods, repetition tactics, personalised plan suggestions, memorization tests, tajweed lessons.
- **Offline voice recitation (Windows only):** runs entirely on your computer; audio is never sent anywhere.
- Requirements: 64-bit CPU (2+ cores), 4 GB RAM, ~1 GB free disk. No GPU needed.
- Windows may show an "unknown publisher" warning because the app is not code-signed: click *More info → Run anyway*.

See [LICENSE](LICENSE) and [THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt). Voice recognition: Tilawa (MIT) and an adapted NVIDIA FastConformer model (CC BY 4.0); Quran text from Tanzil.
