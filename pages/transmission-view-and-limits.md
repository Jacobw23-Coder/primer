---
layout: default
title: The transmission view and its limits
---

<figure class="transmission-flow" aria-label="Sender, channel, and receiver with noise affecting the full exchange">
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
      <svg class="transmission-icon" viewBox="0 0 64 64" aria-hidden="true">
        <rect x="25" y="25" width="14" height="14" rx="2"></rect>
        <path d="M25 29H12v9h13"></path>
        <path d="M39 29h13v9H39"></path>
        <path d="M16 29v9"></path>
        <path d="M48 29v9"></path>
        <path d="M32 25V14"></path>
        <path d="M27 14h10"></path>
        <circle cx="32" cy="45" r="2"></circle>
      </svg>
      <span>channel</span>
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
  <span class="transmission-noise-label">noise</span>
</figure>

This section introduces the transmission model associated with Shannon and Weaver. It is useful when communication is treated as signal transfer: sender, channel, noise, and receiver.

Starter direction for your analysis:

- What this model clarifies about errors, distortion, and clarity.
- Why it remains useful in digital systems and platform communication.
- What humanistic critiques reveal about context, values, and lived experience.

Use this page to show where mathematical precision helps and where it cannot fully account for meaning, ethics, or interpretation.
