---
layout: single
title: "Submit a Scam Example"
permalink: /submit/
author_profile: false
toc: false
---

Seen a scam recently? Sharing the details helps us spot patterns and write better educational content for everyone. Submissions are reviewed privately by our team for research purposes — they are **never published or attributed** anywhere on this site.

## Before you submit: please don't include personal information

To keep this process safe for everyone, do **not** include:

- Your own name, email address, phone number, or physical address
- Any other person's name, email address, or phone number
- Financial account numbers, passwords, or ID numbers
- Screenshots or photos (they often contain hidden personal details)

Just describe what happened in general terms — that's exactly what's useful to us. For example, instead of "John Smith called me from 555-1234 pretending to be my bank," write "I received a call from someone pretending to be my bank, claiming there was suspicious activity on my account."

<form action="https://formspree.io/f/xoeagwyl" method="POST">
  <p style="position:absolute;left:-9999px;" aria-hidden="true">
    <label>Leave this field blank: <input type="text" name="_gotcha" tabindex="-1" autocomplete="off"></label>
  </p>

  <p>
    <label for="scam-type"><strong>Scam type</strong></label><br>
    <select id="scam-type" name="Scam type" required>
      <option value="">Select one…</option>
      <option>Phishing email</option>
      <option>Text/SMS scam</option>
      <option>Phone call</option>
      <option>Social media</option>
      <option>Romance scam</option>
      <option>Fake job offer</option>
      <option>Tech support scam</option>
      <option>Other</option>
    </select>
  </p>

  <p>
    <label for="description"><strong>What happened?</strong> (required, please describe in general terms)</label><br>
    <textarea id="description" name="Description" rows="8" style="width:100%;" required></textarea>
  </p>

  <p>
    <label for="reference-link"><strong>Optional reference link</strong> (e.g. a public news article about this type of scam — not a personal profile)</label><br>
    <input type="url" id="reference-link" name="Reference link" style="width:100%;">
  </p>

  <p>
    <label>
      <input type="checkbox" name="Attestation" value="Confirmed" required>
      I confirm this submission does not include personal information about myself or anyone else.
    </label>
  </p>

  <input type="hidden" name="_next" value="{{ '/submit/thanks/' | absolute_url }}">
  <input type="hidden" name="_subject" value="New Gone Phishing scam submission">

  <button type="submit" class="btn btn--primary">Submit</button>
</form>

Read our [Privacy Policy](/privacy/) for more on how submissions are handled.
