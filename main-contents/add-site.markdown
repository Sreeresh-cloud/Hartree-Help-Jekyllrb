---
layout: default
title: Add Site
permalink: /add-site/
---

<div class="styled-list">
  <h2>How to Add a SITE</h2>
  <ol>
    <li>
      In the top navigation bar, click on your organization’s name 
      (e.g., if your company is named “ABC Consultant,” you will see 
      "ABC Consultant" displayed instead of “Your Org Name”).
    </li>
    <img src="{{ site.image_path }}/Addcustomer.png" alt="Add Customer" />

    <li>Select the customer for whom the site needs to be added.</li>
    <li>In the top navigation bar, click the settings gear icon.</li>
    <li>From the settings menu, click <strong>Site Management</strong>.</li>
    <li>Click the <strong>Plus (+)</strong> button to add a new site.</li>
    <li>In the Add Site pop-up window:</li>
    <ul>
      <li>Enter the required site information.</li>
    </ul>
    <li>Click <strong>Save</strong> to complete the process.</li>
  </ol>
</div>

<div class="other-topics">
      <h2>Recommended Topics</h2>
      <ul>
        {% for topic in site.data.shortcuts %}
          {% unless topic.url == page.permalink %}
            <li><a href="{{ topic.url }}">{{ topic.title }}</a></li>
          {% endunless %}
        {% endfor %}
      </ul>
  </div>

