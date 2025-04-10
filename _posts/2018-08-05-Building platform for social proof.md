---
layout: post
title: "Building a platform to increase sales"
date: 2018-08-26 10:15:00 -0600
brand: "GrowthKit (Wingify)"
description: "GrowthKit, a revenue-boosting platform, leveraged customer insights like sales per week and trending products. Targeting mid-sized e-commerce companies with $1 million in annual revenue, initial tests yielded an impressive 15% average conversion rate uplift."
permalink: /:slug
projecttype: desktop
projectimage: "/assets/building-platform-for-social-proof/cover.png"
---


<section id="hero">
  <div class="container">
    <h2>Building a platform to increase sales</h2>
    <h3>GrowthKit</h3>
  </div>
</section>
<section id="content">
  <div id="introduction" class="process-step grid-of-two small-container">
    <div>
      <h3>About GrowthKit</h3>
      <p>GrowthKit is platform which helped marketers increase revenue by leveraging customer insights such as, sales per week and trending products. We started off with marketing managers at mid-sized e-commerce companies. These companies were at 1 million dollars in annual revenue. The initial tests provided an average uplift of conversion rate by 15%.</p>
    </div>
    <div>
      <h3>Product goals</h3>
      <ul>
        <li>Increase sales with social proof widgets</li>
        <li>Core use-case should be developer independent</li>
        <li>Adding widgets should be interactive experience</li>
      </ul>
    </div>
  </div>
  <img src="/assets/building-platform-for-social-proof/example.png" alt="GrowthKit Onboarding"
  />
  <!-- UX Solution -->
  <div class="process-step">
    <h3>User persona and design challenge</h3>
    <p>
    Our target audience was marketing managers at mid-sized e-commerce. Top design challenge was to be intuitive, and easy to setup.
    </p>
  </div>
  <div class="process-step">
    <h3>UX Solution</h3>
    <p>GrowthKit was designed as platform for the industry a marketer belongs to. One example of how this would impact the website is, the suggested widgets would differ for a travel website versus fashion website.</p>
    <br>
    <p>Another core experience was around embedding widgets on a webpage. For this we used the Editor component from our Component Library. With a little modifications we were ready to test out this new experience.</p>
  </div>
  <img src="/assets/building-platform-for-social-proof/solution-1.png" alt="Mocks for GrowthKit UI"/>
  <div class="process-step">
    <h3>User research</h3>
    <p>Attended close to ~40 customer interviews and gather insights along with product owner.</p>
    <br>
    <p>Key insights from user research</p>
    <ul>
      <li>Drive more sales without giving out discounts or offers at all times. Social proof is an effective way of doing it without having to give away a lot of discounts</li>
      <li>A lot of the tools out there don't tell you what a lot of the best practices are, we guide you through the best usage of social proof notifications across your store</li>
      <li>Customers are looking out for what other folks like them are purchasing and what other customers are talking about the products they are about to purchase, Social proof makes it possible to leverage that information</li>
      <li>Marketing is stretched for resources and getting developers to set up these campaigns themselves is a hard task</li>
    </ul>
  </div>
  <div class="process-step">
    <h3>Wireframes</h3>
    <p>We believe in getting feedback from potential users early on. Therefore, these wireframes were translated from pen and paper to mid-fidelity. This helped us with testing some of the UI elements along with the UX flow early.</p>
  </div>
  <img src="/assets/building-platform-for-social-proof/wireframes-1.png" alt="Wireframes for GrowthKit"/>
  <div class="process-step">
    <h3>Additional customer interviews</h3>
    <p>During our wireframing the designs we had great opportunity to show the wireframe to early adopters. We conducted these tests remotely. Top questions usually would be,</p>
    <ul>
      <li>How aware are you at this stage of the type of data sources you want to connect?</li>
      <li>What do you understand by the different pages shown here?</li>
      <li>What levers of customisation are would you like to see here?</li>
      <li>If you were to compare connecting data sources at this point vs at the start which one would you prefer</li>
    </ul>
    <br>
    <p><b>Key insights from the customer interviews</b></p>
    <ul>
      <li>Some kind of live preview on their website</li>
      <li>Wished to see messaging and design under the same step</li>
      <li>Most of the users wanted Google Analytics connection to be done while being on-boarded</li>
    </ul>
  </div>
  <div class="process-step">
    <h3>Interaction and User Interface design</h3>
    <p>The interaction design for GrowthKit was influenced by our learning from Convertfly. On the similar lines, GrowthKit helped marketers set up different campaigns for increase sales at the different part of the customer journey. The majority of interaction work was around the setup and onboarding flow.
    </p>
  </div>

  <div class="process-step mb-24">
    <p><b>Design decision: </b>Spliting onboarding flow into steps</p>
    <br>
    <p>I split onboarding experience into three steps than one long form which I explored in the wireframing phase. Steps makes users show progress and increase chances of finish-up form.</p>
    <br>
    <img src="/assets/building-platform-for-social-proof/onboarding-solutions.png" alt="Wireframing solutions for onboarding"/>
  </div>
  <div class="process-step image-container">
    <img src="/assets/building-platform-for-social-proof/onboarding-1.png" alt="First step of onboarding; Picking your industry"/>
    <p><b>Onboarding</b>: Capturing industry as a first and then product could adapt to that industry</p>
  </div>
  <div class="process-step image-container">
    <img src="/assets/building-platform-for-social-proof/onboarding-2.png" alt="Second step of onboarding; Connect various integration"/>
    <p><b>Onboarding</b>: Showing upcoming integrations to create anticipation</p>
  </div>

  <div class="process-step mt-56 mb-24">
    <p><b>Design decision: </b>Adding previews inside the form</p>
    <br>
    <p>There were two solutions I looked at. First, adding preview for the product would be outside the form (most products don't show previews are not part of form) and second adding preview next to the form selection. Adding preview in the form helped with making it more connected to the form due to its close proximity to form.</p>
    <br>
    <img src="/assets/building-platform-for-social-proof/campaigns-solutions.png" alt="Wireframing solutions for campaign details"/>
  </div>
  <div class="process-step image-container">
    <img src="/assets/building-platform-for-social-proof/campaign-1.png" alt="Form for a campaign in GrowthKit"/>
    <p><b>Campaigns</b>: The form on a card gains focus while everything is flatten with grey background</p>
  </div>
  <div class="process-step image-container">
    <img src="/assets/building-platform-for-social-proof/campaign-2.png" alt="Campaign detail form with next button highlighted"/>
    <p><b>Campaigns</b>: Setting expectations right; Next button has the informs what's next to come</p>
  </div>

  <div class="process-step mt-56 mb-24">
    <p><b>Design decision: </b>Categorising campaigns based on recommended page</p>
    <br>
    <p>Each campaign are recommended for a particular part of the flow (like, homepage or checkout page). A tab approach would be work out well if each tab would have 3 or more campaigns. We had 3 to 5 campaigns therefore simply tagging each campaign made sense for a smaller pool of campaigns.</p>
    <br>
    <img src="/assets/building-platform-for-social-proof/homepage-solutions.png" alt="Wireframing solutions for grid of all campaigns offered in GrowthKit"/>
  </div>
  <div class="process-step image-container">
    <img src="/assets/building-platform-for-social-proof/widgets-1.png" alt="Campaign home with suggested campaigns"/>
    <p><b>All widgets</b>: We suggest widgets based on the industry marketer selects in onboarding flow</p>
  </div>
  <div class="process-step image-container">
    <img src="/assets/building-platform-for-social-proof/widgets-3.png" alt="Campaigns home with tags highlighted"/>
    <p><b>All widgets</b>: Tags help user learn where the widget would work the best</p>
  </div>
  <div class="process-step image-container">
    <img src="/assets/building-platform-for-social-proof/widgets-2.png" alt="Campaign home with preview button highlighted"/>
    <p><b>All widgets</b>: Preview helps users understand widgets without investing efforts in setting them up</p>
  </div>
  <div class="process-step">
    <h3>What's next?</h3>
    <p>GrowthKit was not to be explored further as a separate brand. Instead this would be integrated with VWO (Visual Website Optimizer) and be part of Wingify brand. Next steps to this is,</p>
    <ul>
      <li>Understand and utitlise Wingify Design System to integrate GrowthKit smoothly into VWO</li>
      <li>Discuss and align product goals with senior product managers at VWO</li>
      <li>Collaborating with VWO engineering and design teams for execution</li>
    </ul>
  </div>
</section>