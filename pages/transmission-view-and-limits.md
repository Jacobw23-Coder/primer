---
layout: default
title: The transmission view and its limits
---

<figure class="transmission-flow" aria-labelledby="transmission-flow-caption">
  <div class="transmission-noise-legend" aria-hidden="true">
    <span>〰</span> noise can affect every part of the exchange
  </div>
  <div class="transmission-flow-track">
    <div class="transmission-node transmission-noisy">
      <svg class="transmission-icon" viewBox="0 0 64 64" aria-hidden="true">
        <circle cx="32" cy="17" r="9"></circle>
        <path d="M15 51c1.5-11 7-17 17-17s15.5 6 17 17"></path>
      </svg>
      <span>sender</span>
    </div>

    <span class="transmission-arrow" aria-hidden="true">→</span>

    <div class="transmission-node transmission-channel transmission-noisy">
      <svg class="transmission-icon" viewBox="0 0 64 64" aria-hidden="true">
        <circle cx="32" cy="34" r="7"></circle>
        <path d="M32 27V14"></path>
        <path d="M27 14h10"></path>
        <path d="M19 24c3.5-4 8-6 13-6s9.5 2 13 6"></path>
        <path d="M14 19c5-6 11-9 18-9s13 3 18 9"></path>
      </svg>
      <span>channel</span>
    </div>

    <span class="transmission-arrow" aria-hidden="true">→</span>

    <div class="transmission-node transmission-noisy">
      <svg class="transmission-icon" viewBox="0 0 64 64" aria-hidden="true">
        <circle cx="32" cy="17" r="9"></circle>
        <path d="M15 51c1.5-11 7-17 17-17s15.5 6 17 17"></path>
      </svg>
      <span>receiver</span>
    </div>
  </div>
  <figcaption id="transmission-flow-caption">A message moves from sender to receiver through a channel, where noise can interfere.</figcaption>
</figure>

This section introduces the transmission model associated with Shannon and Weaver. It is useful when communication is treated as signal transfer: sender, channel, noise, and receiver.

Starter direction for your analysis:

- What this model clarifies about errors, distortion, and clarity.
- Why it remains useful in digital systems and platform communication.
- What humanistic critiques reveal about context, values, and lived experience.

Use this page to show where mathematical precision helps and where it cannot fully account for meaning, ethics, or interpretation.
