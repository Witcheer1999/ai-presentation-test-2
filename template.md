---
marp: true
theme: brand-pro
paginate: true
---

<!-- Cover -->
<!-- class: lead center-y -->
# Deep Learning e Reti Neurali <span class="accent">Demo</span>
## Tutti i layout e le utility del tema
<span class="badge">Brand-Pro</span>

---

<!-- Standard scaffold (title–subtitle–corpus) -->
# Standard scaffold
## Sottotitolo coerente
<div class="corpus">
Testo di <span class="hl">corpo</span> con highlight blu e <span class="accent">accent magenta</span> per enfasi nei titoli.
</div>

---

<!-- Container + stack spacing -->
# Container & Stack
<div class="container stack">
  <p>Il wrapper <code>.container</code> limita la larghezza ideale.</p>
  <p>La classe <code>.stack</code> aggiunge spazio verticale tra i figli.</p>
  <p class="muted">Questa riga è mutata.</p>
</div>

---

<!-- Typography styles -->
# Tipografia
## Livelli tipografici
<div class="corpus">
<h3>H3 in evidenza</h3>
<p class="caption">Didascalia con <code>.caption</code></p>
<p class="eyebrow">EYEBROW / SEZIONE</p>
</div>

---

<!-- Bullets variants -->
# Liste puntate
<div class="split">
  <div>
    <h3>Default</h3>
    <ul>
      <li>Elemento A</li>
      <li>Elemento B</li>
    </ul>
    <h3 class="mt-m">Tight</h3>
    <ul class="bullets--tight">
      <li>Compatto 1</li>
      <li>Compatto 2</li>
    </ul>
    <h3 class="mt-m">Loose</h3>
    <ul class="bullets--loose">
      <li>Largo 1</li>
      <li>Largo 2</li>
    </ul>
  </div>
  <div>
    <h3>Check</h3>
    <ul class="bullets--check">
      <li>Requisito 1</li>
      <li>Requisito 2</li>
    </ul>
    <h3 class="mt-m">Dash</h3>
    <ul class="bullets--dash">
      <li>Punto 1</li>
      <li>Punto 2</li>
    </ul>
    <h3 class="mt-m">Big</h3>
    <ul class="bullets--big">
      <li>Importante 1</li>
      <li>Importante 2</li>
    </ul>
  </div>
</div>

---

<!-- 2×2 grid + cards (incl. tinted) -->
# Grid 2×2 + Cards
<div class="grid-2x2">
  <div class="card">
    <h3>Card base</h3>
    <p class="muted">Superficie bianca + bordo.</p>
  </div>
  <div class="card card--tint-blue">
    <h3>Tinta blue</h3>
    <p>Per evidenziare.</p>
  </div>
  <div class="card card--tint-mag">
    <h3>Tinta magenta</h3>
    <p>Per accentuare.</p>
  </div>
  <div class="card">
    <h3>Card base</h3>
    <p>Neutra.</p>
  </div>
</div>

---

<!-- 3 columns + feature box -->
# 3 colonne (feature)
<div class="cols-3">
  <div class="feature">
    <h3>Dataset</h3>
    <ul class="bullets--tight"><li>Raccolta</li><li>Pulizia</li></ul>
  </div>
  <div class="feature">
    <h3>Training</h3>
    <ul class="bullets--dash"><li>Baseline</li><li>Tuning</li></ul>
  </div>
  <div class="feature">
    <h3>Deploy</h3>
    <ul class="bullets--check"><li>API</li><li>Monitor</li></ul>
  </div>
</div>

---

<!-- Split layout + callouts + KPI -->
# Split + Callout + KPI
<div class="split">
  <div class="card">
    <h3>Problema</h3>
    <p>Classi sbilanciate, <span class="hl">precision</span> bassa.</p>
    <div class="callout mt-s">
      <strong>Nota:</strong> Bilanciamento con pesi.
    </div>
    <div class="callout callout--info mt-s">
      <strong>Info:</strong> Valutazione stratificata.
    </div>
    <div class="callout callout--success mt-s">
      <strong>OK:</strong> Overfitting ridotto.
    </div>
    <div class="callout callout--warn mt-s">
      <strong>Attenzione:</strong> Dati rumorosi.
    </div>
  </div>
  <div class="kpi">
    <div class="kpi__value">+27%</div>
    <div class="kpi__label">Accuracy vs baseline</div>
    <div class="hr mt-s"></div>
    <div class="caption">Validazione 5-fold</div>
    <div class="badges mt-m">
      <span class="pill">CV</span>
      <span class="pill pill--accent">F1</span>
      <span class="pill pill--ink">ROC-AUC</span>
    </div>
  </div>
</div>

---

<!-- Media layout -->
# Media layout
<div class="media">
  <div class="img--rounded">
    <img src="https://picsum.photos/800/600" alt="Example"/>
  </div>
  <div>
    <h3>Immagine + testo</h3>
    <p class="corpus">Usa <code>.media</code> per una colonna visual e una testuale.</p>
    <p class="muted">L’immagine è arrotondata con <code>.img--rounded</code>.</p>
  </div>
</div>

---

<!-- Figure with side caption -->
# Figure con didascalia laterale
<div class="figure">
  <div class="frame img--cover">
    <img src="https://picsum.photos/1200/700" alt="Cover"/>
  </div>
  <div class="caption">
    Didascalia a lato con <code>.figure</code>, cornice con <code>.frame</code>, fill con <code>.img--cover</code>.
  </div>
</div>

---

<!-- Comparison (pros/cons) -->
# Confronto
<div class="compare">
  <div class="pros">
    <h3>Pro</h3>
    <ul class="bullets--check">
      <li>Prestazioni</li><li>Scalabilità</li>
    </ul>
  </div>
  <div class="cons">
    <h3>Contro</h3>
    <ul class="bullets--dash">
      <li>Costo</li><li>Complessità</li>
    </ul>
  </div>
</div>

---

<!-- Timeline -->
# Timeline
<ul class="timeline">
  <li class="timeline__item">
    <div class="muted">Q1</div>
    <div><span class="timeline__dot"></span>Dataset & baseline</div>
  </li>
  <li class="timeline__item">
    <div class="muted">Q2</div>
    <div><span class="timeline__dot"></span>Tuning & MLOps</div>
  </li>
  <li class="timeline__item">
    <div class="muted">Q3</div>
    <div><span class="timeline__dot"></span>Deploy & Monitor</div>
  </li>
</ul>

---

<!-- Steps (numbered) -->
# Steps numerati
<ol class="steps">
  <li>Definisci obiettivi</li>
  <li>Prepara i dati</li>
  <li>Allena e valuta</li>
  <li>Rilascia e monitora</li>
</ol>

---

<!-- Checklist (with is-done) -->
# Checklist
<ul class="checklist">
  <li class="is-done">Baseline addestrata</li>
  <li>Feature engineering</li>
  <li class="is-done">K-fold impostato</li>
  <li>Hyper-tuning</li>
</ul>

---

<!-- Quote -->
# Citazione
<div class="quote">
  “La semplicità è la sofisticazione suprema.”
  <cite>Leonardo da Vinci</cite>
</div>

---

<!-- Tables -->
# Tabella
<table>
  <thead>
    <tr><th>Modello</th><th>F1</th><th>ROC-AUC</th></tr>
  </thead>
  <tbody>
    <tr><td>Baseline</td><td>0.72</td><td>0.80</td></tr>
    <tr><td>Tuned</td><td>0.81</td><td>0.88</td></tr>
  </tbody>
</table>

---

<!-- Code -->
# Codice (pre/code)
```python
def f1_score(y_true, y_pred):
    # placeholder di esempio
    return 0.81
