<div align="center"> <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=2800&pause=2000&color=F97316&center=true&vCenter=true&width=940&lines=Merhaba%2C+Ben+Sena+Y%C3%B6ndemli!+%F0%9F%91%8B;Full+Stack+Developer+%7C+Python+%26+React;Vergi+ve+Denetim+Teknolojileri+Geli%C5%9Ftiriyorum;Veriyi+Anlaml%C4%B1+Kararlara+D%C3%B6n%C3%BC%C5%9Ft%C3%BCr%C3%BCyorum" alt="Typing SVG" /> <img src="https://komarev.com/ghpvc/?username=KULLANICI_ADINIZ&label=Profil%20G%C3%B6r%C3%BCnt%C3%BClenme&color=f97316&style=flat" alt="Ziyaretçi Sayacı" />
<a href="https://www.linkedin.com/in/LINKEDIN_ADRESINIZ/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a> <a href="mailto:EPOSTA_ADRESINIZ"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a> <a href="https://github.com/KULLANICI_ADINIZ"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a> <a href="https://portaliva.com"><img src="https://img.shields.io/badge/Portaliva-F97316?style=for-the-badge&logoColor=white" alt="Portaliva"/></a>

</div>
👩‍💻 Hakkımda
class SenaYondemli:
    def __init__(self):
        self.name = "Sena Yöndemli"
        self.role = "Full Stack Developer"
        self.company = "Basedata"
        self.product = "Portaliva — Yeminli mali müşavirler için denetim ve raporlama platformu"
        self.language_spoken = ["tr_TR", "en_US"]
        self.current_focus = [
            "Mali veri işleme ve raporlama",
            "Kullanıcı dostu arayüzler",
            "Gözlemlenebilir, güvenli altyapı",
            "Yerel (on-premise) yapay zekâ çözümleri",
        ]

    def say_hi(self):
        print("Karmaşık mevzuatı ve dağınık veriyi,")
        print("tek ekranda anlaşılır hale getiriyorum. 📊")


me = SenaYondemli()
me.say_hi()
🏢 Basedata'da, yeminli mali müşavirlerin denetim işlerini dijitalleştiren Portaliva platformunu geliştiriyorum
🧾 Vergi beyannamelerini, e-faturaları ve e-defter kayıtlarını otomatik okuyup denetime hazır veriye dönüştüren sistemler kuruyorum
🎨 Arayüzün kullanıcıyı yormaması, bilginin tek bakışta anlaşılması benim için önceliklidir
🔐 Güvenlik, yetkilendirme ve izlenebilirlik konularına özellikle önem veriyorum
🤖 Geliştirme sürecimde yapay zekâ destekli araçları verimli ve kontrollü şekilde kullanıyorum
🚀 Neler Geliştiriyorum?
Alan	Kısaca
📄	Beyanname Ayrıştırma	KDV, Kurumlar ve Geçici Vergi beyannamelerini PDF'ten okuyup satır satır yapılandırılmış veriye dönüştüren ayrıştırıcılar
🧾	e-Defter & e-Fatura	Kuyruktan beslenen worker'larla XML belgelerini işleme, doğrulama ve analize hazırlama
📊	Raporlama & Excel	Filtrelenebilir listeler, GİB formatına uygun Excel çıktıları, Word/PDF raporlar, özet tablolar
🕵️	Denetim Araçları	Karşıt inceleme, riskli mükellef takibi, denetim tespitleri ve limit kontrolleri
📅	Takvim & Planlama	Denetim takvimi, vergi takvimi ve ekip planlama modülleri
🔐	Kimlik & Yetki	E-posta ile tek kullanımlık kod (OTP) girişi, rol ve menü bazlı yetkilendirme
📬	Bildirim & E-posta	Rol bazlı duyurular, SMTP/IMAP ile otomatik e-posta gönderimi
🗄️	Veri Yönetimi	Çok şemalı PostgreSQL referans verileri, S3 uyumlu dosya depolama ve kota yönetimi
🤖	Yerel Yapay Zekâ	Veriyi dışarı çıkarmadan çalışan AI asistan, sesli komut ve sesli özet
📈	Gözlemlenebilirlik	Grafana + Loki + Alloy ile merkezi loglama ve izleme panoları
🛡️	Altyapı Güvenliği	Nginx / ModSecurity WAF yapılandırması, güvenli yayın süreçleri
🧠 Portaliva'da Neler Yaptım, Neler Öğrendim?
Her başlığa tıklayarak ayrıntıları görebilirsiniz.

<details> <summary><b>📄 PDF beyanname ayrıştırma</b></summary> <br>
Yaptıklarım

KDV, Kurumlar ve Geçici Vergi beyannamelerini pdfplumber ve PyMuPDF ile okuyup bölüm bölüm yapılandırılmış veriye çeviren ayrıştırıcılar yazdım
Eski ve yeni beyanname formatlarını aynı anda destekleyen, şablon tabanlı bir ayrıştırma yapısı kurdum
GİB amortisman oranları listesini ve vergi takvimini PDF'ten okuyup veritabanına aktaran içe aktarma komutları geliştirdim
Öğrendiklerim

PDF'lerdeki bozuk Türkçe karakter kodlamalarını düzeltmek, sayfa geçişinde bölünen tabloları ve çok satırlı hücreleri birleştirmek
Ayrıştırıcıda bir hata düzeltildiğinde eski kayıtları bozmadan yeniden ayrıştırma (Django management komutları) yapmak
Gerçek belgelerle doğrulama yapmanın, en az kodu yazmak kadar önemli olduğunu
</details> <details> <summary><b>🧾 e-Defter, e-Fatura ve mesaj kuyrukları</b></summary> <br>
Yaptıklarım

RabbitMQ kuyruklarından beslenen, e-defter / e-fatura / e-irsaliye XML'lerini işleyen Python worker'ları
XSLT şablonlarıyla e-fatura görüntüleme
Büyük hacimli kayıtları Parquet formatında saklayıp Polars ve PyArrow ile hızlı analiz
Öğrendiklerim

defusedxml ile XXE ve "billion laughs" saldırılarına karşı güvenli XML ayrıştırma
Pandas ile Polars arasındaki performans farkı ve sütunlu veri formatlarının gücü
Asenkron, kuyruk tabanlı mimaride hata toleransı ve yeniden deneme stratejileri
</details> <details> <summary><b>📊 Raporlama, Excel ve belge üretimi</b></summary> <br>
Yaptıklarım

GİB'e yüklenebilir formatta .xls / .xlsx listeler (openpyxl, xlwt, xlsx-js-style)
docxtpl ve python-docx ile Word rapor şablonları, LibreOffice ile PDF dönüşümü ve otomatik içindekiler
Tarayıcı tarafında docx, jsPDF ve html2canvas ile dışa aktarma
Highcharts ve Recharts ile analiz panoları ve Türkiye haritası üzerinde görselleştirme
Öğrendiklerim

Resmî kurumların beklediği dosya türünü ve Türkçe sayı biçimini (1.234,56) birebir korumanın ayrıntıları
Şablon ile veriyi ayırarak raporları kod değiştirmeden güncellenebilir kılmak
</details> <details> <summary><b>🕵️ Denetim ve analiz modülleri</b></summary> <br>
Yaptıklarım

Karşıt inceleme: yıl bazlı GİB eşik değerleriyle tek fatura ve toplam tutar limit kontrolleri
Riskli mükellef takibi, denetim tespitleri, mizan ve bilanço denetimi
Finansal oranlar, patern analizi, sabit kıymet / amortisman üreteci ve adat hesaplama
Öğrendiklerim

Vergi mevzuatını koda dökerken iş kurallarını alan uzmanlarıyla birlikte netleştirmek
Küçük bir kural hatasının (ör. limitin tek faturaya mı toplama mı uygulandığı) sonuçları nasıl değiştirdiğini
</details> <details> <summary><b>📅 Takvim ve ekip planlama</b></summary> <br>
Yaptıklarım

FullCalendar ile denetim takvimi ve takvimin içinde ikinci kip olarak ekip planlama
Sürükle-bırak ile görev atama (@hello-pangea/dnd)
Resmî vergi takviminin yıllık tabloya aktarılması
Öğrendiklerim

Yeni bir özelliği ayrı bir menü yerine mevcut akışın içine yerleştirmenin kullanıcıya etkisini
</details> <details> <summary><b>🔐 Kimlik, yetki ve güvenlik</b></summary> <br>
Yaptıklarım

JWT (SimpleJWT) + e-posta ile tek kullanımlık kod (OTP) doğrulamalı giriş
Rol ve menü bazlı yetkilendirme
Hassas sorgu kataloğunun AES-256-GCM ile şifrelenmesi
Nginx + ModSecurity WAF kurallarının yapılandırılması
Öğrendiklerim

WAF'ın yanlış pozitif ürettiği (403) durumları analiz edip kuralları güvenliği zayıflatmadan ayarlamak
Ters vekil (reverse proxy) zaman aşımlarının giriş hatalarına nasıl dönüşebildiğini
</details> <details> <summary><b>🗄️ Veri, depolama ve kota yönetimi</b></summary> <br>
Yaptıklarım

PostgreSQL'de çok şemalı (genel / referans) veri yapısı ve düzenlenebilir referans tabloları
MinIO (S3 uyumlu) depolama; Uppy ile tarayıcıdan doğrudan S3'e parçalı (multipart) ve kaldığı yerden devam eden yükleme
Kullanıcı bazlı depolama kotası, yinelenen dosya koruması
pgpool-II bağlantı kopmalarına karşı tenacity ile otomatik yeniden deneme
Öğrendiklerim

Büyük dosyaları sunucuyu yormadan yüklemenin (presigned URL) yolları
Referans verisini tek bir kaynaktan yönetmenin veri tutarlılığına katkısı
</details> <details> <summary><b>🤖 Yerel (on-premise) yapay zekâ</b></summary> <br>
Yaptıklarım

Ollama ile şirket içinde çalışan AI asistan ve mevzuat araması
faster-whisper ile tamamen yerel ses → metin (sesli komut)
Yerel TTS servisiyle belgelerin sesli özeti (Celery görevi → MP3 → depolama)
Öğrendiklerim

Mali verinin hassasiyeti nedeniyle modelleri veriyi dışarı göndermeden çalıştırmak
Yapay zekâyı ayrı bir HTTP servisi olarak konumlandırıp uygulamadan bağımsız ölçeklemek
</details> <details> <summary><b>⚙️ Arka plan işleri ve mikroservisler</b></summary> <br>
Yaptıklarım

Celery + Celery Beat ile zamanlanmış görevler ve sonuç takibi
FastAPI ve Flask ile ayrı çalışan ara katman ve rapor servisleri
Redis ile önbellekleme
Selenium ile muhasebe yazılımı entegrasyonu için tarayıcı otomasyonu
Öğrendiklerim

Uzun süren işleri kullanıcıyı bekletmeden arka plana almak ve ilerlemeyi arayüze yansıtmak
</details> <details> <summary><b>📈 Gözlemlenebilirlik ve DevOps</b></summary> <br>
Yaptıklarım

Grafana + Loki + Alloy ile merkezi loglama; Django'da python-json-logger ile yapısal JSON log ve hazır Grafana panoları
Docker / Docker Compose ile çok servisli geliştirme ortamı
k3s üzerinde Kubernetes manifestleri (manifest üreten Python betikleri dahil)
Ansible + Paramiko ile müşteri sunucusuna on-premise kurulum sihirbazı
Portainer ile konteyner yönetimi
Öğrendiklerim

"Log yazmak" ile "log'dan soru sorabilmek" arasındaki fark: alan bazlı sorgulanabilir log tasarımı
Test, prod ve müşteri ortamlarını aynı süreçle ama ayrı yapılandırmayla yönetmek
</details> <details> <summary><b>🎨 Kullanıcı deneyimi</b></summary> <br>
Yaptıklarım

React 19 + Ant Design ile açık/koyu tema uyumlu arayüzler
Shepherd.js ile ürün içi tanıtım turları
Quill tabanlı, tablo destekli zengin metin editörü
react-easy-crop ile görsel kırpma, sürüklenebilir pencereler, bilgi balonları
Öğrendiklerim

Kullanıcının istemediği bir özelliği "sadeleştirme" adına kaldırmadan önce sormak gerektiğini
Yoğun mali tabloları okunur kılmak için boşluk, hizalama ve renk kullanımını
</details>
🛠️ Teknoloji Yığınım
💻 Diller
<p> <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/> <img src="https://img.shields.io/badge/SQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL"/> <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/> <img src="https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css&logoColor=white" alt="CSS"/> <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" alt="Bash"/> <img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logoColor=white" alt="PowerShell"/> <img src="https://img.shields.io/badge/XSLT-8A2BE2?style=for-the-badge&logoColor=white" alt="XSLT"/> </p>
🎨 Frontend
<p> <img src="https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"/> <img src="https://img.shields.io/badge/Ant_Design-0170FE?style=for-the-badge&logo=antdesign&logoColor=white" alt="Ant Design"/> <img src="https://img.shields.io/badge/MUI-007FFF?style=for-the-badge&logo=mui&logoColor=white" alt="MUI"/> <img src="https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=reactrouter&logoColor=white" alt="React Router"/> <img src="https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styledcomponents&logoColor=white" alt="styled-components"/> <img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white" alt="Axios"/> <img src="https://img.shields.io/badge/Highcharts-8087E8?style=for-the-badge&logoColor=white" alt="Highcharts"/> <img src="https://img.shields.io/badge/Recharts-22B5BF?style=for-the-badge&logoColor=white" alt="Recharts"/> <img src="https://img.shields.io/badge/FullCalendar-2C3E50?style=for-the-badge&logoColor=white" alt="FullCalendar"/> <img src="https://img.shields.io/badge/Uppy-1269CF?style=for-the-badge&logoColor=white" alt="Uppy"/> <img src="https://img.shields.io/badge/Quill-3E4E5E?style=for-the-badge&logoColor=white" alt="Quill"/> </p>
⚙️ Backend
<p> <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django"/> <img src="https://img.shields.io/badge/Django_REST-A30000?style=for-the-badge&logo=django&logoColor=white" alt="Django REST Framework"/> <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white" alt="Celery"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/> <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask"/> <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white" alt="SQLAlchemy"/> <img src="https://img.shields.io/badge/Gunicorn-499848?style=for-the-badge&logo=gunicorn&logoColor=white" alt="Gunicorn"/> <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" alt="JWT"/> </p>
🗄️ Veri & Depolama
<p> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/> <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis"/> <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white" alt="RabbitMQ"/> <img src="https://img.shields.io/badge/MinIO_(S3)-C72E49?style=for-the-badge&logo=minio&logoColor=white" alt="MinIO"/> <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/> <img src="https://img.shields.io/badge/Polars-CD792C?style=for-the-badge&logo=polars&logoColor=white" alt="Polars"/> <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/> <img src="https://img.shields.io/badge/Parquet-50ABF1?style=for-the-badge&logo=apacheparquet&logoColor=white" alt="Parquet"/> </p>
📑 Belge İşleme
<p> <img src="https://img.shields.io/badge/pdfplumber-B22222?style=for-the-badge&logoColor=white" alt="pdfplumber"/> <img src="https://img.shields.io/badge/PyMuPDF-0F4C81?style=for-the-badge&logoColor=white" alt="PyMuPDF"/> <img src="https://img.shields.io/badge/python--docx-2B579A?style=for-the-badge&logoColor=white" alt="python-docx"/> <img src="https://img.shields.io/badge/openpyxl-217346?style=for-the-badge&logoColor=white" alt="openpyxl"/> <img src="https://img.shields.io/badge/lxml-4B8BBE?style=for-the-badge&logoColor=white" alt="lxml"/> <img src="https://img.shields.io/badge/LibreOffice-18A303?style=for-the-badge&logo=libreoffice&logoColor=white" alt="LibreOffice"/> </p>
🤖 Yapay Zekâ
<p> <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" alt="Ollama"/> <img src="https://img.shields.io/badge/faster--whisper-6A5ACD?style=for-the-badge&logoColor=white" alt="faster-whisper"/> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch"/> <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV"/> <img src="https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=claude&logoColor=white" alt="Claude Code"/> </p>
🔧 DevOps & Altyapı
<p> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/> <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes"/> <img src="https://img.shields.io/badge/k3s-FFC61C?style=for-the-badge&logo=k3s&logoColor=black" alt="k3s"/> <img src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white" alt="Ansible"/> <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" alt="Nginx"/> <img src="https://img.shields.io/badge/ModSecurity_WAF-4A4A4A?style=for-the-badge&logoColor=white" alt="ModSecurity"/> <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" alt="Grafana"/> <img src="https://img.shields.io/badge/Loki-F2CC0C?style=for-the-badge&logo=grafana&logoColor=black" alt="Loki"/> <img src="https://img.shields.io/badge/Alloy-FF7F50?style=for-the-badge&logo=grafana&logoColor=white" alt="Alloy"/> <img src="https://img.shields.io/badge/Portainer-13BEF9?style=for-the-badge&logo=portainer&logoColor=white" alt="Portainer"/> <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/> </p>
🧪 Test & Otomasyon
<p> <img src="https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white" alt="Jest"/> <img src="https://img.shields.io/badge/Testing_Library-E33332?style=for-the-badge&logo=testinglibrary&logoColor=white" alt="Testing Library"/> <img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white" alt="Selenium"/> </p>
🧰 Araçlar
<p> <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/> <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js"/> <img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white" alt="npm"/> <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logoColor=white" alt="VS Code"/> <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logoColor=white" alt="Excel"/> </p>
📊 GitHub İstatistiklerim
<div align="center"> <img height="170" src="https://github-readme-stats.vercel.app/api?username=KULLANICI_ADINIZ&show_icons=true&include_all_commits=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=f97316&icon_color=f97316" alt="GitHub İstatistikleri"/> <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=KULLANICI_ADINIZ&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=f97316" alt="En Çok Kullanılan Diller"/> <img src="https://streak-stats.demolab.com/?user=KULLANICI_ADINIZ&theme=tokyonight&hide_border=true&background=0d1117&ring=f97316&fire=f97316&currStreakLabel=f97316" alt="GitHub Streak"/> <img src="https://github-readme-activity-graph.vercel.app/graph?username=KULLANICI_ADINIZ&theme=tokyo-night&hide_border=true&bg_color=0d1117&color=f97316&line=f97316&point=ffffff" alt="Katkı Grafiği"/> </div>
💼 Öne Çıkan Proje
<div align="center">
🟠 Portaliva
Yeminli mali müşavirler ve denetim ekipleri için uçtan uca denetim, analiz ve raporlama platformu

</div>
🧾 Veri girişi	E-fatura, e-defter ve beyannameleri otomatik içeri alma ve doğrulama
🔍 Denetim	KDV denetimi, karşıt inceleme, riskli mükellef takibi ve denetim tespitleri
📊 Analiz	Mizan, bilanço, gelir tablosu, finansal oranlar ve patern analizleri
📑 Raporlama	GİB formatında listeler, Excel çıktıları, Word/PDF raporlar ve sunum hazırlama
🤖 Yapay zekâ	Yerel çalışan AI asistan, mevzuat araması, sesli komut ve sesli özet
👥 Organizasyon	Rol bazlı yetkilendirme, duyurular, takvim ve ekip planlama
🔒 Kurumsal ve kapalı kaynak bir üründür; kod paylaşılamamaktadır. 🌐 portaliva.com

🌟 Yetenekler & Uzmanlık Alanları
const skills = {
  frontend:   ["React", "Ant Design", "Highcharts / Recharts", "Responsive & tema uyumlu arayüz"],
  backend:    ["Django & DRF", "FastAPI", "REST API tasarımı", "Celery ile arka plan görevleri"],
  data:       ["PDF / Excel / XML ayrıştırma", "PostgreSQL", "Polars & Pandas", "Veri modelleme"],
  messaging:  ["RabbitMQ", "Redis", "Kuyruk tabanlı worker mimarisi"],
  ai:         ["Ollama (yerel LLM)", "faster-whisper (yerel STT)", "Sesli özet"],
  security:   ["OTP ile giriş", "JWT", "Rol & menü bazlı yetki", "WAF yapılandırması", "Şifreleme"],
  devops:     ["Docker", "Kubernetes (k3s)", "Ansible", "Grafana + Loki ile loglama"],
  domain:     ["Vergi mevzuatı", "KDV & Kurumlar beyannameleri", "Denetim süreçleri"],
  softSkills: ["Problem çözme", "Kullanıcı odaklılık", "Takım çalışması", "Dokümantasyon"],
};
🎯 2026 Hedeflerim
not done
📈 Portaliva'da gözlemlenebilirlik altyapısını canlı ortamda tamamlamak
not done
🤖 Denetim süreçlerinde yapay zekâ destekli analizleri yaygınlaştırmak
not done
☁️ Kubernetes ve bulut mimarisinde uzmanlaşmak
not done
🧪 Test kapsamını artırarak güvenilir yazılım kültürünü güçlendirmek
not done
📝 Mali teknoloji (FinTech / RegTech) üzerine teknik yazılar paylaşmak
💡 Çalışma Prensibim
def gelistir(ozellik):
    """
    Önce kullanıcıyı anla, sonra kodu yaz.
    Çalışan, test edilmiş ve sade olan en iyisidir.
    """
    ihtiyac = kullaniciyi_dinle(ozellik)
    tasarim = sade_tut(ihtiyac)
    kod = yaz_ve_test_et(tasarim)
    return kod if kod.guvenli and kod.anlasilir else gelistir(ozellik)
🤝 Birlikte Çalışalım
Mali teknolojiler, veri odaklı uygulamalar veya kullanıcı dostu arayüzler üzerine fikir alışverişi yapmak isterseniz benimle iletişime geçebilirsiniz!

<div align="center">
📬 İletişim
<a href="https://www.linkedin.com/in/LINKEDIN_ADRESINIZ/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a> <a href="mailto:EPOSTA_ADRESINIZ"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>

<br><br>

⭐ Profilimi beğendiyseniz takip etmeyi unutmayın!

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:fb923c,100:c2410c&height=100&section=footer" width="100%" alt="footer"/>
<sub>🧡 Kod ile yapıldı · © 2026 Sena Yöndemli</sub>

</div>
