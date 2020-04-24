<!DOCTYPE html>
<html lang="id">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>El Mahad : Sekolah Online</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <header>
      <nav class="grid">
        <div class="logo">
          <a href="/index.html"
            ><img src="assets/mobile/logo-elmahad-nav.png" alt="Logo El Mahad"
          /></a>
        </div>
        <div class="hamburger">
          <a href="#0" onclick="openSlideMenu()">
            <img src="assets/mobile/hamburger.svg" alt="Navigasi hamburger">
          </a>
        </div>
        <ul>
          <li><a href="#deskripsi">Kursus</a></li>
          <li><a href="#">Tentang kami</a></li>
          <li><a href="#">Tanya kami</a></li>
          <li>
            <a class="sign-in" href="#">Sign in</a>
          </li>
          <li>
            <a class="daftar" href="#">Daftar</a>
          </li>
        </ul>
        <div id="side-menu" class="side-nav">
          <a href="#0" class="btn-close" onclick="closeSlideMenu()">&times;</a>
          <a href="#deskripsi">Kursus</a>
          <a href="#0">Tentang kami</a>
          <a href="#0">Tanya kami</a>
          <a href="#0" class="sign-in">Sign in</a>
          <a href="#0" class="daftar">Daftar</a>
        </div>
      </nav>
      <section class="hero">
        <div class="hero-text">
          <h1>Bahagia Dunia <br />dan Akhirat</h1>
          <p>
            Kami meyakini kebahagiaan dunia dan akhirat itu ada di dalam Islam.
            Sebagaimana kami ingin bahagia. Kami juga ingin anda bahagia
          </p>
          <a href="#deskripsi" class="cta">Pelajari lebih lengkap</a>
        </div>
        <!-- <div class="hero-img">
          <img
            src="assets/mobile/hero@2x.png"
            alt="Pulpen dan ilustrasi lingkaran kuning"
          />
        </div> -->
      </section>
    </header>

    <section id="deskripsi" class="pendahuluan">
      <div class="pendahuluan-text">
        <h2>Kebahagian dan keselamatan itu wajib</h2>
        <p>
          Kewajiban tersebut terpenuhi diawali dengan pendidikan berkualitas yang
          bermuara dari Al-Quran dan As-Sunnah berdasarkan pemahaman Rasulullah
          shallahu ‘alaihi wasallam berserta para sahabatnya radhi‘allahu ‘anhum
        </p>
        <p>
          Disini anda akan belajar dari program pembelajaran berbasis video pada
          platform online modern dengan website yang mengikuti kurikulum yang
          dibuat oleh ahli agama. Anda akan belajar :
        </p>
      </div>
      <div class="fitur grid">
        <div class="materi">
          <img src="assets/mobile/rukun-iman.svg" alt="Icon ilustrasi hati" />
          <p class="materi-text">Rukun Iman</p>
        </div>
        <div class="materi">
          <img
            src="assets/mobile/rukun-islam.svg"
            alt="Icon ilustrasi lima jari"
          />
          <p class="materi-text">Rukun Islam</p>
        </div>
        <div class="materi">
          <img
            src="assets/mobile/mengenal-allah.svg"
            alt="Icon kaligrafi Allah Ta'ala"
          />
          <p class="materi-text">
            Mengenal Nama &amp; Sifat Allah <span>ﷻ</span>
          </p>
        </div>
        <div class="materi">
          <img
            src="assets/mobile/mengenal-rasul.svg"
            alt="Icon kaligrafi Nabi Muhammad shallahu 'alaihi wasallam"
          />
          <p class="materi-text">
            Mengenal Sifat &amp; Perilaku Rasulullah <span>ﷺ</span>
          </p>
        </div>
        <div class="materi">
          <img
            src="assets/mobile/adab-ilmu.svg"
            alt="Icon ilustrasi pulpen"
          />
          <p class="materi-text">Adab Menuntut Ilmu Syari'i</p>
        </div>
        <div class="materi">
          <img
            src="assets/mobile/tafsir-surat-pendek.svg"
            alt="Icon ilustrasi buku terbuka"
          />
          <p class="materi-text">Tafsir Surat Pendek</p>
        </div>
        <div class="materi">
          <img
            src="assets/mobile/hukum-muamalah.svg"
            alt="Icon ilustrasi mata uang rupiah"
          />
          <p class="materi-text">Muamalah Dasar</p>
        </div>
      </div>
    </section>

    <section class="grupTargetUser">
      <h2>
        Calon orang yang berbahagia
        <div class="border"></div>
      </h2>
      <div>
        <div class="targerUser">
          <div class="icon-number">01</div>
          <h3>Pelajar</h3>
          <p>
            Identitas Islamik pada seorang muslim tidak boleh hilang.
            Pertahankan identitas anda di masa pergaulan bebas dan capai lah
            kebahagiaan hakiki
          </p>
        </div>
        <div class="targerUser">
          <div class="icon-number">02</div>
          <h3>Orang Tua</h3>
          <p>
            Kebahagiaan keluarga tentunya merupakan idaman semua orang.
            Bimbing lah keluarga anda kepada kebagiaan
          </p>
        </div>
        <div class="targerUser">
          <div class="icon-number">03</div>
          <h3>Pekerja</h3>
          <p>
            Mencari nafkah untuk keperluan jasmani adalah hal yang terpuji.
            Terpenuhinya keperluan rohani adalah kebahagiaan sejati
          </p>
        </div>
      </div>
    </section>

    <section class="grupFitur">
      <h2>Apa yang kamu dapatkan?</h2>
      <div class="grid">
        <div class="fitur">
          <img
            src="assets/mobile/kurikulum-berkualitas.svg"
            alt="Icon ilustrasi acung jempol"
          />
          <div class="fitur-text">
            <h3>Kurikulum berkualitas</h3>
            <ul class="fitur-list">
              <li>Pembelajaran terarah dan terbimbing</li>
              <li>Dibuat oleh para ahli agama</li>
              <li>Pembelajaran dirangkum</li>
              <li>Pembelajaran berjenjang</li>
            </ul>
          </div>
        </div>
        <div class="fitur">
          <img
            src="assets/mobile/platform-modern.svg"
            alt="Icon ilusrasi platform media pembelajaran online"
          />
          <div class="fitur-text">
            <h3>Platform modern</h3>
            <ul class="fitur-list">
              <li>Platform website</li>
              <li>Belajar dengan video</li>
              <li>Kuis</li>
              <li>Pembelajaran menarik</li>
              <li>Jadwal mandiri</li>
              <li>Akses materi selamanya</li>
              <li>Materi bisa di download</li>
            </ul>
          </div>
        </div>
        <div class="fitur">
          <img
            src="assets/mobile/pengajar-terpercaya.svg"
            alt="Icon ilustarsi pengajar"
          />
          <div class="fitur-text">
            <h3>Pengajar terpercaya</h3>
            <ul class="fitur-list">
              <li>Lulusan Universitas Islam terpandang dan terpercaya</li>
              <li>Menggunakan Bahasa Indonesia</li>
            </ul>
          </div>
        </div>
        <div class="fitur fitur-cta">
          <img
            src="assets/mobile/kompetensi-agama.svg"
            alt="Icon ilustrasi penghargaan"
          />
          <div class="fitur-text">
            <h3>Kompetensi agama</h3>
            <ul class="fitur-list">
              <li>Pemenuhan pendidikan Islam yang wajib</li>
              <li>Sertifikat kelulusan</li>
            </ul>
          </div>
          <a href="" class="cta">Daftar</a>
        </div>
      </div>
    </section>

    <section class="keunggulan">
      <img
        src="assets/mobile/mengapa-kami.png"
        alt="Tangan yang memegang handphone"
      />
      <div class="keunggulan-text">
        <h2>Mengapa kami?</h2>
        <p>
          Hanya kami satu-satunya di Indonesia yang menghadirkan program
          pendidikan Islam dengan platform website yang memiliki jadwal sesuai
          keinginan anda dan menjamin terpenuhinya pendidikan Islam yang wajib
        </p>
      </div>
    </section>

    <section class="rekomendasi">
      <h2>Rekomendasi Ustadz</h2>
      <div class="grupRekomendasi">
        <div class="g-rekomendasi">
          <img
            src="assets/mobile/pengajar-terpercaya.svg"
            alt="Icon ilustrasi pemberi rekomendasi"
          />
          <div class="tokoh">
            <p><strong>Ust. Dr. Syafiq Riza Basalamah, Lc. MA.</strong></p>
            <p class="tokoh-posisi">Dosen tetap STDI Imam Syafi'i</p>
            <p class="almamater">Universitas Islam Madinah</p>
            <div class="border"></div>
          </div>
          <p class="perkataan">
            Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
            nonumy eirmod tempo
          </p>
        </div>
        <div class="g-rekomendasi">
          <img
            src="assets/mobile/pengajar-terpercaya.svg"
            alt="Icon ilustrasi pemberi rekomendasi"
          />
          <div class="tokoh">
            <p><strong>Ust. Dr. Syafiq Riza Basalamah, Lc. MA.</strong></p>
            <p class="tokoh-posisi">Dosen tetap STDI Imam Syafi'i</p>
            <p class="almamater">Universitas Islam Madinah</p>
            <div class="border"></div>
          </div>
          <p class="perkataan">
            Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
            nonumy eirmod tempo
          </p>
        </div>
        <div class="g-rekomendasi">
          <img
            src="assets/mobile/pengajar-terpercaya.svg"
            alt="Icon ilustrasi pemberi rekomendasi"
          />
          <div class="tokoh">
            <p><strong>Ust. Dr. Syafiq Riza Basalamah, Lc. MA.</strong></p>
            <p class="tokoh-posisi">Dosen tetap STDI Imam Syafi'i</p>
            <p class="almamater">Universitas Islam Madinah</p>
            <div class="border"></div>
          </div>
          <p class="perkataan">
            Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam
            nonumy eirmod tempo
          </p>
        </div>
      </div>
    </section>

    <div class="biaya-wrapper">
      <section class="biaya">
        <h2>Biaya program</h2>
        <div>
          <p class="nominal">0</p>
          <p class="mata-uang">Rp</p>
        </div>
        <p class="teks-kecil">* Tanpa syarat dan ketentuan</p>
        <a href="" class="cta">Daftar</a>
      </section>
    </div>
    
    <section class="partner">
      <h2>Partner kami</h2>
      <div class="grupPartners">
        <img src="assets/mobile/stdi@2x.png" alt="Logo HSI Abdullah Roy" />
        <img src="assets/mobile/hsi@2x.png" alt="Logo STDI Imam Syafi'i" />
      </div>
    </section>

    <section class="kerjasama">
      <div class="kerjasama-text">
        <h2>Dukung kami</h2>
        <p>
          Tim kami fokus pada usaha untuk memberikan jalan untuk meraih
          kebahagian dunia dan akhirat kepada umat muslimin di era modern.
          Kami melakukan hal tersebut dengan memberikan pendidikan Islam
          sesuai Al-Quran dan As-Sunnah dengan platform website. Kami selalu
          senang mendapatkan partner yang memiliki visi yang sama dan ingin
          membantu kami menyebar kebahagiaan yang lebih merata pada umat
        </p>
        <a href="" class="cta">Saya mau</a>
      </div>
      <img
        src="assets/mobile/dukung-kami@2x.png"
        alt="Tangan yang menandatangani kontrak"
      />
      <!-- <div class="kerjasama-gambar">
        <img
          src="assets/mobile/dukung-kami@2x.png"
          alt="Tangan yang menandatangani kontrak"
        />
      </div> -->
    </section>
    <div class="footer-wrapper">
      <footer class="grid">
        <div class="logo-footer">
          <a href="index.html">
            <img src="assets/mobile/logo-elmahad-footer.png" alt="Logo El Mahad" />
          </a>
        </div>
        <div class="kontak">
          <div class="alamat">
            <p class="heading">Alamat kantor</p>
            <p>Jalan Ahmad Dahlan no. 69 RT 5 RW 3 Karanganyar Ambulu Jember
              68172</p>
          </div>
          <div class="kontakPerson">
            <p class="heading">Hubungi kami</p>
            <p>elmahadindonesia@gmail.com</p>
          </div>
        </div>
        <div class="mediaSosial">
          <p class="heading">Media Sosial</p>
          <a href="" class="social">Instagram</a>
          <a href="" class="social">Facebook</a>
          <a href="" class="social">Youtube</a>
        </div>
        <p class="copyright">Copyright &copy;2020 Yayasan El-Mahad</p>
      </footer class="grid">
    </div>
    <script>
      function openSlideMenu() {
        document.getElementById("side-menu").style.width = "50vw";
      }

      function closeSlideMenu() {
        document.getElementById("side-menu").style.width = "0";
      }
    </script>
  </body>
</html>