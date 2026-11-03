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

.research-theme__eyebrow {
  margin: 0 0 0.35rem;
  color: var(--research-accent-dark);
  font-size: 0.74rem;
  font-weight: 700;
  letter-spacing: 0.12em;
  text-transform: uppercase;
}

.research-intro__title {
  margin: 0 0 0.4rem;
  color: var(--research-ink);
  font-size: clamp(1.35rem, 3vw, 1.85rem);
  line-height: 1.2;
}

.research-intro__statement {
  margin: 0;
  font-size: clamp(1.05rem, 2vw, 1.35rem);
  line-height: 1.55;
}

.research-nav {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
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
.publication-card a,
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

.research-publications {
  margin-top: 1.35rem;
  padding-top: 1.1rem;
  border-top: 1px solid var(--research-line);
}

.research-publications > h3 {
  margin: 0 0 0.7rem;
  color: var(--research-accent-dark);
  font-size: 0.76rem;
  font-weight: 750;
  letter-spacing: 0.1em;
  text-transform: uppercase;
}

.publication-list {
  display: grid;
  gap: 0.75rem;
}

.publication-card {
  padding: 0.9rem 1rem;
  border: 1px solid var(--research-line);
  border-radius: 0.4rem;
  background: #fff;
}

.publication-card h4 {
  margin: 0;
  font-size: 0.96rem;
  line-height: 1.4;
}

.publication-card h4 a {
  text-decoration: none;
}

.publication-card h4 a:hover,
.publication-card h4 a:focus {
  text-decoration: underline;
}

.publication-card__meta {
  margin: 0.25rem 0 0;
  color: var(--research-muted);
  font-size: 0.72rem;
  font-weight: 650;
  letter-spacing: 0.035em;
}

.publication-card__contribution {
  margin: 0.65rem 0 0;
  color: #34454f;
  font-size: 0.84rem;
  line-height: 1.55;
}

.publication-card__contribution strong {
  color: var(--research-warm);
}

.publication-card details {
  margin-top: 0.65rem;
  padding-top: 0.55rem;
  border-top: 1px solid #e7eded;
}

.publication-card summary {
  width: max-content;
  color: var(--research-accent-dark);
  font-size: 0.78rem;
  font-weight: 700;
  cursor: pointer;
}

.publication-card details p {
  margin: 0.55rem 0 0;
  color: var(--research-muted);
  font-size: 0.8rem;
  line-height: 1.55;
}

.research-project-note {
  margin: 1rem 0;
  padding: 0.85rem 1rem;
  border-left: 3px solid var(--research-warm);
  color: var(--research-muted);
  font-size: 0.86rem;
  line-height: 1.55;
  background: #fbf7f4;
}

.research-project-note strong {
  color: var(--research-ink);
}

.research-project-note a {
  color: var(--research-accent-dark);
  font-weight: 700;
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
  .research-page {
    width: calc(100vw - 1.25rem);
    max-width: none;
  }

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

  .research-theme,
  .research-theme__header > div,
  .publication-card {
    min-width: 0;
  }

  .research-theme h2,
  .research-theme__lead,
  .publication-card h4 {
    overflow-wrap: anywhere;
  }

  .research-figure {
    max-width: 100%;
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
  <section class="research-intro" aria-labelledby="research-heading">
    <h2 class="research-intro__title" id="research-heading">Child-centered speech and voice AI</h2>
    <p class="research-intro__statement">I develop speech technologies that work in the places children learn—classrooms, homes, museums, and tutoring environments—while treating privacy, efficiency, and equitable evaluation as core system requirements.</p>
  </section>

  <nav class="research-nav" aria-label="Research themes">
    <a href="#child-asr"><span class="research-nav__number">01</span>Automatic Speech Recognition for Children</a>
    <a href="#private-efficient-asr"><span class="research-nav__number">02</span>Privacy-preserving and efficient child ASR</a>
    <a href="#child-adult-interactions"><span class="research-nav__number">03</span>Measuring child–adult interactions</a>
    <a href="#responsible-data-evaluation"><span class="research-nav__number">04</span>Responsible data and evaluation</a>
    <a href="#voice-privacy-policy"><span class="research-nav__number">05</span>Voice privacy and AI policy</a>
    <a href="#downstream-educational-applications"><span class="research-nav__number">06</span>Downstream Educational Applications</a>
  </nav>

  <article class="research-theme" id="child-asr">
    <header class="research-theme__header">
      <span class="research-theme__number">01</span>
      <div>
        <p class="research-theme__eyebrow">Core speech technology</p>
        <h2>Automatic Speech Recognition for Children</h2>
      </div>
    </header>
    <p class="research-theme__lead">My research builds ASR for preschool and school-aged children in naturalistic educational environments. Across three studies, it establishes robust hybrid baselines for spontaneous classroom speech, couples recognition with classroom location to recover activity-specific language measures, and introduces discrete speech units that reduce privacy and compute costs.</p>
    <figure class="research-figure">
      <img src="/images/research/preschool-interaction-data-collection.png" alt="Preschool classroom map, time-varying child and adult locations, speaker annotations, and wearable LENA and location-tracking devices" loading="lazy">
      <figcaption>Naturalistic preschool data collection combines wearable audio, speaker annotation, and real-time location. Figure from <a href="https://www.isca-archive.org/interspeech_2022/dutta22_interspeech.html" target="_blank" rel="noopener noreferrer">Dutta et al., INTERSPEECH 2022</a>.</figcaption>
    </figure>
    <section class="research-publications" aria-labelledby="child-asr-publications">
      <h3 id="child-asr-publications">Selected publications</h3>
      <div class="publication-list">
        <article class="publication-card">
          <h4><a href="https://www.isca-archive.org/interspeech_2022/dutta22_interspeech.html" target="_blank" rel="noopener noreferrer">Challenges remain in Building ASR for Spontaneous Preschool Children Speech in Naturalistic Educational Environments</a></h4>
          <p class="publication-card__meta">INTERSPEECH 2022</p>
          <p class="publication-card__contribution"><strong>Contribution.</strong> Establishes hybrid-ASR baselines for spontaneous classroom speech from 3–5-year-olds with and without developmental delays, and shows that naturalistic child–adult interaction text improves language modeling.</p>
          <details><summary>Abstract</summary><p>The study evaluates factorized TDNN acoustic models and n-gram and recurrent language models for low-resource preschool classroom speech. Comparisons with out-of-domain child corpora show that age, developing articulation, non-speech events, and recording context remain central challenges.</p></details>
        </article>
        <article class="publication-card">
          <h4><a href="https://aclanthology.org/2022.bea-1.13/" target="_blank" rel="noopener noreferrer">Activity focused Speech Recognition of Preschool Children in Early Childhood Classrooms</a></h4>
          <p class="publication-card__meta">BEA 2022 · Association for Computational Linguistics</p>
          <p class="publication-card__contribution"><strong>Contribution.</strong> Fuses conversational speech with real-time classroom location and demonstrates recognition of spoken words, WH-words, and verbs within specific activity zones.</p>
          <details><summary>Abstract</summary><p>A hybrid ASR system with an effective word error rate of about 40% is paired with location sensing in naturalistic preschool classrooms. The resulting activity-level measures illustrate how speech technology could support classroom assessment without relying entirely on direct observation.</p></details>
        </article>
        <article class="publication-card">
          <h4><a href="https://www.sciencedirect.com/science/article/abs/pii/S1071581925000175" target="_blank" rel="noopener noreferrer">Exploring discrete speech units for privacy-preserving and efficient speech recognition for school-aged and preschool children</a></h4>
          <p class="publication-card__meta">International Journal of Human-Computer Studies · 2025</p>
          <p class="publication-card__contribution"><strong>Contribution.</strong> Achieves 15.7% WER on MyST using discrete speech units while matching much larger end-to-end systems more closely in performance than in model size or training cost.</p>
          <details><summary>Abstract</summary><p>The paper tests whether discrete representations can preserve linguistic information needed for ASR while limiting speaker-specific information and waveform reconstruction. It compares discrete and end-to-end systems across multiple child-speech corpora and demonstrates activity-word recognition in preschool teacher–child interactions.</p></details>
        </article>
      </div>
    </section>
  </article>

  <article class="research-theme" id="private-efficient-asr">
    <header class="research-theme__header">
      <span class="research-theme__number">02</span>
      <div>
        <p class="research-theme__eyebrow">Models and deployment</p>
        <h2>Privacy-preserving and efficient child ASR</h2>
      </div>
    </header>
    <p class="research-theme__lead">My research pairs privacy-preserving representations with models small enough for local inference. The discrete-unit study reaches 15.7% WER with a substantially smaller, faster system; the edge-ASR study compresses Whisper for real-time Raspberry Pi deployment while reducing encoder size and computation.</p>
    <div class="research-evidence" aria-label="Selected results">
      <span>15.7% WER on MyST with discrete ASR</span>
      <span>Nearly 3× faster training</span>
      <span>On-device Raspberry Pi inference</span>
    </div>
    <figure class="research-figure research-figure--compact">
      <img src="/images/research/on-device-child-asr-raspberry-pi.png" alt="Raspberry Pi 5, cooling fan, microphone, and enclosure used to evaluate lightweight child automatic speech recognition on an edge device" loading="lazy">
      <figcaption>Raspberry Pi 5 deployment setup. Figure from <a href="https://www.isca-archive.org/wocci_2025/dutta25_wocci.html" target="_blank" rel="noopener noreferrer">Dutta, Chandupatla &amp; Hansen, WOCCI 2025</a>.</figcaption>
    </figure>
    <div class="research-links" aria-label="Code and model resources">
      <a href="https://github.com/SatwikDutta/LiteChildASR" target="_blank" rel="noopener noreferrer">Code and model recipes</a>
    </div>
    <section class="research-publications" aria-labelledby="private-efficient-publications">
      <h3 id="private-efficient-publications">Selected publications</h3>
      <div class="publication-list">
        <article class="publication-card">
          <h4><a href="https://www.sciencedirect.com/science/article/abs/pii/S1071581925000175" target="_blank" rel="noopener noreferrer">Exploring discrete speech units for privacy-preserving and efficient speech recognition for school-aged and preschool children</a></h4>
          <p class="publication-card__meta">International Journal of Human-Computer Studies · 2025</p>
          <p class="publication-card__contribution"><strong>Contribution.</strong> Shows that discrete speech units can support competitive child ASR while limiting reliance on raw voice, cutting training time to roughly one-third of a much larger end-to-end baseline.</p>
          <details><summary>Abstract</summary><p>A discrete-unit ASR model reaches 15.7% WER on MyST and is evaluated on additional school-aged and preschool corpora. The study examines privacy, efficiency, cross-corpus generalization, and the recognition of educationally relevant word categories in teacher–child interactions.</p></details>
        </article>
        <article class="publication-card">
          <h4><a href="https://www.isca-archive.org/wocci_2025/dutta25_wocci.html" target="_blank" rel="noopener noreferrer">Adapting Whisper for Lightweight and Efficient Automatic Speech Recognition of Children for On-device Edge Applications</a></h4>
          <p class="publication-card__meta">WOCCI 2025</p>
          <p class="publication-card__contribution"><strong>Contribution.</strong> Compresses and deploys a child-adapted Whisper model on Raspberry Pi, reducing encoder size and computation while retaining real-time inference.</p>
          <details><summary>Abstract</summary><p>The study fine-tunes Whisper tiny.en on MyST, evaluates filtering strategies, and applies low-rank encoder compression. It reports 15.9% WER overall, 11.8% on filtered speech, 1.26× faster GPU inference, roughly 2 fewer GFLOPS on Raspberry Pi, and real-time factors between 0.23 and 0.41.</p></details>
        </article>
      </div>
    </section>
  </article>

  <article class="research-theme" id="child-adult-interactions">
    <header class="research-theme__header">
      <span class="research-theme__number">03</span>
      <div>
        <p class="research-theme__eyebrow">Speech in the wild</p>
        <h2>Measuring child–adult interactions</h2>
      </div>
    </header>
    <p class="research-theme__lead">My research converts long, naturalistic recordings into interpretable measures of interaction. The museum study turns diarization into conversational-turn, initiation, response, and talk-time measures; the preschool ASR study establishes the transcription foundation for noisy classrooms; and the bilingual study jointly identifies speaker role and language in adult–toddler speech.</p>
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
    <section class="research-publications" aria-labelledby="interaction-publications">
      <h3 id="interaction-publications">Selected publications</h3>
      <div class="publication-list">
        <article class="publication-card">
          <h4><a href="https://www.isca-archive.org/wocci_2025/dutta25b_wocci.html" target="_blank" rel="noopener noreferrer">Little Voices, Big Discoveries — Using Speaker Diarization to Assess Parent-Child Engagement within a Science Museum Scenario</a></h4>
          <p class="publication-card__meta">WOCCI 2025</p>
          <p class="publication-card__contribution"><strong>Contribution.</strong> Introduces an unobtrusive diarization pipeline for converting family museum audio into conversational turns, initiations and responses, and individual talk time.</p>
          <details><summary>Abstract</summary><p>The proof-of-concept combines museum-staff perspectives with parent–child audio collected using LENA recorders in a noisy informal-learning environment. System performance is evaluated with diarization error rate and with engagement measures designed to be meaningful to museum and education stakeholders.</p></details>
        </article>
        <article class="publication-card">
          <h4><a href="https://www.isca-archive.org/interspeech_2022/dutta22_interspeech.html" target="_blank" rel="noopener noreferrer">Challenges remain in Building ASR for Spontaneous Preschool Children Speech in Naturalistic Educational Environments</a></h4>
          <p class="publication-card__meta">INTERSPEECH 2022</p>
          <p class="publication-card__contribution"><strong>Contribution.</strong> Provides the classroom-ASR foundation needed to recover child speech from multi-speaker, activity-rich preschool recordings.</p>
          <details><summary>Abstract</summary><p>The paper benchmarks hybrid acoustic and language models for spontaneous speech from preschool children with and without developmental delays. Results show the value of age- and interaction-matched text while documenting persistent errors associated with developing articulation and non-linguistic classroom events.</p></details>
        </article>
        <article class="publication-card">
          <h4><a href="https://www.isca-archive.org/odyssey_2024/dutta24_odyssey.html" target="_blank" rel="noopener noreferrer">Joint Language and Speaker Classification in Naturalistic Bilingual Adult-Toddler Interactions</a></h4>
          <p class="publication-card__meta">Odyssey 2024</p>
          <p class="publication-card__contribution"><strong>Contribution.</strong> Jointly predicts English or Spanish and adult or child speech using self-supervised representations from naturalistic bilingual interactions.</p>
          <details><summary>Abstract</summary><p>Using the Hoff Corpus at child ages 2½, 3, and 3½ years, the study compares XLSR-53 and HuBERT features in a multitask classifier. A trainable combination of representations across Transformer layers improves both tasks, particularly speaker classification, while child-language identification remains difficult.</p></details>
        </article>
      </div>
    </section>
  </article>

  <article class="research-theme" id="responsible-data-evaluation">
    <header class="research-theme__header">
      <span class="research-theme__number">04</span>
      <div>
        <p class="research-theme__eyebrow">Corpora, benchmarks, and public infrastructure</p>
        <h2>Responsible child-speech data and evaluation</h2>
      </div>
    </header>
    <p class="research-theme__lead">Responsible child-speech AI starts before model training. The corpus-practices paper organizes collection around who is recorded, what speech is needed, when and where recording occurs, and how trust, consent, quality control, triage, and annotation are handled. The Cornell leaderboard project carries those principles into subgroup-disaggregated ASR evaluation for K–12 tutoring audio.</p>
    <div class="research-leaderboard" aria-label="Evaluation priorities">
      <div><strong>Document the data</strong><span>Recording context, speaker roles, transcription quality, and collection conditions.</span></div>
      <div><strong>Disaggregate results</strong><span>Report aggregate and subgroup metrics rather than allowing one score to hide disparities.</span></div>
      <div><strong>Release public infrastructure</strong><span>Open baselines, reproducible recipes, and education-specific leaderboards.</span></div>
    </div>
    <figure class="research-figure">
      <img src="/images/research/child-speech-corpus-data-collection.png" alt="Child speech data-collection framework showing where recordings are collected, how they are captured, who participates, and whether speech is scripted or spontaneous" loading="lazy">
      <figcaption>Core design dimensions for child-speech corpus collection: where data are collected, how recordings are captured, who is recorded, and what type of speech is elicited. Related paper: <a href="https://arxiv.org/abs/2507.12870" target="_blank" rel="noopener noreferrer">Hansen, Dutta &amp; Grand, SLaTE 2025</a>.</figcaption>
    </figure>
    <p class="research-project-note"><strong>Current project.</strong> At Cornell, the <a href="https://k12-ai-infrastructure.org/cornell-university/" target="_blank" rel="noopener noreferrer">Open Leaderboards for Benchmarking ASR in Educational Contexts</a> will release child-optimized baselines, reproducible recipes, and aggregate and subgroup metrics across age, dialect, demographic cohort, and clinical speech differences.</p>
    <section class="research-publications" aria-labelledby="responsible-data-publications">
      <h3 id="responsible-data-publications">Selected publication</h3>
      <div class="publication-list">
        <article class="publication-card">
          <h4><a href="https://arxiv.org/abs/2507.12870" target="_blank" rel="noopener noreferrer">Best Practices and Considerations for Child Speech Corpus Collection and Curation in Educational, Clinical, and Forensic Scenarios</a></h4>
          <p class="publication-card__meta">SLaTE 2025</p>
          <p class="publication-card__contribution"><strong>Contribution.</strong> Provides an end-to-end framework for planning child-speech corpora, from study purpose and participant trust through human-subjects review, quality checks, triage, and annotation.</p>
          <details><summary>Abstract</summary><p>The paper addresses the rapid developmental changes and privacy constraints that make technology-ready child-speech data difficult to collect. It structures decisions around who, what, when, and where to record, then offers practical guidance for collaboration, research protocols, corpus quality, and curation across educational, clinical, and forensic settings.</p></details>
        </article>
      </div>
    </section>
  </article>

  <article class="research-theme" id="voice-privacy-policy">
    <header class="research-theme__header">
      <span class="research-theme__number">05</span>
      <div>
        <p class="research-theme__eyebrow">Technology, law, and governance</p>
        <h2>Voice privacy and AI policy</h2>
      </div>
    </header>
    <p class="research-theme__lead">My research connects technical safeguards to law and governance. The legislative review maps how federal and state privacy rules treat voice, children’s data, and synthetic data; the FAS policy brief converts that analysis into concrete COPPA 2.0 recommendations covering audio exceptions, derived audio features, deidentification, and AI-generated avatars.</p>
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
    <section class="research-publications" aria-labelledby="policy-publications">
      <h3 id="policy-publications">Selected publications</h3>
      <div class="publication-list">
        <article class="publication-card">
          <h4><a href="https://www.isca-archive.org/syndata4genai_2024/dutta24_syndata4genai.html" target="_blank" rel="noopener noreferrer">Navigating the United States Legislative Landscape on Voice Privacy: Existing Laws, Proposed Bills, Protection for Children, and Synthetic Data for AI</a></h4>
          <p class="publication-card__meta">SynData4GenAI 2024</p>
          <p class="publication-card__contribution"><strong>Contribution.</strong> Maps enacted and proposed privacy laws across the United States, with specific attention to voice data, protections for children, and emerging rules for synthetic data.</p>
          <details><summary>Abstract</summary><p>The paper reviews federal activity and legislation across all fifty states to show where recordings and voiceprints enter statutory definitions and where additional safeguards apply to children. It also examines how synthetic data is beginning to appear in AI policy as an alternative to sensitive human data.</p></details>
        </article>
        <article class="publication-card">
          <h4><a href="https://fas.org/publication/childrens-online-voice-privacy/" target="_blank" rel="noopener noreferrer">Update COPPA 2.0 to Strengthen Children’s Online Voice Privacy in the AI Era</a></h4>
          <p class="publication-card__meta">Federation of American Scientists · 2024</p>
          <p class="publication-card__contribution"><strong>Contribution.</strong> Proposes targeted COPPA 2.0 language to close gaps around stored audio, extracted audio features, deidentification, and AI-generated representations of children.</p>
          <details><summary>Abstract</summary><p>The policy brief argues that modern voice-AI systems create risks not captured by rules focused only on raw recordings. It recommends narrowing the audio-file exception, deleting derived features with source audio, defining deidentification practices, and treating AI-generated child avatars as protected personal information.</p></details>
        </article>
      </div>
    </section>
  </article>

  <article class="research-theme" id="downstream-educational-applications">
    <header class="research-theme__header">
      <span class="research-theme__number">06</span>
      <div>
        <p class="research-theme__eyebrow">From speech signals to educational measures</p>
        <h2>Downstream Educational Applications</h2>
      </div>
    </header>
    <p class="research-theme__lead">My research translates speech processing into measures for early childhood education and intervention. The ECRQ study automates teacher WH-word counts by location; the ASEE paper defines engagement through turns, topic initiations, and vocabulary complexity; the S4SG study evaluates smartphones as an accessible alternative to LENA; and the ICMI study measures WH-question frequency across Science and Reading zones.</p>
    <figure class="research-figure research-figure--compact">
      <img src="/images/research/wh-word-frequency-by-learning-location.png" alt="Bar chart comparing actual and ASR-predicted adult WH-word counts in preschool Science and Reading zones" loading="lazy">
      <figcaption>Actual and ASR-predicted adult WH-word frequency across Science and Reading activity zones. Figure from <a href="https://doi.org/10.1145/3461615.3485440" target="_blank" rel="noopener noreferrer">Kothalkar et al., ICMI 2021</a>.</figcaption>
    </figure>
    <section class="research-publications" aria-labelledby="applications-publications">
      <h3 id="applications-publications">Selected publications</h3>
      <div class="publication-list">
        <article class="publication-card">
          <h4><a href="https://www.sciencedirect.com/science/article/abs/pii/S0885200623001308" target="_blank" rel="noopener noreferrer">Capturing the quantity and location of adult wh-words in the preschool classroom using a sensing tool system</a></h4>
          <p class="publication-card__meta">Early Childhood Research Quarterly · 2024</p>
          <p class="publication-card__contribution"><strong>Contribution.</strong> Demonstrates that ASR combined with location sensing can automatically quantify teachers’ WH-words within preschool literacy activity areas.</p>
          <details><summary>Abstract</summary><p>This proof-of-concept replaces limited direct observation with automated speech and location measures. The system identifies “what” as the most frequent adult WH-word, reveals changes across collection time points, and supports comparisons of the language exposure experienced by individual children.</p></details>
        </article>
        <article class="publication-card">
          <h4><a href="https://peer.asee.org/39202" target="_blank" rel="noopener noreferrer">Quantifying Engagement in Preschool Classrooms — Conversational Turn-Taking &amp; Topic Initiations</a></h4>
          <p class="publication-card__meta">ASEE Gulf-Southwest 2022</p>
          <p class="publication-card__contribution"><strong>Contribution.</strong> Defines a combined measurement framework for conversational turns, topic initiations, and phonological vocabulary complexity rather than treating any single count as engagement.</p>
          <details><summary>Abstract</summary><p>The study analyzes five adult–child sessions, including children with and without speech or language delays, to relate who initiates a topic, how long exchanges continue, and the complexity of target nouns. Adult initiations tend to elicit more turns, but the results show why turn counts must be interpreted alongside vocabulary measures.</p></details>
        </article>
        <article class="publication-card">
          <h4><a href="https://www.isca-archive.org/s4sg_2022/dutta22_s4sg.html" target="_blank" rel="noopener noreferrer">Can Smartphones be a cost-effective alternative to LENA for Early Childhood Language Intervention?</a></h4>
          <p class="publication-card__meta">Speech for Social Good 2022</p>
          <p class="publication-card__contribution"><strong>Contribution.</strong> Shows, in a small unsupervised home study, that family smartphones can capture audio with signal quality and ASR performance comparable to dedicated LENA recorders.</p>
          <details><summary>Abstract</summary><p>Three families recorded roughly ten hours of parent–child science-book reading with a LENA device and their own smartphone during the COVID-19 pandemic. Comparisons using speech-to-noise ratio and ASR word error rate support smartphones as a promising lower-cost collection option while documenting the study’s limited scale.</p></details>
        </article>
        <article class="publication-card">
          <h4><a href="https://doi.org/10.1145/3461615.3485440" target="_blank" rel="noopener noreferrer">Measuring Frequency of Child-directed WH-Question Words for Alternate Preschool Locations using Speech Recognition and Location Tracking Technologies</a></h4>
          <p class="publication-card__meta">ICMI 2021</p>
          <p class="publication-card__contribution"><strong>Contribution.</strong> Connects adult and child ASR with location tracking to compare actual and predicted WH-question frequencies across preschool Science and Reading areas.</p>
          <details><summary>Abstract</summary><p>Using daylong recordings from 48 classroom sessions, the study trains hybrid and end-to-end ASR systems for naturalistic adult and child speech. It then maps recognized WH-words to learning zones, showing how automated language measures could inform the design of spaces that encourage adult–child engagement.</p></details>
        </article>
      </div>
    </section>
  </article>

  <section class="earlier-research" id="earlier-research">
    <p class="research-theme__eyebrow">Selected foundations</p>
    <h2>Earlier Research</h2>
    <p>Earlier projects established the signal-processing, clinical-speech, and multimodal foundations for the current research program.</p>
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
