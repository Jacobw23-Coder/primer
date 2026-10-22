---
layout: default
title: The transmission view and its limits
---

<figure class="transmission-flow" aria-labelledby="transmission-flow-caption">
  <div class="transmission-flow-track">
    <div class="transmission-node">
      <svg class="transmission-icon" viewBox="0 0 64 64" aria-hidden="true">
        <circle cx="32" cy="17" r="9"></circle>
        <path d="M15 51c1.5-11 7-17 17-17s15.5 6 17 17"></path>
      </svg>
      <span>sender</span>
    </div>

    <span class="transmission-arrow" aria-hidden="true">→</span>

    <div class="transmission-node transmission-channel">
      <div class="transmission-noise" aria-hidden="true">〰</div>
      <svg class="transmission-icon" viewBox="0 0 64 64" aria-hidden="true">
        <path d="M19 40 45 14"></path>
        <path d="m39 20 5-5 5 5"></path>
        <path d="M24 45 14 55"></path>
        <path d="M31 38 53 60"></path>
        <path d="M38 31 50 43"></path>
        <path d="M11 25c6-6 15-6 21 0"></path>
        <path d="M16 30c3-3 8-3 11 0"></path>
        <circle cx="20" cy="34" r="2"></circle>
      </svg>
      <span>channel</span>
      <small>noise</small>
    </div>

    <span class="transmission-arrow" aria-hidden="true">→</span>

    <div class="transmission-node">
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
