# Demo

**30 dakika hayatta kal. Arkadaşlarınla birlikte.**

**Demo**, 1–4 kişilik co-op bir *survivors* oyunu: karakterin otomatik saldırır, sen hareket edip düşman dalgalarından kaçarsın, seviye atladıkça silah ve güç toplarsın. Her 5 dakikada düşmanlar güçlenir ve bir mini boss gelir; 30. dakikada son boss seni bekler.

Haritada **harita içi eventler** beliriyor: yanına gidersen bonus altın, Ruh Taşı ve özel ödüller kazanırsın. Her event başarısı kalıcı olarak yeni karakter, oyun modu ya da Kalıntı açıyor.

> ⚠️ Oyun **geliştirme aşamasında**; "Demo" geçici adı. Çizimler geçici (pixel art gelecek), denge ayarları test ediliyor. Gördüğün hataları ve fikirlerini yazarsan çok yardımcı olur!

![Oyun içi](images/gameplay.png)

---

## 📥 İndir ve kur

**[👉 En son sürümü indir](https://github.com/HasanBersan/demo-oyun/releases/latest)**

Sayfanın altındaki **Assets** bölümünden işletim sistemine uygun dosyayı indir.

### Windows
1. `Demo-windows.zip` dosyasını indir ve bir klasöre çıkart.
2. `Demo.exe` dosyasını çalıştır.
3. "Windows bilgisayarınızı korudu" uyarısı çıkarsa: **Ek bilgi** → **Yine de çalıştır**.
4. Oda açtığında Windows Güvenlik Duvarı izin isterse **İzin ver**'e bas.

### macOS
1. `Demo-macos.zip` dosyasını indir ve çift tıklayıp aç.
2. `Demo` uygulamasına **sağ tıkla → Aç**.
3. "Apple doğrulayamadı" uyarısı çıkarsa: **Sistem Ayarları → Gizlilik ve Güvenlik** → en altta **Yine de Aç**.

---

## 🎮 Arkadaşlarınla oyna

Bir kişi **oda açar** (host), diğerleri o odaya **bağlanır**. En fazla 4 kişi.

### Aynı evdeyseniz (aynı Wi‑Fi)
1. Host: ana menüde **Oda Aç**.
2. Lobide **"Aynı evden: 192.168.x.x"** yazar. **Adresi kopyala**'ya basıp arkadaşlarına gönder.
3. Arkadaşlar: adresi IP kutusuna yazıp **Odaya Bağlan**.
4. Herkes lobide görününce host **Oyunu Başlat**'a basar.

### Farklı evlerdeyseniz (internet üzerinden)
Bunun için ücretsiz **[Tailscale](https://tailscale.com/download)** programını kullanıyoruz.

1. **Herkes** Tailscale'i indirip kurar ve bir hesapla giriş yapar.
2. **Host**, [Tailscale yönetim panelinde](https://login.tailscale.com/admin/machines) bilgisayarını **Share** ile arkadaşlarıyla paylaşır.
3. Host **Oda Aç**'a basar; **"Farklı evden (Tailscale): 100.x.x.x"** adresini arkadaşlarına gönderir.
4. Arkadaşlar bu adresi IP kutusuna yazıp **Odaya Bağlan**.

> Bağlanamıyorsanız: Tailscale herkeste açık mı? Güvenlik duvarı oyuna izin veriyor mu? Herkes aynı sürümü mü kullanıyor?

---

## 🕹️ Nasıl oynanır

| Tuş | İş |
|---|---|
| **WASD** / ok tuşları | Hareket |
| *(otomatik)* | Saldırı |
| **Tab** | Tam harita |
| **ESC** | Menü / duraklat |

### Temel akış
- **Seviye atla:** Düşmanlardan düşen yeşil XP taşlarını topla. Her seviyede 3 seçenekten birini al: yeni silah (en fazla 3) ya da pasif güç (en fazla 4).
- **Evrim ★:** 5. seviyedeki silahın eşi olan pasif de sendeyse, bir boss sonrası düşen **büyük sandığı** açınca silah güçlü haline evrilir.
- **Co-op:** Ölen takım arkadaşının yanında 3 saniye durursan onu canlandırırsın. Şifacı sınıfı yakınındaki herkesi iyileştirir.

### 🎪 Harita içi eventler
Haritada parlayan **işaretler** beliriyor (ekran kenarındaki oklar ve Tab haritası yeri gösterir). Yanına gidersen event başlar, gitmezsen bir şey olmaz.

- **12 isteğe bağlı event:** Gizli Boss, Hazine Goblini, Lanetli Sunak, Ödül Avı, Kanlı Ay, Kervan Koruma, Arena, Hazine Parçaları, Şans Çarkı, Ölüm Avcısı, Katliam, Şeytan Paktı.
- **Zorluk yıldızları ★ / ★★ / ★★★:** Zor event daha güçlü düşmanla gelir ama **Ruh Taşı ×2–3**, daha çok altın verir.
- **Event zincirleri:** Bazı eventleri bitirince zincirin devamı yeni bir işaret olarak belirir (+1 Ruh Taşı).

### 💎 Ruh Taşı ve Kalıntılar
- Eventleri başarınca **Ruh Taşı** kazanırsın; maç sonunda kaybolmaz.
- Ana menüdeki **Gelişim → Kalıntılar** sekmesinden kalıcı pasif güçler satın alırsın (Usta Silah, Kan Emici, Şans Tılsımı, Cellat ve daha fazlası).

### 🔓 Kilit açma
Her event türünün **ilk başarısı** kalıcı olarak bir şey açar: yeni karakter, oyun modu ya da Kalıntı.
- **Açılan karakterler (★)** daha güçlüdür: +%20 can, +%12 hasar, +%5 hız.

---

## 🗂️ İçerik

| | |
|---|---|
| **Karakterler** | 8 karakter, 4 sınıf — Savaşçı, Büyücü, Okçu, Şifacı (bir kısmı eventlerle açılır) |
| **Silahlar** | 24+ silah, her birinin evrim versiyonu var |
| **Eventler** | 12 isteğe bağlı + 1 otomatik (Sürü Dalgası) |
| **Oyun modları** | Normal, Sonsuz, Zor, Hızlı Maç, Boss Akını (eventlerle açılır) |
| **Düşmanlar** | 6 kademe, elitler, bölünen/patlayan/kalkanlı düşmanlar |
| **Boss'lar** | 5 mini boss + çok aşamalı son boss |
| **Kalıntılar** | 7 kalıcı pasif güçlendirme (Ruh Taşı ile alınır) |

| Ana menü | Harita (Tab) |
|---|---|
| ![Menü](images/menu.png) | ![Harita](images/map.png) |

---

## 💬 Geri bildirim

Hata bulduysan ya da bir fikrin varsa **Issues** sekmesinden yazabilirsin (ya da doğrudan bana söyle). Özellikle şunları merak ediyorum:
- Hangi dakikada zorlandın, ne öldürdü?
- Hangi silah/sınıf çok güçlü ya da çok zayıf geldi?
- Oyun takıldı mı (çok düşman olunca)?
