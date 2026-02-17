---
title: "Audio files"
layout: single
permalink: /audio/
author_profile: false
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.6"
excerpt: "Audio examples from our recording session"
---

[← Back to Home]({{ site.baseurl }}/){: .btn .btn--inverse}

## Recorded audio (original mix)

During the session, we asked the three musicians to play the following musical pieces:

### Hey Jude by The Beatles (first 30 seconds)

<audio controls style="width: 100%; margin: 20px 0;">
  <source src="{{ site.baseurl }}/audio/hey_jude.wav" type="audio/wav">
  Your browser does not support the audio element.
</audio>

### Don't Know Why by Norah Jones (first 30 seconds)

<audio controls style="width: 100%; margin: 20px 0;">
  <source src="{{ site.baseurl }}/audio/dont_know_why.wav" type="audio/wav">
  Your browser does not support the audio element.
</audio>

### I Will Survive by Gloria Gaynor (first 30 seconds)

<audio controls style="width: 100%; margin: 20px 0;">
  <source src="{{ site.baseurl }}/audio/i_will_survive.wav" type="audio/wav">
  Your browser does not support the audio element.
</audio>

---

## Results with CLASS-net

Here we present the results of the CLASS-net performance on each musical piece:

### Hey Jude by The Beatles

<style>
.audio-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 20px;
  margin: 20px 0;
}
.audio-item {
  background: #f8f9fa;
  border-radius: 8px;
  padding: 15px;
}
.audio-item p {
  margin: 0 0 8px 0;
  font-weight: bold;
  font-size: 0.9em;
  color: #444;
}
audio {
  width: 100%;
}
</style>

<div class="audio-grid">
  <div class="audio-item">
    <p>Full mix</p>
    <audio controls>
      <source src="{{ site.baseurl }}/audio/class/hey_jude_20.wav" type="audio/wav">
    </audio>
  </div>
  <div class="audio-item">
    <p>Saxophone only (using "saxophone" prompt)</p>
    <audio controls>
      <source src="{{ site.baseurl }}/audio/class/hey_jude_sax.wav" type="audio/wav">
    </audio>
  </div>
  <div class="audio-item">
    <p>Violin only (using "violin" prompt)</p>
    <audio controls>
      <source src="{{ site.baseurl }}/audio/class/hey_jude_violon.wav" type="audio/wav">
    </audio>
  </div>
  <div class="audio-item">
    <p>Piano only (using "piano" prompt)</p>
    <audio controls>
      <source src="{{ site.baseurl }}/audio/class/hey_jude_piano.wav" type="audio/wav">
    </audio>
  </div>
</div>

### Don't Know Why by Norah Jones

<div class="audio-grid">
  <div class="audio-item">
    <p>Full mix</p>
    <audio controls>
      <source src="{{ site.baseurl }}/audio/class/dont_know_why_20.wav" type="audio/wav">
    </audio>
  </div>
  <div class="audio-item">
    <p>Saxophone only (using "saxophone" prompt)</p>
    <audio controls>
      <source src="{{ site.baseurl }}/audio/class/dont_know_why_sax.wav" type="audio/wav">
    </audio>
  </div>
  <div class="audio-item">
    <p>Violin only (using "violin" prompt)</p>
    <audio controls>
      <source src="{{ site.baseurl }}/audio/class/dont_know_why_violon.wav" type="audio/wav">
    </audio>
  </div>
  <div class="audio-item">
    <p>Piano only (using "piano" prompt)</p>
    <audio controls>
      <source src="{{ site.baseurl }}/audio/class/dont_know_why_piano.wav" type="audio/wav">
    </audio>
  </div>
</div>

### I Will Survive by Gloria Gaynor

<div class="audio-grid">
  <div class="audio-item">
    <p>Full mix</p>
    <audio controls>
      <source src="{{ site.baseurl }}/audio/class/i_will_survive_20.wav" type="audio/wav">
    </audio>
  </div>
  <div class="audio-item">
    <p>Saxophone only (using "saxophone" prompt)</p>
    <audio controls>
      <source src="{{ site.baseurl }}/audio/class/i_will_survive_sax.wav" type="audio/wav">
    </audio>
  </div>
  <div class="audio-item">
    <p>Violin only (using "violin" prompt)</p>
    <audio controls>
      <source src="{{ site.baseurl }}/audio/class/i_will_survive_violon.wav" type="audio/wav">
    </audio>
  </div>
  <div class="audio-item">
    <p>Piano only (using "piano" prompt)</p>
    <audio controls>
      <source src="{{ site.baseurl }}/audio/class/i_will_survive_piano.wav" type="audio/wav">
    </audio>
  </div>
</div>

## Results with the FastMNMF2 algorithm

Here we present the results of the FastMNMF2 performance on Don't Know Why by Gloria Gaymor:

### FastMNMF2 randomly initialized :

<style>
.audio-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 20px;
  margin: 20px 0;
}
.audio-item {
  background: #f8f9fa;
  border-radius: 8px;
  padding: 15px;
}
.audio-item p {
  margin: 0 0 8px 0;
  font-weight: bold;
  font-size: 0.9em;
  color: #444;
}
audio {
  width: 100%;
}
</style>

<div class="audio-grid">
  <div class="audio-item">
    <p>Full mix</p>
    <audio controls>
      <source src="{{ site.baseurl }}/audio/class/dont_know_why_20.wav" type="audio/wav">
    </audio>
  </div>
  <div class="audio-item">
    <p>Saxophone only</p>
    <audio controls>
      <source src="{{ site.baseurl }}/audio/fast_mnmf_2/dont_know_why_rand_sax.wav" type="audio/wav">
    </audio>
  </div>
  <div class="audio-item">
    <p>Violin only</p>
    <audio controls>
      <source src="{{ site.baseurl }}/audio/fast_mnmf_2/dont_know_why_rand_violon.wav" type="audio/wav">
    </audio>
  </div>
  <div class="audio-item">
    <p>Piano only</p>
    <audio controls>
      <source src="{{ site.baseurl }}/audio/fast_mnmf_2/dont_know_why_rand_piano.wav" type="audio/wav">
    </audio>
  </div>
</div>

### FastMNMF2 initialized with the note dictionary (matrix W) :

<div class="audio-grid">
  <div class="audio-item">
    <p>Full mix</p>
    <audio controls>
      <source src="{{ site.baseurl }}/audio/class/dont_know_why_20.wav" type="audio/wav">
    </audio>
  </div>
  <div class="audio-item">
    <p>Saxophone only</p>
    <audio controls>
      <source src="{{ site.baseurl }}/audio/fast_mnmf_2/dont_know_why_W_sax.wav" type="audio/wav">
    </audio>
  </div>
  <div class="audio-item">
    <p>Violin only</p>
    <audio controls>
      <source src="{{ site.baseurl }}/audio/fast_mnmf_2/dont_know_why_W_violon.wav" type="audio/wav">
    </audio>
  </div>
  <div class="audio-item">
    <p>Piano only</p>
    <audio controls>
      <source src="{{ site.baseurl }}/audio/fast_mnmf_2/dont_know_why_W_piano.wav" type="audio/wav">
    </audio>
  </div>
</div>

### FastMNMF2 initialized with the CLASS-net (matrix H) :

<div class="audio-grid">
  <div class="audio-item">
    <p>Full mix</p>
    <audio controls>
      <source src="{{ site.baseurl }}/audio/class/dont_know_why_20.wav" type="audio/wav">
    </audio>
  </div>
  <div class="audio-item">
    <p>Saxophone only</p>
    <audio controls>
      <source src="{{ site.baseurl }}/audio/fast_mnmf_2/dont_know_why_H_sax.wav" type="audio/wav">
    </audio>
  </div>
  <div class="audio-item">
    <p>Violin only</p>
    <audio controls>
      <source src="{{ site.baseurl }}/audio/fast_mnmf_2/dont_know_why_H_violon.wav" type="audio/wav">
    </audio>
  </div>
  <div class="audio-item">
    <p>Piano only</p>
    <audio controls>
      <source src="{{ site.baseurl }}/audio/fast_mnmf_2/dont_know_why_H_piano.wav" type="audio/wav">
    </audio>
  </div>
</div>

---

[← Back to Home]({{ site.baseurl }}/){: .btn .btn--inverse}