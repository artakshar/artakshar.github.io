---
layout: post
title: "Designing a system for consistency"
date: 2018-08-26 10:15:00 -0600
brand: "Helpshift"
permalink: /:slug
---


<section id="hero">
  <div class="container">
    <h2>Designing system for consistency</h2>
    <h3>Helpshift</h3>
  </div>
</section>
<section id="content">
  <div id="introduction" class="process-step grid-of-two small-container">
    <div>
      <h3>About Helpshift</h3>
      <p>Helpshift enabled support teams at Microsoft, Supercell, and Tencent Games to help over 600 million users monthly. The next challenge for me in mobile and desktop SDK team was to, create consistency for all projects. I decided to own the design system for mobile SDKs and started off this exercise in early 2017.</p>
    </div>
    <div>
      <h3>Goals of this exercise</h3>
      <p>The primary goal of this exercise was to design a system which would help bring consistency in future SDK projects.</p>
      <ul>
        <li>Refreshing UI for Android SDK</li>
        <li>Design system for future design projects</li>
        <li>Enabling customisability for new components and updating developer docs</li>
      </ul>
    </div>
  </div>
  <img src="/assets/learning-educating-accessibility/landing.png" alt="Landing page for Helpshift"/>
  <div class="process-step">
    <h3>Designing a system for consistency</h3>
    <p>
    Helpshift’s design strategy was to provide native experience. This design system would start off as a style guide and then grow into a design system. The way I envisioned this to progress is,
    </p>
    <ul>
      <li>Colours and typography</li>
      <li>UI elements and components</li>
      <li>Adding usage docs for UI elements and components</li>
      <li>Writing (starting off with tone for error messages)</li>
    </ul>
  </div>
  <div class="process-step">
    <h3>Colours and typography</h3>
    <p>Helpshift's native experience demanded the SDK to be updated with the best practices of each platform. With that in mind, we were using the color palette recommended by Material design (Android) and Human Interface Guidelines for iOS, and macOS.</p>
  </div>
  <div class="process-step image-container">
    <img src="/assets/designing-system-for-consistency/colors-1.png" alt="Color palette in Helpshift style guide"/>
    <p>The original sketch file contained more detailed colour palette with various shades ranging from light backgrounds to dark accented text</p>
  </div>
  <div class="process-step">
    <h3>UI elements and components</h3>
    <p>Existing UI elements and components were plain layers and shapes. These had to converted to Sketch symbols and it's usage, specifications and examples had to be documented for better design collaboration.</p>
    <br><br>
    <p>Before a central document, design team shared Sketch files of projects and picked up UI elements from these. This had caused several inconsistencies in design, such as, several greys, paddings, and margins.</p>
  </div>
  <div class="process-step image-container">
    <img src="/assets/designing-system-for-consistency/elements-1.png" alt="UI components existing in Sketch"/>
    <p>The Sketch file was shared via Confluence</p>
  </div>
  <div class="process-step">
    <h3>Adding usage docs for components</h3>
    <p>With component specifications, we needed a guiding documentation which would help designers and engineers onboard and understand each component when using it.
    <br><br>
    This document was created on our existing knowledge base, Confluence. This document covered details like,
    </p>
    <ul>
      <li>How do you customise a component’s colours and other specifications</li>
      <li>Landscape-orientation behaviour</li>
      <li>Events tracked for a particular component</li>
      <li>An example from our existing use-case</li>
    </ul>
  </div>
  <div class="process-step image-container">
    <img src="/assets/designing-system-for-consistency/documents-1.png" alt="UI components preview in Sketch and Confluence"/>
    <p>All master Sketch file, color palette and components were documented on Confluence</p>
  </div>
  <div class="process-step">
    <h3>Writing</h3>
    <p>The content was all across the SDK. Content like, “Was this helpful?” and “Yes, I’m in”. Similar to our native UI this was packed as the default setup. Therefore we needed some consistency here as well. Simple content corrections like, changing British English to American English across all SDKs and Helpshift Dashboard experience.
    <br><br>
    Along with making existing messaging consistent, I wrote a little writing guide for error messages. This guide will be help the team write better error messages for experiences. This was heavy inspired by writing guidelines published by Google and MailChimp.
    </p>
  </div>
  <div class="process-step image-container">
    <img src="/assets/designing-system-for-consistency/writing-1.png" alt="Screenshot of Google Material Guideline and MailChimp's Voice and Tone"/>
    <p>Documentation done right by Google and MailChimp</p>
  </div>
  <div class="process-step">
    <h3>Customisations and developer docs</h3>
    <p>While updating old components we discovered several components were not customisable and had been rogue. We added the ability to customise these components with the style guide exercise and published changes to Helpshift Developer Docs.
    <br><br>
    The support and success team closed several customisation requests with this update to developer docs.</p>
  </div>
  <div class="process-step image-container">
    <img src="/assets/designing-system-for-consistency/devdocs-1.png" alt="Developer docs for Helpshift SDK"/>
    <p>Developer documentations were updated with latest design customisations</p>
  </div>
  <div class="process-step">
    <h3>Impact of this exercise</h3>
    <ul>
      <li>Design and engineering collaboration was easier with UI elements was documented along with its usage</li>
      <li>Existing designs were now consistent with the native UI across all SDKs</li>
      <li>Components now had more customisations which means more control over design for our customers</li>
    </ul>
  </div>
</section>