<template>
  <main class="landing">
    <section id="beranda" class="section hero">
      <p class="eyebrow">LPK Bistra | Lembaga Pelatihan Kerja</p>
      <h1>Bekal Keterampilan, Langsung Siap Masuk Dunia Kerja.</h1>
      <p class="hero-copy">
        LPK Bistra membantu peserta membangun kompetensi teknis, soft skill, dan portofolio kerja
        yang dibutuhkan industri modern.
      </p>
      <div class="hero-actions">
        <a class="btn btn-primary" href="#program">Lihat Program</a>
        <a class="btn btn-secondary" href="#kontak">Konsultasi Gratis</a>
      </div>
      <div class="hero-facts" aria-label="Ringkasan capaian">
        <article>
          <strong>1200+</strong>
          <span>alumni dibimbing</span>
        </article>
        <article>
          <strong>4.8/5</strong>
          <span>rating kepuasan peserta</span>
        </article>
        <article>
          <strong>32</strong>
          <span>mitra usaha dan industri</span>
        </article>
      </div>
    </section>

    <section id="tentang" class="section about">
      <header>
        <p class="eyebrow">Tentang LPK Bistra</p>
        <h2>Belajar dari praktik, dibimbing sampai percaya diri.</h2>
      </header>
      <p>
        Kami fokus pada pelatihan berbasis proyek nyata, simulasi kerja, dan evaluasi berkala.
        Kurikulum disusun bersama praktisi agar materi relevan dengan kebutuhan lapangan.
      </p>
      <p>
        Peserta tidak hanya memahami teori, tetapi juga terbiasa dengan ritme kerja profesional,
        komunikasi tim, dan standar pelayanan industri.
      </p>
    </section>

    <section id="program" class="section programs">
      <header>
        <p class="eyebrow">Program Pelatihan</p>
        <h2>Pilih jalur belajar sesuai minat dan target karier.</h2>
      </header>

      <div class="program-grid">
        <article class="program-card">
          <h3>Administrasi Perkantoran Digital</h3>
          <p>
            Pengelolaan dokumen, korespondensi bisnis, spreadsheet, dan praktik administrasi modern.
          </p>
          <span>Durasi: 8 minggu</span>
        </article>

        <article class="program-card">
          <h3>Desain Grafis untuk UMKM</h3>
          <p>
            Produksi materi promosi digital, branding dasar, dan tugas proyek desain sesuai brief klien.
          </p>
          <span>Durasi: 10 minggu</span>
        </article>

        <article class="program-card">
          <h3>Teknisi Komputer Dasar</h3>
          <p>
            Perakitan, troubleshooting perangkat, instalasi sistem, dan standar layanan perbaikan.
          </p>
          <span>Durasi: 9 minggu</span>
        </article>

        <article class="program-card">
          <h3>Bahasa Inggris untuk Dunia Kerja</h3>
          <p>
            Latihan percakapan kerja, presentasi, email profesional, dan simulasi wawancara.
          </p>
          <span>Durasi: 6 minggu</span>
        </article>
      </div>
    </section>

    <section id="kontak" class="section contact">
      <header>
        <p class="eyebrow">Kontak</p>
        <h2>Konsultasi program dan jadwal pendaftaran.</h2>
      </header>
      <div class="contact-grid">
        <article>
          <h3>Alamat</h3>
          <p>Jl. Anggrek Selatan No. 18, Bandung</p>
        </article>
        <article>
          <h3>WhatsApp</h3>
          <p><a href="https://wa.me/6281234567890" target="_blank" rel="noopener">+62 812-3456-7890</a></p>
        </article>
        <article>
          <h3>Email</h3>
          <p><a href="mailto:halo@lpkbistra.id">halo@lpkbistra.id</a></p>
        </article>
      </div>
    </section>

    <footer class="footer">
      <p>© 2026 LPK Bistra. Siap kerja, siap berkembang.</p>
    </footer>
  </main>
</template>

<style scoped>
:global(body) {
  margin: 0;
  color: #1f2933;
  font-family: "Plus Jakarta Sans", "Nunito Sans", "Segoe UI", sans-serif;
  line-height: 1.6;
}

:global(*) {
  box-sizing: border-box;
}

:global(a) {
  color: inherit;
}

.landing {
  width: min(1080px, calc(100% - 2.5rem));
  margin: 0 auto;
  padding: 2.25rem 0 2.75rem;
}

.section {
  border-radius: 1.5rem;
  padding: 2rem;
  margin-bottom: 1rem;
  background: rgba(255, 255, 255, 0.84);
  border: 1px solid rgba(27, 79, 96, 0.1);
  box-shadow: 0 12px 30px rgba(23, 47, 60, 0.08);
}

.eyebrow {
  display: inline-flex;
  margin: 0;
  padding: 0.35rem 0.8rem;
  border-radius: 999px;
  font-weight: 700;
  letter-spacing: 0.05em;
  font-size: 0.72rem;
  text-transform: uppercase;
  color: #0f6f62;
  background: rgba(15, 111, 98, 0.11);
}

h1,
h2,
h3 {
  margin: 0;
  font-family: "Fraunces", "Georgia", serif;
  color: #13363f;
  line-height: 1.2;
}

h1 {
  font-size: clamp(2rem, 5vw, 3.3rem);
  margin-top: 1rem;
  max-width: 18ch;
}

h2 {
  font-size: clamp(1.5rem, 3vw, 2.1rem);
  margin-top: 0.75rem;
  max-width: 28ch;
}

.hero-copy {
  margin: 1rem 0 0;
  max-width: 60ch;
  font-size: 1.03rem;
}

.hero-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 0.75rem;
  margin-top: 1.5rem;
}

.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  border-radius: 999px;
  padding: 0.8rem 1.3rem;
  text-decoration: none;
  font-weight: 700;
  transition: transform 180ms ease, box-shadow 180ms ease;
}

.btn:hover {
  transform: translateY(-1px);
}

.btn-primary {
  color: #fff;
  background: linear-gradient(120deg, #0f766e 0%, #1d8f61 100%);
  box-shadow: 0 8px 22px rgba(15, 118, 110, 0.28);
}

.btn-secondary {
  color: #164454;
  background: #fff;
  border: 1px solid rgba(22, 68, 84, 0.22);
}

.hero-facts {
  margin-top: 1.75rem;
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 0.8rem;
}

.hero-facts article {
  border-radius: 1rem;
  padding: 1rem;
  background: rgba(243, 250, 248, 0.95);
  border: 1px solid rgba(15, 118, 110, 0.16);
}

.hero-facts strong {
  display: block;
  color: #115b58;
  font-size: 1.4rem;
  margin-bottom: 0.1rem;
}

.hero-facts span {
  font-size: 0.92rem;
  color: #355362;
}

.about p {
  margin: 0.9rem 0 0;
  max-width: 70ch;
}

.program-grid {
  margin-top: 1.4rem;
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 0.9rem;
}

.program-card {
  border-radius: 1rem;
  padding: 1.2rem;
  background: #fff;
  border: 1px solid rgba(19, 54, 63, 0.14);
}

.program-card h3 {
  font-size: 1.2rem;
}

.program-card p {
  margin: 0.65rem 0;
  color: #355362;
}

.program-card span {
  display: inline-flex;
  padding: 0.3rem 0.7rem;
  border-radius: 999px;
  font-size: 0.82rem;
  font-weight: 700;
  color: #0f6f62;
  background: rgba(15, 111, 98, 0.1);
}

.contact-grid {
  margin-top: 1.3rem;
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 0.8rem;
}

.contact-grid article {
  border-radius: 1rem;
  padding: 1rem;
  background: rgba(243, 250, 248, 0.85);
  border: 1px solid rgba(19, 54, 63, 0.13);
}

.contact-grid h3 {
  font-size: 1.06rem;
  margin-bottom: 0.45rem;
}

.contact-grid p {
  margin: 0;
}

.footer {
  text-align: center;
  padding: 1.2rem 0 0;
  color: #3e5665;
  font-size: 0.92rem;
}

@media (max-width: 900px) {
  .hero-facts,
  .program-grid,
  .contact-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}

@media (max-width: 640px) {
  .landing {
    width: min(1080px, calc(100% - 1.25rem));
    padding-top: 1.1rem;
  }

  .section {
    padding: 1.25rem;
    border-radius: 1.1rem;
  }

  .hero-facts,
  .program-grid,
  .contact-grid {
    grid-template-columns: 1fr;
  }

  .hero-copy {
    font-size: 0.97rem;
  }
}
</style>
