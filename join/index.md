---
title: Join Us
nav:
  order: 4
  tooltip: Opportunities for students, fellows, and collaborators
---

# {% include icon.html icon="fa-solid fa-user-plus" %}Join Us

Are you curious, motivated, and passionate about scientific research? We welcome enthusiastic students, fellows, and collaborators eager to explore new ideas and build rigorous experimental and bioinformatics skills in the Microbial Biotechnology Division at NIB.

{%
  include button.html
  type="email"
  text="Contact Divisional Head"
  link="hashemnib04@yahoo.com"
%}
{%
  include button.html
  type="email"
  text="Recruitment & Dry Lab Inbox"
  link="mbddrylab@gmail.com"
%}
{%
  include button.html
  icon="fa-solid fa-microscope"
  text="Review Research Areas"
  link="research"
%}

{% include section.html %}

## Pathways & Opportunities

{% capture col1 %}
<div class="mbd-panel">
  <span class="mbd-kicker">Open Pathways</span>
  <h3>Who Can Join</h3>
  <ul>
    <li><strong>Thesis Students:</strong> MS / BS dissertation supervision in microbiology, biotechnology, or bioinformatics</li>
    <li><strong>Research Fellows:</strong> Project-aligned fellowships in functional probiotics, genomics, and enzymes</li>
    <li><strong>Research Interns:</strong> Short-term wet-lab &amp; dry-lab computational training</li>
    <li><strong>Collaborators:</strong> Joint research proposals, strain characterization, and shared manuscripts</li>
  </ul>
</div>
{% endcapture %}

{% capture col2 %}
<div class="mbd-panel">
  <span class="mbd-kicker">How to Connect</span>
  <h3>Start a Conversation</h3>
  <ul>
    <li><strong>01 · Share Your Background:</strong> Mention your university program, coursework, and the wet-lab or genomics skills you hope to develop.</li>
    <li><strong>02 · Propose a Shared Question:</strong> For collaborators, outline the strain collection, assay capability, or grant/manuscript topic.</li>
    <li><strong>03 · Institutional Alignment:</strong> Availability depends on active projects, supervision capacity, and NIB institutional guidelines.</li>
  </ul>
</div>
{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% capture note %}
**Direct Recruitment & Dry Lab Email:** You can write directly to [`mbddrylab@gmail.com`](mailto:mbddrylab@gmail.com) (thesis/dry-lab inquiries) or [`hashemnib04@yahoo.com`](mailto:hashemnib04@yahoo.com) (Divisional Head), or submit the inquiry form below.
{% endcapture %}

{% include alert.html type="info" content=note %}

{% include section.html %}

## Send an Inquiry
{:#recruitment-form}

Interested in joining the division as a thesis student, intern, fellow, or collaborator? Send a brief message outlining your academic affiliation, research interests, and preferred timeframe.

<div id="mbd-submitted-alert" class="alert" style="--color: #22c55e; display: none; max-width: 760px; margin: 20px auto;">
  <i class="icon fa-solid fa-circle-check"></i>
  <div class="alert-content">
    <p><strong>Thank you!</strong> Your inquiry has been sent directly to the Microbial Biotechnology Division inbox (<code>mbddrylab@gmail.com</code>).</p>
  </div>
</div>

<form class="mbd-recruitment-form" action="https://formsubmit.co/mbddrylab@gmail.com" method="POST">
  <input type="hidden" name="_subject" value="MBD Website Recruitment / Collaboration Inquiry" />
  <input type="hidden" name="_captcha" value="false" />
  <input type="hidden" name="_next" id="mbd-form-next" value="" />
  <input type="text" name="_honey" style="display:none" tabindex="-1" autocomplete="off" />

  <div class="mbd-field">
    <label for="join-name">Full Name *</label>
    <input type="text" id="join-name" name="name" required placeholder="Your full name" autocomplete="name" />
  </div>

  <div class="mbd-field">
    <label for="join-email">Email Address *</label>
    <input type="email" id="join-email" name="email" required placeholder="you@university.edu" autocomplete="email" />
  </div>

  <div class="mbd-field mbd-field-full">
    <label for="join-subject">Subject / Opportunity *</label>
    <input type="text" id="join-subject" name="subject" required placeholder="e.g., MS Thesis Supervision in Microbial Genomics" />
  </div>

  <div class="mbd-field mbd-field-full">
    <label for="join-message">Message *</label>
    <textarea id="join-message" name="message" required placeholder="Briefly describe your academic institution, background, research interests, and preferred timeframe..."></textarea>
  </div>

  <div class="mbd-field mbd-field-full">
    <div>
      <button type="submit" class="button">
        <i class="icon fa-solid fa-paper-plane"></i>
        <span>Submit Inquiry</span>
      </button>
    </div>
    <p class="mbd-form-note">
      Routed securely via FormSubmit to <code>mbddrylab@gmail.com</code>. This website does not store personal form data.
    </p>
  </div>
</form>

<script>
  (function () {
    var nextInput = document.getElementById("mbd-form-next");
    if (nextInput) {
      nextInput.value = window.location.origin + window.location.pathname + "?submitted=1#recruitment-form";
    }
    if (new URLSearchParams(window.location.search).get("submitted") === "1") {
      var banner = document.getElementById("mbd-submitted-alert");
      if (banner) banner.style.display = "flex";
    }
  })();
</script>
