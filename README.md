# LINEA-DE-TIEMPO-CONQUISTA
<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Línea de tiempo interactiva — La Conquista (1518–1521)</title>
  <style>
    :root{--accent:#0b5cff;--card:#fff;--bg:#f4f6fb;--text:#122;}
    body{font-family:Inter, system-ui, -apple-system, Roboto, 'Segoe UI', Arial; background:var(--bg); color:var(--text); margin:0; padding:24px}
    header{display:flex;align-items:center;gap:16px}
    h1{font-size:1.6rem;margin:0}
    .timeline{display:flex;gap:12px;overflow:auto;padding:18px 6px;margin-top:18px}
    .event{min-width:300px;background:linear-gradient(180deg,#fff,#fbfdff);border-radius:12px;box-shadow:0 6px 18px rgba(10,20,40,.06);padding:14px;border:1px solid rgba(10,20,40,.04)}
    .meta{font-size:.9rem;color:#556;}
    .title{font-weight:700;margin:.2rem 0 .4rem}
    .imgwrap{height:160px;border-radius:8px;overflow:hidden;background:#eee;display:flex;align-items:center;justify-content:center}
    .imgwrap img{max-width:100%;height:100%;object-fit:cover}
    .desc{font-size:.95rem;line-height:1.35;margin-top:.5rem}
    .controls{display:flex;gap:8px;align-items:center;margin-top:12px}
    .btn{background:var(--accent);color:#fff;padding:8px 10px;border-radius:8px;text-decoration:none;font-weight:600}
    footer{margin-top:18px;color:#556;font-size:.9rem}

    /* Desktop layout tweak */
    @media(min-width:900px){
      .timeline{flex-wrap:nowrap}
    }
  </style>
</head>
<body>
  <header>
    <img src="" alt="ícono" style="width:64px;height:64px;border-radius:8px;background:linear-gradient(135deg,var(--accent),#16b3ff)">
    <div>
      <h1>Línea de tiempo interactiva — La Conquista (1518 → 13 de agosto de 1521)</h1>
      <div class="meta"></div>
    </div>
  </header>

  <div class="timeline" id="timeline">
    <!-- Event cards: cada tarjeta tiene fecha, título, imagen (enlace), explicación breve y botón para ver más -->

    <article class="event" data-date="1518">
      <div class="meta">1518</div>
      <div class="title">Expedición de Juan de Grijalva</div>
      <div class="imgwrap"><a href="https://www.worldhistory.org/image/16225/juan-de-grijalva-meeting-a-maya-chief/" target="_blank">Ver ilustración</a></div>
      <div class="desc">Juan de Grijalva bordea las costas del Golfo de México y explora la región. Sus reportes motivan nuevas expediciones españolas hacia el interior.</div>
      <div class="controls"><a class="btn" href="#" onclick="focusEvent(0);return false">Ir</a></div>
    </article>

    <article class="event" data-date="feb-1519">
      <div class="meta">Febrero 1519</div>
      <div class="title">Llegada a Cozumel</div>
      <div class="imgwrap"><a href="https://www.granger.com/0119895-cortez-landing-1519-hernando-cortes-landing-at-veracruz-spr-image.html" target="_blank">Ilustración: Arribo</a></div>
      <div class="desc">Hernán Cortés llega a las costas (Cozumel) y establece los primeros contactos con pueblos mayas; continua su avance hacia el valle de México.</div>
      <div class="controls"><a class="btn" href="#" onclick="focusEvent(1);return false">Ir</a></div>
    </article>

    <article class="event" data-date="mar-1519">
      <div class="meta">15 de marzo de 1519</div>
      <div class="title">La Malinche (Malintzin) se une a Cortés</div>
      <div class="imgwrap"><a href="https://es.wikipedia.org/wiki/La_Malinche" target="_blank">Ver retratos y fuentes</a></div>
      <div class="desc">En Tabasco, tras una victoria, los indígenas regalan mujeres a los españoles. Una de ellas, Malintzin, hablará maya y náhuatl, sirviendo de intérprete y consejera clave.</div>
      <div class="controls"><a class="btn" href="#" onclick="focusEvent(2);return false">Ir</a></div>
    </article>

    <article class="event" data-date="apr-1519">
      <div class="meta">Abril 1519</div>
      <div class="title">Fundación de La Villa Rica de la Vera Cruz y desmantelamiento de las naves</div>
      <div class="imgwrap"><a href="https://www.gettyimages.com/detail/news-photo/scene-of-cortes-destruction-of-his-ships-news-photo/" target="_blank">Ilustración</a></div>
      <div class="desc">Cortés funda la Villa Rica de la Vera Cruz para legitimar su expedición y, para evitar la retirada, desmantela o hunde las naves — acto simbólico de compromiso con la conquista.</div>
      <div class="controls"><a class="btn" href="#" onclick="focusEvent(3);return false">Ir</a></div>
    </article>

    <article class="event" data-date="mid-1519">
      <div class="meta">Mediados de 1519</div>
      <div class="title">Alianza con Tlaxcala</div>
      <div class="imgwrap"><a href="https://www.britannica.com/biography/Hernan-Cortes" target="_blank">Contexto histórico</a></div>
      <div class="desc">Tras vencer o negociar con pueblos locales, los tlaxcaltecas se alían con los españoles: esta alianza será decisiva contra Tenochtitlan.</div>
      <div class="controls"><a class="btn" href="#" onclick="focusEvent(4);return false">Ir</a></div>
    </article>

    <article class="event" data-date="oct-1519">
      <div class="meta">Octubre–Noviembre 1519</div>
      <div class="title">Matanza de Cholula</div>
      <div class="imgwrap"><a href="https://www.britannica.com/place/Cholula" target="_blank">Más sobre Cholula</a></div>
      <div class="desc">En Cholula, por sospechas de traición, Pedro de Alvarado ordena una matanza masiva en el templo; esto enardece a muchas comunidades mexicas y marca un punto de no retorno.</div>
      <div class="controls"><a class="btn" href="#" onclick="focusEvent(5);return false">Ir</a></div>
    </article>

    <article class="event" data-date="nov-1519">
      <div class="meta">Noviembre 1519</div>
      <div class="title">Entrada a Tenochtitlan</div>
      <div class="imgwrap"><a href="https://commons.wikimedia.org/wiki/File%3AConquista-de-M%C3%A9xico-por-Cort%C3%A9s-Tenochtitlan-Painting.png" target="_blank">Ver pintura (Commons)</a></div>
      <div class="desc">Los españoles son recibidos por Moctezuma II y hospedados en el Palacio de Axayácatl; las tensiones aumentan cuando Cortés toma prisionero al tlatoani.</div>
      <div class="controls"><a class="btn" href="#" onclick="focusEvent(6);return false">Ir</a></div>
    </article>

    <article class="event" data-date="may-1520">
      <div class="meta">Mayo–Junio 1520</div>
      <div class="title">Salida de Cortés y la Matanza del Templo Mayor</div>
      <div class="imgwrap"><a href="https://www.britannica.com/event/Spanish-conquest-of-Mexico" target="_blank">Contexto y fuentes</a></div>
      <div class="desc">Cortés marcha para enfrentarse a Pánfilo de Narváez; deja a Pedro de Alvarado al mando, quien provoca la matanza del Templo Mayor. Esto provoca la revuelta mexica.</div>
      <div class="controls"><a class="btn" href="#" onclick="focusEvent(7);return false">Ir</a></div>
    </article>

    <article class="event" data-date="jun-30-1520">
      <div class="meta">30 de junio de 1520</div>
      <div class="title">La Noche Triste</div>
      <div class="imgwrap"><a href="https://www.worldhistory.org/article/1250/la-noche-triste/" target="_blank">Leer sobre La Noche Triste</a></div>
      <div class="desc">Los españoles intentan huir cargando tesoros; son descubiertos y sufren grandes pérdidas en la retirada desde Tenochtitlan — un duro revés para la expedición.</div>
      <div class="controls"><a class="btn" href="#" onclick="focusEvent(8);return false">Ir</a></div>
    </article>

    <article class="event" data-date="1520-1521">
      <div class="meta">Invierno 1520 — 1521</div>
      <div class="title">Reagrupamiento, viruela y construcción de bergantines</div>
      <div class="imgwrap"><a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1570189/" target="_blank">Estudios sobre enfermedades</a></div>
      <div class="desc">Los españoles se reagrupan en Tlaxcala. La viruela (traída por los europeos) debilita a la población mexica; los españoles construyen bergantines para controlar las aguas y aislar la ciudad.</div>
      <div class="controls"><a class="btn" href="#" onclick="focusEvent(9);return false">Ir</a></div>
    </article>

    <article class="event" data-date="aug-13-1521">
      <div class="meta">13 de agosto de 1521</div>
      <div class="title">Caída de Tenochtitlan</div>
      <div class="imgwrap"><a href="https://commons.wikimedia.org/wiki/File%3AThe_Conquest_of_Tenochtitlan.jpg" target="_blank">Ilustración (Commons)</a></div>
      <div class="desc">Tras meses de asedio, hambre y enfermedades, la ciudad cae. Cuauhtémoc es capturado y con esto termina el dominio mexica y comienza la era colonial española.</div>
      <div class="controls"><a class="btn" href="#" onclick="focusEvent(10);return false">Ir</a></div>
    </article>

  </div>

  <footer>
    Fuentes (imágenes y síntesis breve): Wikimedia Commons, WorldHistory.org, Britannica, artículos históricos y la presentación de la maestra. Los enlaces en cada tarjeta llevan a ilustraciones y artículos de referencia.
  </footer>

  <script>
    const events = Array.from(document.querySelectorAll('.event'));
    function focusEvent(i){
      const el = events[i];
      if(!el) return; el.scrollIntoView({behavior:'smooth',block:'center',inline:'center'});
      el.animate([{transform:'scale(.98)'},{transform:'scale(1)'}],{duration:300});
      el.style.outline='3px solid rgba(11,92,255,.12)';
      setTimeout(()=>el.style.outline='none',900);
    }
    // keyboard navigation
    let idx=0; window.addEventListener('keydown',e=>{
      if(e.key==='ArrowRight'){ idx=Math.min(events.length-1,++idx); events[idx].scrollIntoView({behavior:'smooth',inline:'center'}); }
      if(e.key==='ArrowLeft'){ idx=Math.max(0,--idx); events[idx].scrollIntoView({behavior:'smooth',inline:'center'}); }
    });
  </script>
</body>
</html>
