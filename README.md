# web-discoteca-el-molar
KARAOKE TANIT
Galería Contacto Reservar
Interior de Karaoke Tanit con mural neón y cabina DJ
El Molar · Madrid

Donde la noche nunca termina

Música, karaoke, luces neón y un ambiente pensado para celebrar cada noche. Descubre KARAOKE TANIT y reserva tu próxima salida.

Ver Próximos Eventos Cómo llegar
Concepto visual

Una discoteca con identidad neón

Estética

Negro absoluto, rosa neón, morado eléctrico y destellos de verde para una imagen intensa y moderna.

Experiencia

Espacios diferenciados para bailar, tomar algo, entrar al baño con comodidad y disfrutar del ambiente completo.

Reservas

Contacto directo por WhatsApp para consultas, eventos privados y celebraciones.

Galería

Fotos en el orden indicado

La galería está organizada exactamente según la estructura del documento: zona de baile, baños, barra y exterior.

Zona de baile

Recorrido visual del interior principal y la pista, manteniendo el mismo orden del documento.

Zona de baile de Karaoke Tanit con iluminación azul
Vista lateral de la zona de baile y cabina
Barra iluminada desde el pasillo lateral
Pista con círculos de luz azul
Interior de la sala con barra y luces de colores
Baños

Baños separados y espacio adaptado.

Puertas de baños separados chico y chica
Baño adaptado con lavabo y barras de apoyo
Barra

Zona de servicio y botellería con estética oscura y puntos de color.

Vista interior de la barra con botellas
Botellería de la barra
Exterior

Fachada y acceso principal del local.

Rótulo exterior de Karaoke Tanit
Entrada exterior de Karaoke Tanit en la calle
Contacto

Reserva tu próxima noche

Haz tu reserva o consulta disponibilidad para eventos, cumpleaños y celebraciones.

Dirección Calle Pocito, 5 · El Molar 28710
Horario
Jueves a sábado · 22:00 a 06:00

WhatsApp reservas +34 649 87 49 33
Redes sociales
Instagram TikTok Facebook
© KARAOKE TANIT · Donde la noche nunca termina

document.getElementById('year').textContent = new Date().getFullYear();
:root {
  --bg: #07070b;
  --surface: rgba(18, 18, 28, 0.78);
  --surface-strong: rgba(23, 23, 36, 0.96);
  --text: #f4f4f8;
  --muted: #b7b7c9;
  --pink: #ff007f;
  --purple: #9d00ff;
  --green: #00ffa3;
  --border: rgba(255, 255, 255, 0.1);
  --shadow: 0 20px 60px rgba(0, 0, 0, 0.45);
  --radius: 24px;
}

* { box-sizing: border-box; }
html { scroll-behavior: smooth; }
body {
  margin: 0;
  font-family: 'Montserrat', sans-serif;
  background:
    radial-gradient(circle at top left, rgba(157, 0, 255, 0.15), transparent 30%),
    radial-gradient(circle at top right, rgba(255, 0, 127, 0.12), transparent 25%),
    var(--bg);
  color: var(--text);
}

img { display: block; max-width: 100%; }
a { color: inherit; text-decoration: none; }

.container {
  width: min(1120px, calc(100% - 32px));
  margin: 0 auto;
}

.bg-glow {
  position: fixed;
  inset: auto;
  width: 420px;
  height: 420px;
  filter: blur(110px);
  opacity: 0.18;
  z-index: 0;
  pointer-events: none;
}
.bg-glow-1 { top: 10%; left: -120px; background: var(--pink); }
.bg-glow-2 { bottom: 5%; right: -120px; background: var(--purple); }

.site-header {
  position: sticky;
  top: 0;
  z-index: 20;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 18px 24px;
  backdrop-filter: blur(16px);
  background: rgba(7, 7, 11, 0.72);
  border-bottom: 1px solid var(--border);
}

.logo {
  display: inline-flex;
  flex-direction: column;
  gap: 2px;
  line-height: 1;
}
.logo-main, .logo-sub {
  font-weight: 800;
  letter-spacing: 0.2em;
}
.logo-main { font-size: 0.88rem; color: var(--muted); }
.logo-sub {
  font-size: 1.2rem;
  color: white;
  text-shadow: 0 0 12px rgba(255, 0, 127, 0.55);
}

.nav {
  display: flex;
  align-items: center;
  gap: 18px;
}
.nav a { color: var(--muted); font-weight: 600; }
.nav a:hover { color: white; }

.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 14px 22px;
  border-radius: 999px;
  background: linear-gradient(135deg, var(--pink), var(--purple));
  color: white;
  font-weight: 700;
  box-shadow: 0 10px 30px rgba(157, 0, 255, 0.35);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}
.btn:hover { transform: translateY(-2px); box-shadow: 0 16px 34px rgba(157, 0, 255, 0.45); }
.btn-small { padding: 10px 16px; }
.btn-secondary {
  background: transparent;
  border: 1px solid rgba(255,255,255,.18);
  box-shadow: none;
}

.hero {
  position: relative;
  min-height: 88vh;
  display: grid;
  place-items: center;
  overflow: hidden;
}
.hero-image {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
  filter: saturate(1.1);
}
.hero-overlay {
  position: absolute;
  inset: 0;
  background:
    linear-gradient(180deg, rgba(7,7,11,0.35), rgba(7,7,11,0.86)),
    radial-gradient(circle at center, rgba(157,0,255,.18), transparent 30%);
}
.hero-content {
  position: relative;
  z-index: 1;
  padding: 90px 0;
}
.eyebrow {
  text-transform: uppercase;
  letter-spacing: .22em;
  color: var(--green);
  font-size: .78rem;
  font-weight: 700;
  margin-bottom: 14px;
}
.hero h1 {
  margin: 0;
  max-width: 780px;
  font-size: clamp(3rem, 9vw, 6.2rem);
  line-height: .95;
}
.hero h1 span { color: var(--pink); }
.hero-text {
  max-width: 620px;
  margin: 22px 0 0;
  color: #e7e7f5;
  font-size: 1.05rem;
  line-height: 1.7;
}
.hero-actions {
  display: flex;
  gap: 14px;
  flex-wrap: wrap;
  margin-top: 28px;
}

section { position: relative; z-index: 1; }
.intro, .gallery-section { padding: 96px 0 24px; }
.section-heading { margin-bottom: 30px; }
.section-heading h2 {
  margin: 0 0 12px;
  font-size: clamp(2rem, 4vw, 3.2rem);
}
.section-heading p { color: var(--muted); max-width: 760px; line-height: 1.7; }

.intro-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 18px;
}
.card {
  background: var(--surface);
  border: 1px solid var(--border);
  border-radius: var(--radius);
  box-shadow: var(--shadow);
  backdrop-filter: blur(16px);
}
.feature-card { padding: 24px; }
.feature-card h3 { margin-top: 0; margin-bottom: 10px; }
.feature-card p { margin: 0; color: var(--muted); line-height: 1.7; }

.gallery-block {
  margin-bottom: 32px;
  padding: 24px;
  border: 1px solid var(--border);
  border-radius: calc(var(--radius) + 4px);
  background: var(--surface);
  box-shadow: var(--shadow);
}
.block-header { margin-bottom: 18px; }
.block-header h3 { margin: 0 0 8px; font-size: 1.45rem; }
.block-header p { margin: 0; color: var(--muted); }

.photo-grid {
  display: grid;
  gap: 16px;
}
.photo-grid-dance {
  grid-template-columns: 1.2fr .8fr .8fr;
  grid-auto-rows: 260px;
}
.photo-grid-two {
  grid-template-columns: repeat(2, 1fr);
}
.photo-card {
  overflow: hidden;
  border-radius: 20px;
  background: #111;
  border: 1px solid rgba(255,255,255,.08);
}
.photo-card img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  transition: transform .35s ease;
}
.photo-card:hover img { transform: scale(1.03); }
.photo-card-large { grid-row: span 2; }
.photo-card-wide { grid-column: span 2; }
.photo-grid-two .photo-card { aspect-ratio: 16 / 10; }

.contact-section { padding: 72px 0 96px; }
.contact-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 28px;
  align-items: start;
}
.contact-text { color: var(--muted); max-width: 520px; line-height: 1.7; }
.contact-card { padding: 28px; }
.contact-list {
  list-style: none;
  margin: 0;
  padding: 0;
  display: grid;
  gap: 22px;
}
.contact-list li span {
  display: block;
  margin-bottom: 6px;
  font-size: .84rem;
  text-transform: uppercase;
  letter-spacing: .14em;
  color: var(--green);
  font-weight: 700;
}
.contact-list p,
.contact-list a { margin: 0; color: white; font-weight: 600; }
.social-links { display: flex; flex-wrap: wrap; gap: 10px; }
.social-links a {
  padding: 10px 14px;
  border: 1px solid rgba(255,255,255,.12);
  border-radius: 999px;
  color: var(--muted);
}
.social-links a:hover { color: white; border-color: rgba(255,255,255,.25); }

.site-footer {
  padding: 24px;
  text-align: center;
  color: var(--muted);
  border-top: 1px solid var(--border);
}

@media (max-width: 980px) {
  .intro-grid,
  .contact-grid,
  .photo-grid-two {
    grid-template-columns: 1fr;
  }

  .photo-grid-dance {
    grid-template-columns: 1fr;
    grid-auto-rows: 260px;
  }

  .photo-card-large,
  .photo-card-wide { grid-row: auto; grid-column: auto; }
}

@media (max-width: 720px) {
  .site-header {
    padding: 14px 16px;
    gap: 16px;
    flex-direction: column;
  }

  .nav {
    width: 100%;
    justify-content: center;
    flex-wrap: wrap;
  }

  .hero-content { padding: 54px 0 72px; }
  .gallery-block { padding: 18px; }
}
