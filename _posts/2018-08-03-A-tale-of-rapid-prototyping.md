---
layout: post
title: "A tale of rapid prototyping"
date: 2018-08-26 10:15:00 -0600
brand: "CustomerJet"
permalink: /:slug
---


<section id="hero">
  <div class="container">
    <h2>A tale of rapid prototyping</h2>
    <h3>CustomerJet</h3>
  </div>
</section>
<section id="content">
  <!-- INTRODUCTION SECTION -->
  <div id="introduction" class="process-step grid-of-two small-container">
    <div>
      <h3>About CustomerJet</h3>
      <p>CustomerJet was a tool to help technical support engineers understand why a support ticket was created in the first place. We could record the user’s journey and render it as a video. This video would be attached to each support ticket. The last version of CustomerJet worked with Intercom, Zendesk and independently.</p>
    </div>
    <div>
      <h3>Product goal</h3>
      <p>
      CustomerJet helped customer support and experience teams reduce the resolution time and resolve critical conversations faster.
      </p>
    </div>
  </div>
  <img src="/assets/convertfly-making-messenger-marketing-simple/example.png" alt="Convertfly helps Shopify stores with various widgets for recovering sales"
  />
  <!-- UX Solution -->
  <div class="process-step small-container">
    <h3>UX Solution</h3>
    <p>
    CustomerJet captured the user’s journey and rendered it as a video. This video would be attached to the customer conversations and this helped support teams understand why a support ticket was created. The last version of CustomerJet worked with Intercom, Zendesk and independently.
    </p>
  </div>
  <div class="process-step image-container">
    <img src="/assets/a-tale-of-rapid-prototyping/solution.png" alt="Convertfly helps Shopify stores with various widgets for recovering sales"/>
    <p><b>CustomerJet</b>: CustomerJet was designed to be part of existing flow of support engineers</p>
  </div>
  <div class="process-step small-container">
    <h3>User research</h3>
    <p>We locked down the product’s direction toward support teams. Since this project was expected to get to market quickly, I conducted interviews and coffee talks with in-house support engineers.
    Questions would be around what’s their daily routine like and what their toolset.
    </p>
  </div>
  <div class="process-step image-container">
    <img src="/assets/a-tale-of-rapid-prototyping/flow-1.png" alt="Convertfly helps Shopify stores with various widgets for recovering sales"/>
    <p><b>Onboarding</b>: Showing upcoming integrations to create anticipation</p>
  </div>
  <div class="process-step small-container">
    <h3>User flows</h3>
    <p>With a decent knowledge of users and insights gathered by product team, we went ahead with whiteboarding solutions with folks from engineering team. From whiteboard solutions to I headed to drawing user flows so that we've got decent understanding of how to not disrupt support team's work flow.</p>
  </div>
  <div class="process-step image-container">
    <img src="/assets/a-tale-of-rapid-prototyping/userflow-1.png" alt="Convertfly helps Shopify stores with various widgets for recovering sales"/>
    <p><b>Userflow done on Sketch</b>: Lemonade was the beta project name and later rebranded as CustomerJet</p>
  </div>
  <div class="process-step">
    <p>Why do a Chrome extension instead of a whole web app experience?</p>
    <ul>
      <li>A web app would need a new tab which is an additional window to focus on</li>
      <li>Chrome extension permits scraping content (DOM) on the active tab. This helped us retrieve conversation ID and populate user sessions with the same conversation ID.</li>
      <li>Chrome extension was faster to build and there are lesser cases to handle</li>
    </ul><br>
    <p>Session player and the recording module were extracted from our mature product, Visual Website Optimizer (VWO). This helped us resolve engineering complexity early on.</p>
  </div>
  <div class="process-step">
    <h3>Interaction and User Interface design</h3>
    <p>Our product was designed for support teams. And top priority of support teams were to solve tickets and were measured against how many tickets are solved under specific time. For few cases, they needed technical debugging tool which provides console errors. CustomerJet was a product for these few cases.</p>
  </div>
  <div class="process-step image-container">
    <img src="/assets/a-tale-of-rapid-prototyping/chrome-1.png" alt="Convertfly helps Shopify stores with various widgets for recovering sales"/>
    <p><b>Session list for a user</b>: CustomerJet would share a list of user sessions. Each session used timestamp as the title. Support engineer could see which session had more errors to start debugging.</p>
  </div>
  <div class="process-step image-container">
    <img src="/assets/a-tale-of-rapid-prototyping/chrome-2.png" alt="Convertfly helps Shopify stores with various widgets for recovering sales"/>
    <p><b>Error in a session</b>: Before watching a session, support engineers could take a look at errors in the session. If it seems like a known error they could reply back immediately.</p>
  </div>
  <div class="process-step image-container">
    <img src="/assets/a-tale-of-rapid-prototyping/chrome-3.png" alt="Convertfly helps Shopify stores with various widgets for recovering sales"/>
    <p><b>Session list in session player</b>: We added session list in the session player for cases when support engineer has to head to next sessions while debugging</p>
  </div>
  <div class="process-step image-container">
    <img src="/assets/a-tale-of-rapid-prototyping/chrome-4.png" alt="Convertfly helps Shopify stores with various widgets for recovering sales"/>
    <p><b>Bugs list in session player</b>: Each session could have different pages therefore each error has been sorted thorugh pages within the session player</p>
  </div>
  <div class="process-step image-container">
    <img src="/assets/a-tale-of-rapid-prototyping/chrome-5.png" alt="Convertfly helps Shopify stores with various widgets for recovering sales"/>
    <p>Sometimes chrome extension would not load the sessions, therefore, we added a way to search for sessions by entering a Visitor ID. This ID would be attached to the ticket as a custom field.</p>
  </div>
  <div class="process-step small-container">
    <h3>UI Implementation</h3>
    <div class="grid-of-two">
      <div class="process-step">
        <p><b>Tasks involved</b></p>
        <ul>
          <li>Writing HTML over AngularJS and ReactJS</li>
          <li>Styling using SASS</li>
        </ul>
      </div>
      <div class="process-step">
        <p><b>Lessons learnt</b></p>
        <ul>
          <li>Working with Chrome Extensions and Chrome browser APIs</li>
          <li>Played around with AngularJS on Chrome extension and ReactJS for web app</li>
          <li>Writing CSS accelerated the hand-off process</li>
        </ul>
      </div>
    </div>
  </div>
</section>