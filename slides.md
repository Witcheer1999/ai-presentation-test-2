---
marp: true
theme: brand-pro
paginate: true
---

<!-- Cover -->
<!-- class: lead center-y -->
# Machine Learning vs Deep Learning
## Differenze fondamentali, implicazioni e use case
<span class="badge">AI · Workshop</span>

---

<!-- Introduzione -->
# Introduzione
## Perché confrontarli?
<div class="corpus">
- Entrambi sono approcci **basati sui dati** per costruire modelli predittivi.  
- Il <span class="hl">Machine Learning (ML)</span> è l’insieme più ampio.  
- Il <span class="accent">Deep Learning (DL)</span> è un sottoinsieme del ML, con maggiore complessità e capacità.  
- Capire le differenze è essenziale per **scegliere l’approccio corretto**.
</div>

---

<!-- Differenze concettuali -->
# Differenze concettuali
## Come apprendono
<div class="split">
  <div class="card">
    <h3>Machine Learning</h3>
    <ul class="bullets--tight">
      <li>Richiede <span class="hl">feature engineering</span> manuale</li>
      <li>Algoritmi relativamente semplici (es. alberi, SVM, regressione)</li>
      <li>Capace di apprendere da dataset limitati</li>
      <li>Interpretabilità elevata</li>
    </ul>
  </div>
  <div class="card card--tint-mag">
    <h3>Deep Learning</h3>
    <ul class="bullets--tight">
      <li>Apprende feature in modo <span class="accent">automatico</span></li>
      <li>Architetture complesse (reti neurali profonde)</li>
      <li>Richiede grandi quantità di dati e potenza computazionale</li>
      <li>Interpretabilità ridotta, ma prestazioni superiori</li>
    </ul>
  </div>
</div>

---

<!-- Pipeline a confronto -->
# Pipeline a confronto
## ML vs DL
<div class="grid-2x2">
  <div class="card">
    <h3>ML: Processo classico</h3>
    <ul class="bullets--dash">
      <li>Raccolta dati</li>
      <li>Feature engineering manuale</li>
      <li>Scelta modello + training</li>
      <li>Valutazione e deploy</li>
    </ul>
  </div>
  <div class="card card--tint-blue">
    <h3>DL: Processo end-to-end</h3>
    <ul class="bullets--dash">
      <li>Raccolta dati (molti!)</li>
      <li>Pre-processing minimo</li>
      <li>Training profondo e automatico</li>
      <li>Feature extraction integrata nel modello</li>
    </ul>
  </div>
</div>

---

<!-- Tabella riassuntiva -->
# Confronto sintetico
<table>
  <thead>
    <tr><th>Caratteristica</th><th>Machine Learning</th><th>Deep Learning</th></tr>
  </thead>
  <tbody>
    <tr><td>Feature</td><td>Manuali</td><td>Automatiche</td></tr>
    <tr><td>Dati richiesti</td><td>Pochi / medi</td><td>Grandi volumi</td></tr>
    <tr><td>Hardware</td><td>CPU sufficiente</td><td>GPU/TPU consigliate</td></tr>
    <tr><td>Interpretabilità</td><td>Alta</td><td>Bassa</td></tr>
    <tr><td>Prestazioni</td><td>Buone</td><td>Molto alte</td></tr>
  </tbody>
</table>

---

<!-- Applicazioni pratiche -->
# Use case reali
<div class="cols-3">
  <div class="feature">
    <h3>Machine Learning</h3>
    <ul class="bullets--tight">
      <li>Previsioni finanziarie</li>
      <li>Credit scoring</li>
      <li>Raccomandazioni base</li>
    </ul>
  </div>
  <div class="feature">
    <h3>Deep Learning</h3>
    <ul class="bullets--tight">
      <li>Computer vision</li>
      <li>Riconoscimento vocale</li>
      <li>LLM & NLP avanzato</li>
    </ul>
  </div>
  <div class="feature">
    <h3>Ibridi</h3>
    <ul class="bullets--tight">
      <li>Time series con reti + regressione</li>
      <li>Pipeline ML + embeddings DL</li>
      <li>Classificatori misti</li>
    </ul>
  </div>
</div>

---

<!-- Quando scegliere cosa -->
# Quando usare quale approccio
## Scelta strategica
<div class="compare">
  <div class="pros">
    <h3>Machine Learning</h3>
    <ul class="bullets--check">
      <li>Dati limitati</li>
      <li>Necessità di spiegabilità</li>
      <li>Tempi di sviluppo rapidi</li>
    </ul>
  </div>
  <div class="pros">
    <h3>Deep Learning</h3>
    <ul class="bullets--check">
      <li>Dati abbondanti e non strutturati</li>
      <li>Necessità di alte prestazioni</li>
      <li>Compiti complessi (immagini, linguaggio, audio)</li>
    </ul>
  </div>
</div>

---

<!-- Citazione -->
# Citazione
<div class="quote">
  “Il Deep Learning è come un razzo: richiede carburante (dati) e potenza (hardware), ma può portarti molto più lontano.”
  <cite>Andrew Ng</cite>
</div>

---

<!-- Recap -->
<!-- class: slide--recap -->
# Recap & Takeaways
<div class="recap">
  <div class="recap__card recap__card--tint">
    <h3 class="recap__title">Abbiamo visto</h3>
    <ul class="recap__list">
      <li>ML e DL sono approcci complementari</li>
      <li>DL automatizza la feature extraction</li>
      <li>ML resta efficace dove dati e risorse sono limitati</li>
    </ul>
  </div>
  <div class="recap__card">
    <h3 class="recap__title">Key takeaways</h3>
    <ul class="recap__list bullets--big">
      <li><span class="accent">ML ≠ DL</span>: è un sottoinsieme più potente ma più oneroso</li>
      <li>La scelta dipende da <span class="hl">dati, risorse e obiettivi</span></li>
      <li>Spesso la soluzione migliore è un <span class="accent">approccio ibrido</span></li>
    </ul>
  </div>
</div>
