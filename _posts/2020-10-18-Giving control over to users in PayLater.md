---
layout: post
title: "Giving control over to users in PayLater"
date: 2020-10-15 00:28:00 -0600
brand: "Gojek"
logo: "./assets/landing/logo-gojek.svg"
description: "We aimed to provide users with flexible buy-now-pay-later options by aligning GoPayLater with limits that match what users want, rather than imposing fixed credit limits."
permalink: /:slug
projectvideo: "/assets/pyl/PYL-Intro.mp4"
---


<section id="hero">
  <div class="small-container">
    <h2>Giving control over to users in PayLater</h2>
    <h3>Gojek </h3>
  </div>
</section>
<section id="content">
  <div id="introduction" class="process-step grid-of-two small-container">
    <div>
      <h3>About Gojek & PayLater</h3>
      <p>Gojek is a super app with services like mobility, food delivery, and digital payments. PayLater is a credit product by Gojek which allows users to order food, rides, and do digital payments. Much like a credit card, users can repay all the dues right before its due date.</p>
      <p class="mt-16">My role - lead product and interaction design</p>
    </div>
    <div>
      <h3>UX Problems</h3>
      <p>PayLater users had a fixed limit they could spend. The choice was either this limit or nothing. Our users felt like they couldn't control their spendings in PayLater or couldn't customize their limit based on their needs.</p>
    </div>
  </div>
  <video src="/assets/pyl/PYL-Intro.mp4" autoplay muted loop></video>
  <div class="process-step">
    <h3>Target audience</h3>
    <p>
    The target audience is - PayLater users who need a dynamic limit and want to optimize price to limit ratio. Many users want the lowest plan to continue having access to PayLater. For some users who considered getting PayLater but had a fixed limit and were afraid of overspending.
    </p>
  </div>
  <div class="process-step">
    <h3>User Research</h3>
    <p>
      In March 2020, we started upgrading our users to a higher limit (those who were eligible.) We received negative feedback on social media and realized that users didn't want a higher limit right away. They wanted the choice of moving to higher and lower limits.<br><br>
    </p>
    <p>
    Post that, we have run concept tests with users by offering different limits as plans (combined view of fees and limits.) Our learning was when we position fees and limit, users consider fees as a deciding factor. Whereas fees are fixed after a certain point. This would lead to our users in the wrong direction.<br><br>
    </p>
    <p><b>Our key learnings from the research:</b></p>
    <ul>
      <li>Users need control over their limit and not forced to move to a limit.</li>
      <li>The fee is an important component to the decision, however, users excessive emphasized when present <i>new limits</i> as plans.</li>
    </ul>
  </div>
  <div class="process-step image-container">
    <img src="/assets/pyl/PYL-concept test.png" alt="Some of the iterations we tried out in-house." class="mb-24"/>
    <p>Concept tests was done with feature positioned as "plans" instead of "picking a limit."</p>
  </div>
  <div class="process-step">
    <h3>UX solution</h3>
    <p>The final form of the feature was building a way for our users to customize their PayLater limit. In the first version of the feature, the new limit would be active only at the end of the month after the dues were paid. Given the flow, we broke down the feature into 2 key experiences:</p>
    <ul>
      <li>Customizing the PayLater limit</li>
      <li>Notifying and keeping users updated with their upcoming limit</li>
    </ul>
  </div>
  <div class="process-step image-container">
    <img src="/assets/pyl/PYL-user flows.png" alt="User flows drawn for pick your limit feature" class="mb-24"/>
    <p>Earliest form of the user flows</p>
  </div>
  <div class="process-step">
    <h3>Iterations</h3>
    <p>Before heading in for the usability tests, we explored different approaches. A variant of sliders and not just limited to the UI. We explored different ways of interacting with sliders.</p>
  </div>
  <div class="process-step image-container">
    <img src="/assets/pyl/PYL-iterations.png" alt="Some of the iterations we tried out in-house." class="mb-24"/>
    <p>These are some of those iterations which didn't go through.</p>
  </div>
  <div class="process-step">
    <p>From the usability tests, we figured out there were no major problems in the entire flow. In terms of the usability of the slider design, the moving card turned out to be distracting. Slider with a fixed was usable and intuitive for the participants.</p>
  </div>
  <div class="process-step image-container">
    <video src="/assets/pyl/PYL-wireframe.mp4" autoplay muted loop class="mb-24"></video>
    <p>We created & tested these prototypes as part of the usability tests.</p>
  </div>
  <div class="process-step">
    <h3>Interaction design</h3>
    <p>I partnered with the interaction designer and we explored how could we make the experience more delightful. There were a couple of visual design questions open for discussion like:
    </p>
    <ul>
      <li>How do we handle the success screen when a user cancels their new limit?</li>
      <li>The slider looked very vanilla. How do we add visual weight to these cards?</li>
    </ul>
  </div>
  <div class="process-step image-container">
    <video src="/assets/pyl/PYL-Onboarding.mp4" autoplay muted loop class="mb-24"></video>
    <p>First goal was to handle multiple onboarding nudges in PayLater home. Second to onboard users in a slughtly more engaging way.</p>
  </div>
  <div class="process-step image-container">
    <img src="/assets/pyl/PYL-interaction design-1.png" alt="Developer docs for Helpshift SDK" class="mb-24"/>
    <p>Users can pick from all the limits available and next step is to confirm the changes to the limit & the fees.</p>
  </div>
  <div class="process-step image-container">
    <img src="/assets/pyl/PYL-interaction design-2.png" alt="Developer docs for Helpshift SDK" class="mb-24"/>
    <p>Depending certain user criteria the new limit is either instantly activated or scheduled for a change. For scheduled change, we show when is the new limit due and option to cancel or change the new limit.</p>
  </div>
  <div class="grid-of-two small-container">
    <div class="process-step">
      <h3>Metrics</h3>
      <p>Note: This project is still work-in-progress.</p>
      <ul>
        <li><b>Retention rate:</b> Since the insight from our earlier experiments said, higher limit equals to higher retention, we would be closely monitoring this months after the release.</li>
        <li><b>Number of active users:</b> With the ability to lower your limit to bring down the fees is one of the ways our users can freely try out PayLater and get on board.</li>
      </ul>
    </div>
    <div class="process-step">
      <h3>What's next?</h3>
      <ul>
        <li>An extension of this project is to recommend the right limit for our users based on their spending. We would recommend increasing or decreasing the limit based on the average spending, truly what's the best for our users.</li>
        <li>Enable users to instantly change their limits without waiting for the whole cycle to complete.</li>
      </ul>
    </div>
  </div>
</section>