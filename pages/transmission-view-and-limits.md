---
layout: default
title: The Transmission View and Its Limits
---
**Communication is more than just sending and receiving messages**

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

Claude Shannon and Warren Weaver's 1949 Transmission Model of communication shows how messages travel from a sender, through a channel, and to a receiver. Throughout this transmission, the sender, receiver, and channel can be affected by noise. Noise is anything that can disrupt the transmission of a message at any stage.  

***Noise Can Be...***
- **Physical-** Any external sound or distraction including sirens, horns or loud music 
- **Psychological-** Internal distractions such as stress, emotional state or preexisting assumptions
- **Physiological-** Physical distractions within a person such as symptoms from illness, fatigue or a headache
- **Semantic-** When a sender and receiver interpret the meanings of words differently, leading to confusion over what exactly is being said

***What It Does Well***

The Transmission Model is helpful for explaining the processes by which a message moves between a sender and receiver. Additionally, it shows how technical errors can disrupt the sender, channel and receiver, leading to a potential lack of understanding.
- **In AI-mediated arguments-** This model can help point out how missing context or incomplete prompting by the user can determine the responses they receive from the chatbot. 

***Where It Falls Short***

The accurate transmission of a model does not ensure that the receiver will interpret its meaning accurately. Human communication involves emotions, individual experiences and prior assumptions that a mathematical model simply cannot account for.
- **In AI-mediated arguments-** It is important to consider that people have their own experiences and emotions that are hard to replicate when writing a prompt. Additionally, messages from one communicator to another in an argument can be misinterpreted, leading to an inaccurate portrayal of events to the chatbot, thus, leading to an unhelpful response. 