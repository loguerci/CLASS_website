---
layout: splash
title: "Acoustic Sound Recording and Music Sound Separation"
header:
  overlay_color: "#00000083"
  overlay_filter: "0.5"
---

## Introduction

This page is dedicated to a project conducted within the ATIAM Master’s program. The objective of this project is to separate a trio consisting of a tenor saxophonist, a violinist, and a pianist, recorded together in an acoustic room, as if each instrument had been recorded independently. Our approach is based on the relationship between microphone placement strategies for high-quality sound recording and a source separation algorithm combining deep learning and signal processing methods.

[Read full paper]({{ site.baseurl }}/assets/PAM_Rapport_Groupe2.pdf){: .btn .btn--primary}
[View Recording Session Photos]({{ site.baseurl }}/photo/){: .btn .btn--primary}
[View Recording Session audio files]({{ site.baseurl }}/audio/){: .btn .btn--primary}


## Abstract

Over the past several years, significant progress has been made in Music Source Separation (MSS). From the vibration of musical instruments to the audio signal present in a finalized recording, numerous factors come into play. These include the acoustic radiation of the instrument, the movements associated with musical performance, the room’s response to a moving acoustic source, the microphone array configuration, and the transformations applied during post-production. Due to the complexity and variability of these factors, establishing a new state-of-the-art
approach remains challenging.

From this perspective, the objective of source separation is to design algorithms capable of virtually reversing this entire chain of transformations and mixing processes in order to estimate the signal produced by each individual musical instrument. This can be achieved by incorporating prior knowledge about both the structure of the source signals and the nature of the transformations they have undergone.

In this paper, we present a novel hybrid source separation pipeline that leverages CLAP-based Language-Queried Audio Source Separation (CLASS-net) as a prior for initializing the Fast Multichannel Non-Negative Matrix Factorization (FastMNMF) algorithm. Despite the complexity of the task, we demonstrate that the model can achieve respectable results compared to the state-of-the-art methods.

## Authors

**Loïs Guerci** • **Louis Gosselin** • **Samy Benzaïm** • **Antonin Longeot** • **Jean-Henri Nothias**

---

[View on GitHub](https://github.com/loguerci/LASS_PAM){: .btn .btn--primary}