# TUGAS KONSEP JARINGAN

## BAB 1 – PENGANTAR JARINGAN INTERNET

**Nama:** Marsha Rifky Febriansyah  
**NRP:** 3125600031  
**Dosen Pengajar:** Dr. Ferry Astika Saputra, ST. M.Sc

**PROGRAM STUDI D4 TEKNIK INFORMATIKA**  
**POLITEKNIK ELEKTRONIKA NEGERI SURABAYA (PENS)**  
**TAHUN 2026**

---

## TUGAS KONSEP JARINGAN

1. Mencatat tentang kabel UTP cat 1 sampai cat 9.
2. Standard wifi yang ada cari tau berapa abgn nya.
3. Mencari detail sejarah dan timeline internet.
4. Menginterpretasikan detail internet yang muncul pada fast.com.

### 1. Kabel UTP (Unshielded Twisted Pair) Kategori 1 Hingga 9

Kabel twisted pair menggunakan lilitan pasangan kawat tembaga untuk mereduksi interferensi elektromagnetik (*crosstalk*). Standar resmi TIA/EIA mencakup hingga Cat 8, sementara istilah "Cat 9" di pasaran umumnya merujuk pada kabel kustom non-standar industri.

| Kategori | Kecepatan Maksimal | Frekuensi (Bandwidth) | Penggunaan Utama |
|:--|:--|:--|:--|
| Cat 1 | < 1 Mbps | 1 MHz | Jalur telepon analog (POTS) konvensional. |
| Cat 2 | 4 Mbps | 4 MHz | Jaringan Token Ring awal era 1980-an. |
| Cat 3 | 10 Mbps | 16 MHz | Jaringan 10BASE-T Ethernet dan telepon digital. |
| Cat 4 | 16 Mbps | 20 MHz | Jaringan Token Ring kecepatan tinggi. |
| Cat 5 | 100 Mbps | 100 MHz | Fast Ethernet (100BASE-TX). |
| Cat 5e | 1 Gbps (1.000 Mbps) | 100 MHz | Gigabit Ethernet standar perumahan/kantor. |
| Cat 6 | 1 Gbps (hingga 10 Gbps jarak < 55m) | 250 MHz | Jaringan LAN Gigabit performa tinggi. |
| Cat 6a | 10 Gbps (hingga 100m) | 500 MHz | 10GBASE-T pada jaringan komersial dan server. |
| Cat 7 | 10 Gbps | 600 MHz | Standar ISO/IEC (umumnya tipe S/FTP berpelindung). |
| Cat 8 | 25 Gbps – 40 Gbps (jarak 30m) | 2.000 MHz (2 GHz) | Koneksi switch-to-server di *Data Center*. |
| Cat 9 | Non-standar TIA/EIA | Hingga 25 GHz (klaim vendor) | Kabel proprietary segmen audio-video/industri khusus. |

### 2. Standar Wi-Fi (IEEE 802.11)

Generasi standar nirkabel IEEE 802.11 berkembang dari varian abgn hingga generasi modern:

| Generasi Wi-Fi | Standar IEEE | Frekuensi Kerja | Kecepatan Maksimal Teoretis | Fitur Utama |
|:--|:--|:--|:--|:--|
| Legacy | 802.11 (asli) | 2,4 GHz | 2 Mbps | Standar transmisi nirkabel awal (1997). |
| Wi-Fi 1 | 802.11b | 2,4 GHz | 11 Mbps | DSSS modulation; adopsi massal pertama. |
| Wi-Fi 2 | 802.11a | 5 GHz | 54 Mbps | Modulasi OFDM; minim gangguan interferensi. |
| Wi-Fi 3 | 802.11g | 2,4 GHz | 54 Mbps | Membawa modulasi OFDM ke spektrum 2,4 GHz. |
| Wi-Fi 4 | 802.11n | 2,4 GHz & 5 GHz | 600 Mbps (4x4 MIMO) | Pengenalan MIMO (*Multiple Input Multiple Output*). |
| Wi-Fi 5 | 802.11ac | 5 GHz | 3,46 Gbps – 6,9 Gbps | Kanal 80 MHz/160 MHz, teknologi MU-MIMO. |
| Wi-Fi 6 / 6E | 802.11ax | 2,4 GHz, 5 GHz, 6 GHz | 9,6 Gbps | Modulasi OFDMA, target efisiensi perangkat padat. |
| Wi-Fi 7 | 802.11be | 2,4 GHz, 5 GHz, 6 GHz | Hingga 46 Gbps | Kanal 320 MHz, teknologi 4096-QAM, MLO. |

### 3. Timeline & Sejarah Perkembangan Internet

- **Lahirnya ARPANET — Tahun 1969**  
  Departemen Pertahanan Amerika Serikat (DARPA) membangun jaringan *packet switching* pertama yang menghubungkan empat simpul universitas: UCLA, Stanford Research Institute, UC Santa Barbara, dan University of Utah.

- **Adopsi Protokol TCP/IP — 1 Januari 1983**  
  ARPANET beralih secara resmi dari protokol NCP ke TCP/IP (*Transmission Control Protocol / Internet Protocol*) rancangan Vinton Cerf dan Robert Kahn, menandai lahirnya arsitektur internet modern.

- **Domain Name System (DNS) — Tahun 1984**  
  Paul Mockapetris merancang DNS untuk memetakan alamat IP numerik ke nama domain yang mudah diingat manusia (seperti .com, .org, .edu).

- **Penemuan World Wide Web (WWW) — Tahun 1989 - 1991**  
  Tim Berners-Lee di CERN mengembangkan konsep hiperteks, protokol HTTP, bahasa HTML, dan browser web pertama yang membuka akses internet untuk publik luas.

- **Komersialisasi & Ledakan Dot-com — Dekade 1990-an**  
  Pencabutan restriksi komersial di NSFNET, peluncuran browser Mosaic (1993) serta Netscape (1994), memicu ledakan ekonomi internet dan layanan web konsumen.

- **Era Web 2.0 & Mobile Internet — Dekade 2000-an - Sekarang**  
  Transisi ke konten interaktif, komputasi awan (*cloud computing*), media sosial, serta konektivitas seluler pita lebar (3G, 4G, 5G, 6G).

### 4. Interpretasi Metrik Pengukuran Fast.com

Fast.com (didukung oleh server Netflix) mengukur performa jaringan internet nyata. Mengklik tombol "Tampilkan info selengkapnya" memunculkan parameter berikut:

- **Kecepatan Download (Unduh)**
  - Kecepatan transfer data dari server uji ke perangkat pengguna (satuan Mbps atau Gbps).
  - Menentukan kelancaran streaming video definisi tinggi, unduhan file besar, serta pemuatan halaman web.

- **Kecepatan Upload (Unggah)**
  - Kecepatan pengiriman data dari perangkat pengguna menuju server luar.
  - Berperan penting untuk panggilan video Zoom/Meet, pengiriman lampiran email, siaran langsung (*live streaming*), dan pencadangan data ke *cloud*.

- **Latensi - Tak Bermuatan (Unloaded Latency)**
  - Waktu tempuh bolak-balik (*Round Trip Time* / RTT) sinyal saat jaringan berada dalam kondisi tenang tanpa aktivitas lalu lintas data berat (satuan milidetik/ms).
  - Mengukur kualitas dasar koneksi fisik ke server terdekat.

- **Latensi - Bermuatan (Loaded Latency)**
  - Waktu tempuh bolak-balik saat jaringan sedang bekerja penuh mengunduh atau mengunggah data secara simultan.
  - Mengindikasikan ada tidaknya gejala *Bufferbloat* (penumpukan antrean paket pada router yang membuat koneksi terasa *lag* saat ada pengguna lain mengunduh file).

- **Klien (Client IP & Location)**
  - Alamat IP publik perangkat beserta nama Penyedia Jasa Internet (ISP) yang terdeteksi saat sesi pengujian.

- **Server (Server Location)**
  - Lokasi fisik pusat data server penyedia pengujian tempat data dikirim dan diterima.

---

## LATIHAN SOAL BAB I

### Level A — Ingatan dan Pemahaman

#### 1. Jelaskan pengertian jaringan komputer dengan menyebutkan empat unsur pokoknya.

Jaringan komputer adalah sistem interkoneksi antara dua atau lebih perangkat komputasi otonom yang saling bertukar data dan berbagi sumber daya. Empat unsur pokoknya:

- **Perangkat (Nodes/End Systems):** Komputer, server, atau perangkat cerdas yang memproses dan menghasilkan data.
- **Media Transmisi (Links):** Jalur fisik penghubung kabel (tembaga, serat optik) maupun nirkabel (*wireless*).
- **Protokol Komunikasi:** Aturan baku yang mengatur format, sintaks, semantik, serta sinkronisasi transmisi data.
- **Perangkat Perantara (Intermediate Devices):** Perangkat pengarah lalu lintas data seperti switch dan router.

#### 2. Apa yang dimaksud dengan perangkat otonom dalam definisi jaringan?

Perangkat otonom adalah sistem komputasi independen yang memiliki prosesor, memori, dan kendali sistem operasi sendiri, sehingga mampu mengambil keputusan pemrosesan tanpa bergantung pada kendali mutlak terminal atau komputer induk lain (berbeda dari arsitektur mainframe-dumb terminal).

#### 3. Bedakan data, sinyal, dan paket.

- **Data:** Entitas informasi dalam bentuk representasi logika digital (bit 0 dan 1) yang dipahami oleh aplikasi pengguna.
- **Sinyal:** Representasi fisik dari bit data berupa gelombang tegangan listrik, pulsa cahaya optik, atau gelombang elektromagnetik radio saat melintasi media transmisi.
- **Paket:** Potongan unit data berformat khusus yang dilengkapi header (berisi alamat asal, alamat tujuan, nomor urut, kendali galat) dan muatan data (*payload*).

#### 4. Jelaskan perbedaan PAN, LAN, MAN, dan WAN tanpa hanya menggunakan ukuran jarak.

- **PAN (Personal Area Network):** Jaringan ad-hoc berdaya rendah yang berpusat pada ruang kendali satu individu pengguna.
- **LAN (Local Area Network):** Jaringan di bawah satu kepemilikan administratif tunggal (kantor, sekolah) dengan kendali penuh atas infrastruktur fisik kabel/nirkabel berkecepatan tinggi.
- **MAN (Metropolitan Area Network):** Infrastruktur skala kota yang mengintegrasikan berbagai LAN melalui jalur transmisi bersama atau konsorsium kota.
- **WAN (Wide Area Network):** Jaringan multi-domain administratif yang melintasi yurisdiksi publik, mengandalkan operator telekomunikasi pihak ketiga (telco/ISP), serta menggunakan teknologi routing inter-domain.

#### 5. Apa perbedaan intranet, ekstranet, dan Internet publik?

- **Intranet:** Jaringan privat dengan akses eksklusif hanya untuk entitas internal organisasi.
- **Ekstranet:** Jaringan privat organisasi yang sebagian aksesnya dibuka secara terotentikasi kepada mitra eksternal terpercaya (pemasok, vendor, klien bisnis).
- **Internet Publik:** Jaringan global terdesentralisasi yang dapat diakses secara bebas oleh siapa saja tanpa batasan keanggotaan institusional.

#### 6. Mengapa Wi-Fi tidak dapat disamakan dengan Internet?

Wi-Fi adalah teknologi lapisan fisik dan data-link (standar IEEE 802.11) untuk menghubungkan perangkat ke titik akses lokal (*access point*) secara nirkabel. Internet adalah interkoneksi jaringan komputer global berbasis protokol tumpukan TCP/IP yang melintasi batas geografis. Seseorang dapat terhubung penuh ke sinyal Wi-Fi lokal namun tidak memiliki akses ke Internet publik jika router tidak terhubung ke ISP.

#### 7. Jelaskan perbedaan client, server, dan peer.

- **Client:** Entitas peminta layanan yang memulai inisiasi komunikasi ke sistem lain.
- **Server:** Entitas penyedia layanan tersentralisasi yang selalu aktif mendengar dan merespons permintaan masuk.
- **Peer:** Entitas yang berposisi setara, mampu bertindak sebagai peminta maupun penyedia layanan secara simultan.

#### 8. Apa perbedaan bandwidth, throughput, dan goodput?

- **Bandwidth:** Kapasitas laju transmisi data teoretis maksimum yang dapat disalurkan oleh suatu tautan komunikasi dalam satuan waktu (misal: 100 Mbps).
- **Throughput:** Laju volume data aktual yang berhasil terkirim dan diterima melintasi tautan fisik per satuan waktu.
- **Goodput:** Laju throughput murni dari data pengguna (*payload* aplikasi) yang berhasil diterima tanpa menyertakan *overhead* header protokol atau bit data yang dikirim ulang akibat *loss*.

#### 9. Sebutkan empat komponen nodal delay.

- **Processing Delay ($d_{proc}$):** Waktu yang dibutuhkan router/node untuk memeriksa header paket, mendeteksi galat bit, dan menentukan rute keluaran.
- **Queuing Delay ($d_{queue}$):** Waktu tunggu paket dalam antrean penyangga (*buffer*) sebelum diproses atau ditransmisikan.
- **Transmission Delay ($d_{trans}$):** Waktu yang dibutuhkan untuk mendorong seluruh bit paket ke dalam media transmisi ($L/R$).
- **Propagation Delay ($d_{prop}$):** Waktu tempuh satu bit sinyal fisik dari awal media hingga tiba di ujung penerima ($d/s$).

#### 10. Mengapa Web tidak sama dengan Internet?

Internet adalah infrastruktur jaringan fisik dan lapisan transportasi global (kabel, router, TCP/IP) yang menghubungkan komputer di seluruh dunia. Web (*World Wide Web*) adalah salah satu aplikasi lapisan aplikasi yang berjalan di atas infrastruktur Internet, menggunakan protokol HTTP/HTTPS untuk menyajikan dokumen terdistribusi melalui tautan hiperteks. Layanan lain seperti email (SMTP), transfer file (FTP), dan SSH juga berjalan di Internet tanpa melalui Web.

### Level B — Penerapan dan Analisis

#### 11. Sebuah paket berukuran 1.000 byte dikirim melalui tautan 10 Mbps. Hitung transmission delay ideal paket tersebut. Jelaskan komponen delay yang belum tercakup.

Ukuran Paket ($L$): 1.000 byte = 1.000 × 8 = 8.000 bit.

Kecepatan Tautan ($R$): 10 Mbps = 10 × 10⁶ bit/detik.

Transmission Delay ($d_{trans}$):

$$
d_{trans} = \frac{L}{R} = \frac{8.000}{10.000.000} = 0{,}0008\text{ detik} = 0{,}8\text{ milidetik (ms)}
$$

Komponen yang belum tercakup: *Propagation delay* (waktu rambat sinyal di kabel), *processing delay* (waktu baca header paket oleh router), dan *queuing delay* (waktu antre di buffer transmisi).

#### 12. Sebuah kampus memiliki koneksi Internet 2 Gbps, tetapi pengguna di satu lantai hanya memperoleh throughput rendah. Susun sedikitnya lima hipotesis yang tidak langsung menyalahkan koneksi ISP.

- **Saturasi Access Point (AP) / Kepadatan Klien:** Terlalu banyak perangkat mahasiswa terhubung ke satu radio AP, menimbulkan perebutan media (*channel contention*).
- **Interferensi Radio Frekuensi:** Gangguan sinyal Co-Channel Interference (CCI) antar AP tetangga yang beroperasi di frekuensi 2,4 GHz yang sama atau interferensi elektromagnetik lingkungan.
- **Hambatan Port Uplink Switch Akses:** Switch lantai terhubung ke distribution switch melalui port yang mengalami negosiasi kecepatan rendah (misal: kabel cacat sehingga turun ke 100 Mbps half-duplex).
- **Konfigurasi Rate Limiting / Traffic Shaping:** Penerapan aturan QoS atau alokasi bandwidth per-subnet/per-VLAN di lantai tersebut yang dibatasi oleh administrator.
- **Broadcast Storm / Loop Jaringan:** Adanya loop layer 2 akibat port bridging tanpa Spanning Tree Protocol (STP) yang aktif, menghabiskan sumber daya switch lantai.

#### 13. Bandingkan kebutuhan jaringan untuk transfer berkas cadangan dan panggilan video. Metrik apa yang paling penting bagi masing-masing aplikasi?

- **Transfer Berkas Cadangan:** Membutuhkan integritas data 100% tanpa kehilangan paket (*packet loss* = 0). Metrik terpenting: Throughput/Bandwidth tinggi dan keandalan transmisi. Toleran terhadap latensi dan jitter.
- **Panggilan Video:** Bersifat interaktif waktu-nyata (*real-time*). Metrik terpenting: Latensi rendah (<150 ms) dan Jitter minimal. Toleran terhadap sedikit kehilangan paket (*loss* 1-2%), tetapi tidak dapat mentoleransi antrean panjang atau retransmisi lambat.

#### 14. Sebuah organisasi mempunyai dua koneksi Internet dari dua operator. Keduanya melewati tiang dan jalur ducting yang sama. Evaluasi kualitas redundansinya.

- Meskipun ada redundansi pada tingkat penyedia layanan logis (Layer 3 multi-homing), secara fisik terjadi *Single Point of Failure* (SPOF) pada Layer 1.
- Gangguan fisik seperti tiang roboh, galian utilitas umum yang memutus selongsong ducting, atau kebakaran jalur kabel akan langsung melumpuhkan kedua tautan ISP secara bersamaan (*shared fate*).

#### 15. Jelaskan mengapa penambahan bandwidth tidak selalu mengurangi waktu akses ke server yang sangat jauh.

Karena Penambahan bandwidth hanya memperkecil *transmission delay* ($L/R$). Untuk server yang terpisah benua, komponen waktu yang mendominasi adalah *propagation delay* (kecepatan perambatan cahaya di serat optik dibatasi fisika, ≈ 200.000 km/s) dan penundaan jabat tangan protokol (*round-trip time TCP Handshake*). Ketika ukuran file kecil atau interaksi membutuhkan banyak sesi bolak-balik (RTT), peningkatan lebar pipa tidak memengaruhi kecepatan rambat sinyal bolak-balik.

#### 16. Sebuah layanan tersedia 99,9% selama satu tahun. Hitung perkiraan maksimum durasi ketidaktersediaannya. Bandingkan dengan target 99,99%.

Satu tahun biasa = **365 × 24 × 60 = 525.600 menit.**

- **Target 99,9%:**
  - Waktu mati = 0,1% × 525.600 menit = 525,6 menit ≈ **8 jam 45 menit 36 detik** per tahun.
- **Target 99,99%:**
  - Waktu mati = 0,01% × 525.600 menit = 52,56 menit ≈ **52 menit 34 detik** per tahun.
- Peningkatan dari 99,9% ke 99,99% menuntut pengurangan toleransi gangguan hingga sepersepuluhnya, membutuhkan arsitektur kluster failover otomatis tanpa intervensi manual.

#### 17. Analisis kelebihan dan kelemahan client–server serta P2P untuk distribusi berkas berukuran besar kepada ribuan pengguna.

**Client-Server:**

- **Kelebihan:** Kontrol hak akses terpusat, integritas file mudah diverifikasi, ketersediaan stabil selama server hidup.
- **Kelemahan:** Keterbatasan skala bandwidth (*server bottleneck*); biaya bandwidth server membengkak seiring bertambahnya pengunduh.

**Peer-to-Peer (P2P):**

- **Kelebihan:** Skalabilitas tinggi (semakin banyak pengunduh, kapasitas agregat unggah jaringan justru bertambah), beban server asal minim.
- **Kelemahan:** Ketergantungan pada keberadaan *seeder*, konsumsi bandwidth hulu pengguna, serta tantangan verifikasi integritas data dari node yang berpotensi jahat.

#### 18. Berikan contoh ketika topologi fisik dan topologi logis pada jaringan kampus berbeda.

- **Fisik Star, Logis Bus/Ring:** Seluruh kabel UTP dari komputer di laboratorium ditarik menuju satu konsentrator tengah (Hub atau perangkat Switch ber-VLAN bersama). Secara fisik berbentuk bintang (Star), namun jika hub menyiarkan paket ke semua port, secara logis sinyal berbagi media tunggal (Bus).
- **Fisik Star, Logis Point-to-Point:** Komputer kampus terhubung ke switch lokal, lalu membentuk terowongan VPN atau PPPoE langsung ke server gerbang kampus; secara fisik topologinya bertingkat, tetapi secara logis bertindak sebagai koneksi langsung titik-ke-titik.

### Level C — Evaluasi dan Sintesis

#### 19. Rancang klasifikasi kebutuhan jaringan kampus untuk mahasiswa, staf administrasi, tamu, kamera pengawas, dan laboratorium riset. Jelaskan alasan segmentasi dan aturan komunikasi utamanya.

**Klasifikasi Segmen (VLAN/Subnet):**

- **VLAN Mahasiswa:** Akses Internet, kuota terkontrol, isolasi antar klien.
- **VLAN Staf Administrasi:** Akses sistem informasi akademik dan database internal.
- **VLAN Tamu (Guest):** Akses publik terbatas melalui portal penangkap (*captive portal*).
- **VLAN Kamera Pengawas (CCTV):** Jalur video streaming tertutup menuju server NVR.
- **VLAN Laboratorium Riset:** Alokasi bandwidth tinggi dan hak konfigurasi port khusus.

**Alasan Segmentasi:**

- Membatasi domain siaran (*broadcast domain*), meningkatkan keamanan melalui isolasi hak akses, serta mempermudah penerapan kebijakan mutu layanan (QoS).

**Aturan Komunikasi Utama (Firewall Matrix):**

- Tamu & Mahasiswa diblokir mutlak dari akses menuju segmen Administrasi dan CCTV.
- CCTV hanya diizinkan berkomunikasi dengan IP server perekam (NVR) menggunakan port streaming spesifik.
- Mahasiswa dan Tamu diaktifkan *Client Isolation* (mencegah infeksi antar perangkat di dalam subnet yang sama).
- Laboratorium Riset diizinkan akses keluar ke Internet dan repositori akademik, namun diisolasi dari lalu lintas data operasional keuangan kampus.

#### 20. Evaluasi pernyataan: “Jaringan internal tidak memerlukan enkripsi karena sudah dilindungi firewall.” Gunakan prinsip kerahasiaan, integritas, dan ketersediaan.

Pernyataan ini keliru dan berbahaya, bertentangan dengan paradigma keamanan modern (*Zero Trust*):

- **Kerahasiaan (Confidentiality):** Firewall perimeter tidak melindungi data dari penyadapan internal (*packet sniffing*) oleh pengguna resmi, penyerang yang berhasil masuk ke jaringan lokal via Wi-Fi/port publik, atau perangkat terinfeksi malware di LAN.
- **Integritas (Integrity):** Tanpa enkripsi (seperti TLS/IPsec), paket data internal rentan terhadap serangan manipulasi *Man-in-the-Middle* (MitM) melalui teknik ARP poisoning atau DNS spoofing.
- **Ketersediaan (Availability):** Tanpa verifikasi terenkripsi antar-layanan, aktor internal jahat dapat menyuntikkan paket kendali palsu untuk melumpuhkan server database melalui pemutusan koneksi tanpa izin.

#### 21. Diskusikan mengapa Internet dapat berkembang tanpa otoritas teknis pusat tunggal. Jelaskan manfaat serta risikonya.

**Manfaat:**

- Skalabilitas global tanpa birokrasi perizinan terpusat;
- Inovasi terbuka berbasis konsensus sukarela melalui organisasi standar terbuka (IETF, ICANN, W3C, RIR);
- Ketahanan sistem tinggi tanpa satu titik kerentanan tunggal (*no single point of failure*).

**Risiko:**

- Lambatnya adopsi standar baru secara global (contoh nyata: migrasi dari IPv4 ke IPv6 membutuhkan waktu puluhan tahun);
- Masalah keamanan inheren pada protokol lawas berbasis kepercayaan terbuka (seperti kerentanan pembajakan rute BGP dan pemalsuan balasan DNS);
- Ketiadaan mekanisme penegakan hukum universal terhadap serangan siber lintas batas.

#### 22. Bandingkan circuit switching dan packet switching untuk layanan suara. Jelaskan mengapa suara modern tetap dapat berjalan pada jaringan paket.

- **Circuit Switching** mengalokasikan jalur fisik/kanal frekuensi eksklusif dengan bandwidth terjamin selama panggilan berlangsung, menghasilkan latensi konstan tanpa jitter, namun memboroskan kapasitas saat hening (*silence period*).
- **Packet Switching** memecah suara menjadi potongan paket data digital yang berbagi jalur bersama dengan lalu lintas lain, memberikan efisiensi utilisasi media transmisi yang jauh lebih tinggi.
- **Alasan Suara Modern Berjalan di Jaringan Paket:** Kemajuan teknologi kompresi audio (*codec* modern seperti Opus), tersedianya mekanisme *Quality of Service* (QoS seperti DiffServ/802.1p) untuk memprioritaskan paket suara di atas paket data lain, peningkatan kecepatan transmisi, serta penyangga *jitter buffer* adaptif di sisi penerima.

#### 23. Ambil satu keluhan nyata atau hipotetis berupa “Internet lambat”. Susun prosedur pengumpulan bukti, pengujian hipotesis, dan kriteria keberhasilan perbaikannya.

**Tahap 1: Pengumpulan Bukti Terstruktur**

- Catat waktu kejadian, alamat MAC/IP pelapor, aplikasi yang terdampak (web, streaming, game), dan jenis media akses (kabel atau Wi-Fi).
- Lakukan pengujian terukur dari terminal klien menggunakan alat diagnostik standar (ping, traceroute, iperf3 ke gateway lokal, dan uji throughput ke server CDN lokal/luar).

**Tahap 2: Pengujian Hipotesis Berjenjang**

- **Uji Lapisan Lokal (L1-L3):** Jalankan ping berkala ke IP default gateway lokal. Jika latensi tinggi (>5 ms pada kabel, >20 ms pada Wi-Fi) atau terjadi packet loss, masalah berada di segmen akses lokal.
- **Uji Resolusi Nama (L7):** Jalankan nslookup atau dig. Jika waktu query DNS tinggi, sumber masalah ada pada latensi server DNS.
- **Uji Tautan Keluar (WAN/ISP):** Lakukan pengujian beban bandwidth dari router gateway langsung ke ISP untuk memverifikasi apakah saturasi terjadi pada port uplink kampus.

**Tahap 3: Kriteria Keberhasilan Perbaikan**

- Packet loss menuju gateway internal 0% dan menuju target publik <0,5%.
- Latensi ping stabil sesuai batas acuan dasar (*baseline*).
- Nilai throughput klien mencapai batas alokasi profil bandwidth yang ditetapkan.

#### 24. Kunjungi statistik IPv6 Google atau sumber pengukuran APNIC. Catat tanggal, definisi metrik, populasi yang diukur, dan nilai untuk Indonesia. Jelaskan mengapa angka dari dua sumber dapat berbeda.

**Data Karakteristik (Berdasarkan Laporan Statistik Global Google & APNIC):**

- **Sumber 1 (Google IPv6 Adoption):** Mengukur persentase pengguna yang mengakses layanan Google melalui IPv6 secara global per negara. Populasi: Pengguna aktif Google. Nilai Indonesia berada di kisaran 15% – 18%.
- **Sumber 2 (APNIC IPv6 Measurement):** Mengukur kemampuan eksekusi script pengukuran web terdistribusi pada browser pengguna saat memuat iklan analitik. Populasi: Sampel acak pengguna web di seluruh AS (*Autonomous System*) Indonesia.

**Penyebab Perbedaan Angka Antar-Sumber:**

- **Perbedaan Metodologi Sampling:** Google hanya mengukur klien yang membuka properti Google via browser/aplikasi; APNIC menyisipkan kode pengukuran pada jaringan penayangan iklan lintas ribuan situs web pihak ketiga.
- **Perilaku Dual-Stack & Algoritma Happy Eyeballs:** Ketika perangkat memiliki IPv4 dan IPv6, algoritma sistem operasi memilih jalur paling responsif; jika jalur IPv6 lokal terdeteksi sedikit lebih lambat, kueri dialihkan ke IPv4.
- **Bias Populasi Pengguna:** Pengguna seluler (operator telco yang sudah menerapkan IPv6-only/464XLAT) memiliki adopsi IPv6 tinggi, sementara segmen ISP kabel rumahan/kantor di Indonesia sebagian besar masih mengandalkan CGNAT IPv4.

#### 25. Buat argumen mengenai penggunaan satelit orbit rendah sebagai koneksi utama atau cadangan bagi kampus di wilayah terpencil. Nilai kinerja, biaya, ketergantungan cuaca, pengelolaan, dan keamanan.

**Evaluasi Satelit Orbit Rendah (LEO) untuk Kampus Terpencil**

- **Kinerja:** Memiliki latensi kompetitif (25–45 ms) karena ketinggian orbit yang rendah (≈ 550 km), jauh lebih unggul dibandingkan satelit geostasioner (GEO, ≈ 600 ms). Throughput mampu mencapai 100–250 Mbps per terminal.
- **Biaya:** Pengeluaran belanja modal perangkat antena (*phased array*) dan biaya langganan bulanan relatif tinggi dibanding kabel darat kota, namun jauh lebih ekonomis dibandingkan menggelar serat optik melintasi medan hutan/laut.
- **Ketergantungan Cuaca:** Frekuensi gelombang mikro tinggi (pita Ku/Ka) rentan terhadap pelemahan sinyal saat terjadi hujan badai lebat (*rain fade*).
- **Pengelolaan:** Pemasangan sangat praktis (*plug-and-play*), perbaikan fisik terminal mudah ditangani secara mandiri, namun ketergantungan mutlak pada konsol manajemen milik operator satelit.
- **Keamanan:** Jalur transmisi nirkabel terbuka melintasi ruang angkasa rentan disadap atau diganggu pemancar pengacak sinyal (*jamming*), sehingga seluruh lalu lintas jaringan kampus wajib diamankan menggunakan enkripsi ujung-ke-ujung (IPsec/WireGuard).
- **Rekomendasi:** Sangat layak dijadikan koneksi utama apabila tidak ada akses serat optik, atau sebagai koneksi cadangan aktif (*failover*) jika kampus sudah memiliki jalur radio gelombang mikro (*microwave link*) darat.

#### 26. Jelaskan bagaimana otomatisasi jaringan dapat meningkatkan konsistensi sekaligus memperbesar dampak kesalahan. Usulkan kontrol teknis dan proses untuk mengurangi risiko tersebut.

- **Konsistensi vs Amplifikasi Risiko:** Otomatisasi (via Ansible, Terraform, skrip Python) mengeliminasi human-error ketik manual pada CLI, memastikan kepatuhan konfigurasi identik di ratusan router. Namun, kesalahan logika sintaks atau variabel parameter yang keliru pada satu baris kode otomatisasi akan langsung direplikasi seketika ke seluruh perangkat jaringan dalam hitungan detik, memicu pemadaman massal berskala luas (*blast radius* tak terkendali).

**Kontrol Teknis:**

- Terapkan arsitektur *Infrastructure as Code* (IaC) dengan validasi sintaks pra-penerapan (*pre-commit hooks* dan pengujian linting).
- Gunakan lingkungan laboratorium kembar digital (*Network Digital Twin* / Containerlab) untuk simulasi penerapan sebelum masuk jaringan produksi.
- Terapkan strategi penerapan bertahap (*canary deployment*): luncurkan skrip ke 5% router non-kritis terlebih dahulu, lakukan pengecekan telemetri kesehatan, baru lanjutkan ke node lainnya.

**Kontrol Proses:**

- Penerapan jalur integrasi berkelanjutan (CI/CD) yang mewajibkan peninjauan kode (*peer code review*) oleh minimal dua teknisi senior sebelum perintah digabungkan (*merge*).
- Mekanisme otomatisasi pemulihan mundur (*automated rollback*): skrip harus memverifikasi status konektivitas segera setelah konfigurasi diunggah; jika ping pengawas putus, perangkat secara otomatis mengembalikan berkas konfigurasi ke versi sebelumnya (*commit confirmed*).
