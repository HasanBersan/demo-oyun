# ASOO

**30 dakika hayatta kal. Arkadaşlarınla birlikte.**

ASOO, 1–4 kişilik çevrimiçi co-op bir *survivors* oyunudur. Silahlar otomatik saldırır; oyuncular hareket ederek düşman dalgalarından kaçar, XP toplar ve seviye atladıkça silah veya pasif güç seçer. Normal maç yaklaşık 30 dakika sürer; haritaya ve moda göre süre değişebilir.

Haritalarda isteğe bağlı event işaretleri belirir. Eventleri tamamlayarak altın, Ruh Taşı, karakterler, oyun modları ve Kalıntılar kazanırsın.

> **v0.5.0 test sürümü:** **Zorluk Isısı** (maç öncesi 10 taş mühürle zorluk kuralları seç, karşılığında daha çok altın kazan), yerden yükselen Kan Kitabesi seviye kartları, Kan sistemi (Kan Öfkesi, kanla diriltme, Kan Sunağı), her yeteneğe özel efekt ve iz, parçalanan düşmanlar, patlayıcı fıçılar ve yuvarlanan kayalar, darbe fiziği, dairesel Yetenek Ağacı, Tehlike saati, Dönüşümler ve Ansiklopedi, co-op'ta akıcı düşman hareketi. 20 karakterin adları İngilizce oldu; Zor Mod ve toplanabilir bomba kaldırıldı.
>
> **Bilinen sınırlamalar:** Maç sırasında bağlantısı kopan oyuncu yeniden katılamaz. İki cihazla internet/Tailscale bağlantı testi henüz tamamlanmadı. macOS paketi gerçek bir Mac'te ilk açılış testinden geçmedi.

![Dört haritadan oyun içi ekran görüntüleri: Savaş Meydanı, Volkan, Buzul Vadisi ve Lanetli Bataklık](images/asoo-maps.png)

---

## 📥 İndir ve kur

**[👉 Blood & Chain v0.5.0 test sürümünü indir](https://github.com/HasanBersan/demo-oyun/releases/tag/v0.5.0)**

Release sayfasındaki **Assets** bölümünden işletim sistemine uygun ZIP dosyasını indir.

### Windows
1. `Demo-windows.zip` dosyasını indirip bir klasöre çıkart.
2. İçindeki `Demo.exe` dosyasını çalıştır.
3. Windows koruma uyarısı çıkarsa **Ek bilgi → Yine de çalıştır** seçeneğini kullan.
4. Oda açarken güvenlik duvarı sorarsa oyuna izin ver.

### macOS
1. `Demo-macos.zip` dosyasını indirip aç.
2. İçindeki `Demo.app` uygulamasına sağ tıklayıp **Aç**'ı seç.
3. macOS uygulamayı doğrulayamazsa **Sistem Ayarları → Gizlilik ve Güvenlik → Yine de Aç** yolunu izle.

---

## 🎮 Arkadaşlarınla oyna

Bir kişi oda açar (host), diğerleri bağlanır. En fazla 4 kişi oynayabilir.

### Aynı Wi‑Fi'de
1. Host ana menüden **Oda Aç**'ı seçer.
2. Lobide gösterilen yerel IP adresini arkadaşlarına gönderir.
3. Diğer oyuncular adresi IP kutusuna yazıp **Odaya Bağlan**'ı seçer.
4. Herkes lobide görünce host **Oyunu Başlat**'a basar.

### Farklı ağlarda
İnternet/Tailscale bağlantısı iki cihazla henüz doğrulanmadı. Bağlantısı maç sırasında kopan oyuncu yeniden katılamaz.

---

## 🕹️ Nasıl oynanır

| Tuş | İş |
|---|---|
| **WASD** / ok tuşları | Hareket |
| *(otomatik)* | Saldırı |
| **Tab** | Tam harita |
| **ESC** | Menü / duraklat |

Düşmanlardan düşen XP taşlarını topla ve seviye atladıkça silah ya da pasif güç seç. Silahları eşleşen pasiflerle geliştir; boss sandıklarından evrim kazan. Takım arkadaşını yerdeyken yanında 3 saniye durarak canlandırabilirsin.

## ✨ İçerik

- 20 karakter: her birinin kendine özgü özelliği, tek bir başlangıç silahı ve kendi Yetenek Ağacı var
- 49 temel silah, 49 evrim ve 20 pasif
- 4 harita: Savaş Meydanı, Volkan, Buzul Vadisi ve Lanetli Bataklık; her birinin kendi düşmanları, tehlikesi ve temalı duraklatma ekranı var
- 16 isteğe bağlı event (haritaya özel olanlar dahil) ve 1 otomatik Sürü Dalgası
- Normal, Sonsuz, Hızlı Maç ve Boss Akını modları; 10 isteğe bağlı Zorluk Isısı mührüyle zorluğu kendin ayarla (kural başına +%15 maç sonu altını)
- 8 mini boss, 3 evreli son boss ve kalıcı Kalıntılar; Volkan ve Buzul Vadisi'nde haritaya özel kalıcı ilerleme

![Oynanabilir karakterler: her birinin özelliği ve tek başlangıç silahı (oyun içi sprite'larla hazırlanmış kart sayfası)](images/asoo-characters.png)

![Her haritanın kendi duraklatma ekranı: Savaş Meydanı, Volkan, Buzul Vadisi ve Lanetli Bataklık](images/asoo-pause.png)

---

## 💬 Geri bildirim

Hata bildirmek veya fikir paylaşmak için GitHub **Issues** sekmesini kullan. Hata raporuna oyunun dakikasını, seçtiğin karakteri ve oyun modunu ekle.
