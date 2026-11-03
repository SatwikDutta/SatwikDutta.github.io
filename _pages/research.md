---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<style>
.research-page {
  --research-ink: #182431;
  --research-muted: #52616b;
  --research-accent: #086f72;
  --research-accent-dark: #07575a;
  --research-warm: #a94e2d;
  --research-line: #d8e1e2;
  --research-paper: #f5f8f8;
  color: var(--research-ink);
}

.research-page * {
  box-sizing: border-box;
}

.research-intro {
  max-width: 50rem;
  margin: 0 0 2rem;
  padding: 1.35rem 1.5rem;
  border-left: 4px solid var(--research-accent);
  background: linear-gradient(110deg, #edf6f5 0%, #f8faf9 100%);
}

.research-intro__eyebrow,
.research-theme__eyebrow {
  margin: 0 0 0.35rem;
  color: var(--research-accent-dark);
  font-size: 0.74rem;
  font-weight: 700;
  letter-spacing: 0.12em;
  text-transform: uppercase;
}

.research-intro__statement {
  margin: 0;
  font-size: clamp(1.05rem, 2vw, 1.35rem);
  line-height: 1.55;
}

.research-nav {
  display: grid;
  grid-template-columns: repeat(4, minmax(0, 1fr));
  gap: 0.65rem;
  margin: 0 0 2.4rem;
}

.research-nav a {
  display: flex;
  min-height: 4.4rem;
  padding: 0.8rem;
  border: 1px solid var(--research-line);
  border-radius: 0.35rem;
  color: var(--research-ink);
  font-size: 0.82rem;
  font-weight: 650;
  line-height: 1.35;
  text-decoration: none;
  background: #fff;
}

.research-nav a:hover,
.research-nav a:focus {
  border-color: var(--research-accent);
  color: var(--research-accent-dark);
}

.research-nav__number {
  margin-right: 0.5rem;
  color: var(--research-accent);
  font-variant-numeric: tabular-nums;
}

.research-theme {
  margin: 0 0 3.4rem;
  scroll-margin-top: 5rem;
}

.research-theme__header {
  display: grid;
  grid-template-columns: 3.2rem minmax(0, 1fr);
  gap: 0.9rem;
  align-items: start;
  margin-bottom: 1rem;
}

.research-theme__number {
  display: grid;
  place-items: center;
  width: 3.2rem;
  height: 3.2rem;
  border: 1px solid var(--research-accent);
  border-radius: 50%;
  color: var(--research-accent-dark);
  font-size: 0.82rem;
  font-weight: 700;
}

.research-theme h2 {
  margin: 0;
  color: var(--research-ink);
  font-size: clamp(1.35rem, 3vw, 1.85rem);
  line-height: 1.2;
}

.research-theme__lead {
  margin: 0 0 1rem 4.1rem;
  color: var(--research-muted);
  font-size: 1rem;
  line-height: 1.65;
}

.research-evidence {
  display: flex;
  flex-wrap: wrap;
  gap: 0.55rem;
  margin: 0 0 1.25rem 4.1rem;
}

.research-evidence span {
  padding: 0.38rem 0.65rem;
  border: 1px solid var(--research-line);
  border-radius: 999px;
  color: #34454f;
  font-size: 0.76rem;
  font-weight: 650;
  background: #fff;
}

.research-figure {
  margin: 1.25rem 0 1rem;
  border: 1px solid var(--research-line);
  border-radius: 0.45rem;
  overflow: hidden;
  background: #fff;
  box-shadow: 0 12px 30px rgba(30, 54, 63, 0.08);
}

.research-figure img {
  display: block;
  width: 100%;
  height: auto;
}

.research-figure--compact img {
  width: min(100%, 47rem);
  margin: 0 auto;
}

.research-figure figcaption {
  padding: 0.7rem 0.9rem;
  border-top: 1px solid var(--research-line);
  color: var(--research-muted);
  font-size: 0.73rem;
  line-height: 1.45;
  background: var(--research-paper);
}

.research-figure figcaption a,
.research-links a,
.earlier-card a {
  color: var(--research-accent-dark);
  font-weight: 700;
}

.research-links {
  display: flex;
  flex-wrap: wrap;
  gap: 0.65rem;
  margin: 1rem 0 0;
}

.research-links a {
  display: inline-flex;
  align-items: center;
  padding: 0.45rem 0.7rem;
  border-bottom: 2px solid var(--research-accent);
  text-decoration: none;
  background: #eef6f5;
}

.research-links a:hover,
.research-links a:focus {
  color: #fff;
  background: var(--research-accent-dark);
}

.research-leaderboard {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 0.75rem;
  margin: 1.2rem 0;
}

.research-leaderboard div {
  padding: 1rem;
  border-top: 3px solid var(--research-accent);
  background: var(--research-paper);
}

.research-leaderboard strong {
  display: block;
  margin-bottom: 0.25rem;
  color: var(--research-ink);
  font-size: 0.88rem;
}

.research-leaderboard span {
  color: var(--research-muted);
  font-size: 0.78rem;
  line-height: 1.45;
}

.earlier-research {
  margin-top: 3.8rem;
  padding-top: 2rem;
  border-top: 1px solid var(--research-line);
  scroll-margin-top: 5rem;
}

.earlier-research h2 {
  margin: 0 0 0.4rem;
  color: var(--research-ink);
}

.earlier-research > p {
  margin: 0 0 1.2rem;
  color: var(--research-muted);
}

.earlier-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 0.8rem;
}

.earlier-card {
  padding: 1rem;
  border: 1px solid var(--research-line);
  border-radius: 0.35rem;
  background: #fff;
}

.earlier-card h3 {
  margin: 0 0 0.35rem;
  color: var(--research-ink);
  font-size: 0.98rem;
}

.earlier-card p {
  margin: 0;
  color: var(--research-muted);
  font-size: 0.83rem;
  line-height: 1.5;
}

.research-footer-link {
  margin: 1.7rem 0 0;
  text-align: right;
}

.research-footer-link a {
  color: var(--research-warm);
  font-weight: 700;
}

@media (max-width: 700px) {
  .research-nav,
  .research-leaderboard,
  .earlier-grid {
    grid-template-columns: 1fr;
  }

  .research-nav a {
    min-height: auto;
  }

  .research-theme__header {
    grid-template-columns: 2.65rem minmax(0, 1fr);
    gap: 0.7rem;
  }

  .research-theme__number {
    width: 2.65rem;
    height: 2.65rem;
  }

  .research-theme__lead,
  .research-evidence {
    margin-left: 0;
  }
}
</style>

<div class="research-page">
  <section class="research-intro" aria-labelledby="research-statement">
    <p class="research-intro__eyebrow">Child-centered speech and voice AI</p>
    <p class="research-intro__statement" id="research-statement">I develop speech technologies that work in the places children learn—classrooms, homes, museums, and tutoring environments—while treating privacy, efficiency, and equitable evaluation as core system requirements.</p>
  </section>

  <nav class="research-nav" aria-label="Research themes">
    <a href="#private-efficient-asr"><span class="research-nav__number">01</span>Privacy-preserving and efficient child ASR</a>
    <a href="#child-adult-interactions"><span class="research-nav__number">02</span>Measuring child–adult interactions</a>
    <a href="#responsible-data-evaluation"><span class="research-nav__number">03</span>Responsible data and evaluation</a>
    <a href="#voice-privacy-policy"><span class="research-nav__number">04</span>Voice privacy and AI policy</a>
  </nav>

  <article class="research-theme" id="private-efficient-asr">
    <header class="research-theme__header">
      <span class="research-theme__number">01</span>
      <div>
        <p class="research-theme__eyebrow">Models and deployment</p>
        <h2>Privacy-preserving and efficient child ASR</h2>
      </div>
    </header>
    <p class="research-theme__lead">I investigate how child-speech recognition can reduce dependence on cloud inference and limit exposure of raw voice data. This work combines discrete speech units with compact, compressed Whisper models that can run locally on low-cost edge hardware.</p>
    <div class="research-evidence" aria-label="Selected results">
      <span>15.7% WER on MyST with discrete ASR</span>
      <span>Nearly 3× faster training</span>
      <span>On-device Raspberry Pi inference</span>
    </div>
    <figure class="research-figure research-figure--compact">
      <img src="/images/research/on-device-child-asr-raspberry-pi.png" alt="Raspberry Pi 5, cooling fan, microphone, and enclosure used to evaluate lightweight child automatic speech recognition on an edge device" loading="lazy">
      <figcaption>Raspberry Pi 5 deployment setup. Figure from <a href="https://www.isca-archive.org/wocci_2025/dutta25_wocci.html" target="_blank" rel="noopener noreferrer">Dutta, Chandupatla &amp; Hansen, WOCCI 2025</a>.</figcaption>
    </figure>
    <div class="research-links" aria-label="Publications and code">
      <a href="https://www.sciencedirect.com/science/article/abs/pii/S1071581925000175" target="_blank" rel="noopener noreferrer">IJHCS 2025 · Discrete speech units</a>
      <a href="https://www.isca-archive.org/wocci_2025/dutta25_wocci.html" target="_blank" rel="noopener noreferrer">WOCCI 2025 · Lightweight Whisper</a>
      <a href="https://github.com/SatwikDutta/LiteChildASR" target="_blank" rel="noopener noreferrer">Code and model recipes</a>
    </div>
  </article>

  <article class="research-theme" id="child-adult-interactions">
    <header class="research-theme__header">
      <span class="research-theme__number">02</span>
      <div>
        <p class="research-theme__eyebrow">Speech in the wild</p>
        <h2>Measuring child–adult interactions</h2>
      </div>
    </header>
    <p class="research-theme__lead">Long, naturalistic recordings become useful only when they can be converted into interpretable measures. I build speech-recognition and speaker-diarization pipelines for classrooms and informal learning environments, including science museums, to estimate conversational turns, spoken initiations and responses, individual talk time, and location-aware engagement.</p>
    <div class="research-evidence" aria-label="Interaction measures">
      <span>Who spoke when?</span>
      <span>Conversational turns</span>
      <span>Initiations and responses</span>
      <span>Individual talk time</span>
    </div>
    <figure class="research-figure">
      <img src="/images/research/museum-diarization-pipeline.png" alt="Science City museum layout, parent and child wearing LENA audio recorders, and a speaker diarization pipeline that produces engagement metrics" loading="lazy">
      <figcaption>Field setup and diarization pipeline for measuring parent–child engagement in a science museum. Figure from <a href="https://www.isca-archive.org/wocci_2025/dutta25b_wocci.html" target="_blank" rel="noopener noreferrer">Dutta et al., WOCCI 2025</a>.</figcaption>
    </figure>
    <div class="research-links">
      <a href="https://www.isca-archive.org/wocci_2025/dutta25b_wocci.html" target="_blank" rel="noopener noreferrer">WOCCI 2025 · Little Voices, Big Discoveries</a>
      <a href="https://www.isca-archive.org/interspeech_2022/dutta22_interspeech.html" target="_blank" rel="noopener noreferrer">INTERSPEECH 2022 · Naturalistic preschool ASR</a>
    </div>
  </article>

  <article class="research-theme" id="responsible-data-evaluation">
    <header class="research-theme__header">
      <span class="research-theme__number">03</span>
      <div>
        <p class="research-theme__eyebrow">Corpora, benchmarks, and public infrastructure</p>
        <h2>Responsible child-speech data and evaluation</h2>
      </div>
    </header>
    <p class="research-theme__lead">Responsible child-speech AI starts before model training. My work addresses field data collection, corpus curation, transcription quality, and evaluation that goes beyond a single aggregate word error rate. The goal is to make performance differences visible across age groups, regional dialects, demographic cohorts, and clinical speech differences.</p>
    <div class="research-leaderboard" aria-label="Evaluation priorities">
      <div><strong>Document the data</strong><span>Recording context, speaker roles, transcription quality, and collection conditions.</span></div>
      <div><strong>Disaggregate results</strong><span>Report aggregate and subgroup metrics rather than allowing one score to hide disparities.</span></div>
      <div><strong>Release public infrastructure</strong><span>Open baselines, reproducible recipes, and education-specific leaderboards.</span></div>
    </div>
    <figure class="research-figure">
      <img src="/images/research/preschool-interaction-data-collection.png" alt="Diagram of a preschool classroom, children and adults moving through activity areas over time, LENA audio recorders, a location tracker, and speaker-annotated audio" loading="lazy">
      <figcaption>Naturalistic preschool data collection combines wearable audio, location, activity context, and speaker annotation. Figure from <a href="https://www.isca-archive.org/interspeech_2022/dutta22_interspeech.html" target="_blank" rel="noopener noreferrer">Dutta et al., INTERSPEECH 2022</a>.</figcaption>
    </figure>
    <p class="research-theme__lead">At Cornell, this direction continues through the <a href="https://k12-ai-infrastructure.org/cornell-university/" target="_blank" rel="noopener noreferrer">Open Leaderboards for Benchmarking Automated Speech Recognition in Educational Contexts</a>, which is developing child-optimized baselines and subgroup-disaggregated evaluation for K–12 tutoring audio.</p>
  </article>

  <article class="research-theme" id="voice-privacy-policy">
    <header class="research-theme__header">
      <span class="research-theme__number">04</span>
      <div>
        <p class="research-theme__eyebrow">Technology, law, and governance</p>
        <h2>Voice privacy and AI policy</h2>
      </div>
    </header>
    <p class="research-theme__lead">Technical safeguards operate within a changing policy environment. I study how U.S. federal and state privacy laws define voice recordings and voiceprints, what additional protections apply to children, and how synthetic data can support responsible AI development without treating regulation as an afterthought.</p>
    <div class="research-evidence" aria-label="Policy areas">
      <span>Federal and state privacy law</span>
      <span>Children’s data protection</span>
      <span>Voice as biometric data</span>
      <span>Synthetic data governance</span>
    </div>
    <figure class="research-figure">
      <img src="/images/research/us-voice-privacy-landscape.png" alt="Six maps comparing U.S. state privacy laws, definitions of voice as biometric data, protections for children's personal data, COPPA alignment, and protected age ranges" loading="lazy">
      <figcaption>U.S. state voice-privacy and children’s-data protections as analyzed in the paper; legislative data are current to June 24, 2024. Figure from <a href="https://www.isca-archive.org/syndata4genai_2024/dutta24_syndata4genai.html" target="_blank" rel="noopener noreferrer">Dutta &amp; Hansen, SynData4GenAI 2024</a>.</figcaption>
    </figure>
    <div class="research-links">
      <a href="https://www.isca-archive.org/syndata4genai_2024/dutta24_syndata4genai.html" target="_blank" rel="noopener noreferrer">ISCA 2024 · U.S. voice-privacy landscape</a>
      <a href="https://fas.org/publication/childrens-online-voice-privacy/" target="_blank" rel="noopener noreferrer">FAS Policy Brief · Strengthening Children’s Online Voice Privacy</a>
    </div>
  </article>

  <section class="earlier-research" id="earlier-research">
    <p class="research-theme__eyebrow">Selected foundations</p>
    <h2>Earlier Research</h2>
    <p>Earlier projects established the signal-processing, clinical-speech, and multimodal foundations for my current work.</p>
    <div class="earlier-grid">
      <article class="earlier-card">
        <h3>NeuroVAD</h3>
        <p>Real-time speech-activity detection from non-invasive magnetoencephalography signals using recurrent neural networks. <a href="https://doi.org/10.3390/s20082248" target="_blank" rel="noopener noreferrer">Journal article</a></p>
      </article>
      <article class="earlier-card">
        <h3>Prompted-speech activity detection</h3>
        <p>Automatic segmentation of preschool speech for scalable speech-sound-disorder screening and assessment. <a href="https://speakeasy.utdallas.edu/" target="_blank" rel="noopener noreferrer">SpeakEasy project</a></p>
      </article>
      <article class="earlier-card">
        <h3>Articulatory kinematics</h3>
        <p>Tongue and lip motion patterns as sensitive markers of speech-motor change in amyotrophic lateral sclerosis.</p>
      </article>
      <article class="earlier-card">
        <h3>Silent speech and laryngectomy</h3>
        <p>Motion-based analysis and classification of voiced, silent, and alaryngeal speech. <a href="/files/2020_MotorSpeech.pdf" target="_blank" rel="noopener noreferrer">Research poster</a></p>
      </article>
    </div>
  </section>

  <p class="research-footer-link"><a href="https://scholar.google.com/citations?hl=en&amp;authuser=1&amp;user=sZkQ4Y0AAAAJ" target="_blank" rel="noopener noreferrer">View all publications on Google Scholar →</a></p>
</div>
