---
layout: post
title: "Learning & educating accessibility"
date: 2018-08-26 10:15:00 -0600
brand: "Design for all"
description: "While building a design system at Helpshift, we took the opportunity to be design experiences that everyone could across all mobile and desktop platforms."
permalink: /:slug
---


<section id="hero">
  <div class="container">
    <h2>Learning & educating accessibility</h2>
    <h3>Helpshift</h3>
  </div>
</section>
<section id="content">
  <div id="introduction" class="process-step grid-of-two small-container">
    <div>
      <h3>About Helpshift</h3>
      <p>Helpshift enabled support teams at Microsoft, Supercell, and Tencent Games to help over 600 million users monthly. The growing number of conversations coupled with the diverse user base led us to focus our efforts on making our UX more inclusive and accessible. I was leading the design efforts for making Helpshift SDKs accessible across all platforms.</p>
    </div>
    <div>
      <h3>Goals of this exercise</h3>
      <ul>
        <li>Adding accessibility to all our existing SDKs</li>
        <li>Work with OS-level accessibility tools: Talkback, VoiceOver, tooltips</li>
        <li>Educating fellow designers about accessibility</li>
        <li>Establishing accessibility processes for design and engineering</li>
      </ul>
    </div>
  </div>
  <img src="/assets/learning-educating-accessibility/landing.png" alt="Landing page for Helpshift"
  />
  <div class="process-step">
    <h3>Adding accessibility to all our existing SDKs</h3>
    <p>
    Accessibility means all text is readable, all elements have the right labels and all the user flows are usable by all. I referred to W3C Compliance for the basic requirements and recommendations for font size and contrast ratio.
    </p>
  </div>
  <img src="/assets/learning-educating-accessibility/platforms.png" alt="Helpshift was designed for Android, iOS, macOS and Windows"/>
  <div class="process-step">
    <h3>Working with Talkback & VoiceOver</h3>
    <p>Most of the devices today have an accessibility tool which reads out a description of everything happening on your screen. You get Talkback on Android and VoiceOver on iOS and macOS.
    </p><br><br>
    <p><b>Defining actions and labelling them right</b></p>
    <p>Accessibility tools use these labels to help users by reading it out. With the accessibility practice we had to add correct labels to provide the same experience to all humans.</p>
    <br>
    <p><b>Defining core user flows</b></p>
    <p>The elements which don’t have to be part of the accessibility flow. Each flows had to be drawn out and then strategic add labels and make elements part of accessibility flow.</p>
  </div>
  <div class="process-step image-container">
    <img src="/assets/learning-educating-accessibility/label.png" alt="Adding correct labels for UI elements"/>
    <p>Previous labels were not contextual therefore they didn't help people with Talkback feature</p>
  </div>
  <div class="process-step">
    <h3>Educating fellow designers about accessibility</h3>
    <p>Helpshift had a design team of 6 product designers. To get inclusive mindsets we had to have equal knowledge of do’s and don’ts of accessibility. I was given the responsibility of creating awareness of the need to think about accessibility and how can we do our best to be more accessible.</p>
    <br>
    <p>Conducted sessions detailing the need to focus on accessibility and what are the tools we would need to design for (Talkback and VoiceOver)</p>
  </div>
  <div class="process-step">
    <h3>Establishing accessibility processes for design & engineering</h3>
    <p>The next step for accessibility efforts at Helpshift was to add accessibility practices to the design process and prepare developers for what to expect with upcoming features.</p>
    <ul>
      <li>A redefined colour palette for eliminating all the colours with bad contrast ratios</li>
      <li>Adding labels to any new UI elements you use</li>
      <li>Using text styles recommended by respective OS (used Material design and Human Interface Guidelines for most of it)</li>
    </ul>
  </div>
  <div class="process-step image-container">
    <img src="/assets/learning-educating-accessibility/process-3.png" alt="Font color with complying with W3C web standards"/>
    <p><b>Maintain color contrasts</b>: Legible text contrast for all age groups</p>
  </div>
  <div class="process-step image-container">
    <img src="/assets/learning-educating-accessibility/process-1.png" alt="Contextual labels for UI elements"/>
    <p><b>Add contextual labels</b>: Example taken from Helpshift Android SDK</p>
  </div>
  <div class="process-step image-container">
    <img src="/assets/learning-educating-accessibility/process-2.png" alt="Font sizing recommended by operating systems"/>
    <p><b>Use system fonts</b>: This one was taken from Apple's HIG documentation</p>
  </div>
  <div class="grid-of-two small-container">
    <div class="process-step">
      <h3>Takeaways and lessons learnt</h3>
      <p>I found this project interesting for the reason there was so much to learn about peripherals of design and reading best practices and industry standards of accessibility.</p>
      <br>
      <p><b>Things I learned</b></p>
      <ul>
        <li>The need for accessibility at scale</li>
        <li>The current state of accessibility tools on Android, iOS & macOS</li>
        <li>The engineering aspects of accessibility</li>
      </ul>
    </div>
    <div class="process-step">
      <h3>What's next?</h3>
      <ul>
        <li>Building features and interactions with accessibility in the design process</li>
        <li>Complying with the accessibility standards for all future platforms</li>
      </ul>
    </div>
  </div>
</section>