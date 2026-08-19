🛡️ FPS Guardian - Gamer Edition

    Bilgisayarınızın performansını zirveye taşıyan, siberpunk temalı akıllı sistem optimizasyon ve güvenlik asistanı.

🚀 FPS Guardian Nedir? Ne İşe Yarar?

FPS Guardian, oyuncuların oyun oynarken arka planda yaşanan takılmaları, FPS düşüşlerini ve kaynak israfını engellemek için geliştirilmiş özel bir araçtır. Tamamen sezgisel, modern ve siberpunk esintili bir arayüze sahiptir.
🌟 Öne Çıkan Özellikler:

    ⚡ Game Turbo Modu: Arka plandaki gereksiz Windows hizmetlerini (Spooler, DiagTrack vb.) geçici olarak durdurur, seçtiğiniz oyuna Yüksek Öncelik (High Priority) atayarak maksimum FPS sağlar.

    🔄 Akıllı Otomatik Güncelleme (Auto-Updater): Yeni bir sürüm yayınlandığında bunu otomatik olarak algılar, kullanıcıdan onay alarak kendini günceller ve ilk açılışta Yama Notları (Patch Notes) ekranını gösterir.

    🧹 Anlık RAM Temizleyici: Tek tıkla Windows önbelleğini boşaltarak RAM rahatlaması sağlar.

    🌐 Ping / DNS Tazeleme: Ağ bağlantınızı ve DNS önbelleğinizi sıfırlayarak gecikmeleri (ping) en aza indirir.

    📊 MSI Afterburner Entegrasyonu: Tek tuşla donanım izleme programınızı hızlıca başlatmanızı sağlar.

    👁️ Göz Dinlendirme Sayacı: Uzun oyun maratonlarında sağlığınız için size mola hatırlatması yapar.

    🌙 Rahatsız Etme ve Ses Efektleri: Cyberpunk tarzı mekanik ses geri bildirimleri sunar, dilerseniz tamamen sessiz moda alabilirsiniz.

    🛡️ Sistem Tepsisi (Tray) Desteği: Çarpı tuşuna bastığınızda kapanmaz, arka planda sistem tepsisinde sessizce çalışmaya devam eder.

🛠️ Nasıl Kurulur ve Çalıştırılır?

Projeyi kendi bilgisayarınızda çalıştırmak veya kaynak kodundan derlemek için şu adımları izleyebilirsiniz:
1. Gereksinimler

Bilgisayarınızda Python yüklü olmalıdır. Ardından gerekli kütüphaneleri yükleyin:
Bash

pip install psutil pystray pillow

2. Kaynak Koddan .exe Yapma (Derleme)

Projeyi tek bir .exe dosyası haline getirmek için terminale şu komutu yazabilirsiniz:
Bash

pyinstaller --onefile --noconsole fps_guardian.py

(Oluşan fps_guardian.exe dosyası dist klasörünün içinde yer alacaktır.)
🔒 Güvenlik ve Şeffaflık Politikası

FPS Guardian, tamamen açık kaynaklı ve kullanıcı güvenliğini ön planda tutacak şekilde tasarlanmıştır:

    🔑 Yönetici İzni (Admin Rights): Program, arka plandaki hizmetleri durdurabilmek ve oyunlara öncelik atayabilmek için Windows Yönetici iznine ihtiyaç duyar.

    📂 Yerel Çalışma: Program hiçbir kişisel verinizi toplamaz, dışarıya hassas bilgi sızdırmaz. Tüm log kayıtları sadece bilgisayarınızdaki uygulama klasöründe (fps_guardian_log.txt) tutulur.

    🌐 Güvenli Güncelleme: Güncellemeler yalnızca sizin belirlediğiniz resmi GitHub deposu üzerinden HTTPS protokolü ile kontrol edilir ve indirilir.

👨‍💻 Geliştirici

    Hacı Yasir - Project Creator & Developer
