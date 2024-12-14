---
layout: default
title: How to do an ASHRAE Energy Audit
permalink: /energy-audit/
---

<div class="styled-list">
  <h2>How to do an ASHRAE Energy Audit</h2>
  <p>To do an audit, follow these steps:</p>
  <ol>
    <li>
      In the top navigation bar, click on your organization’s name 
      (e.g., if your company is named “ABC Consultant,” you will see 
      "ABC Consultant" displayed instead of “Your Org Name”).
    </li>

        <img src="{{ site.image_path }}/Addcustomer.png" alt="Add Customer" />


    <li>Select the customer for whom the audit needs to be done.</li>
    <li>
      Add a site in Site Management for which the audit needs to be conducted:
      <div class="sub-point">
        a) Follow the 
        <a href="/add-site/" style="color: #42b29d; font-weight: bold;" >How to Add a Site</a> 
        steps for guidance.
      </div>
    </li>
    <li>Click on the <strong>Hartree</strong> logo in the navigation bar to return to the home page.</li>
    <li>Click <strong>Remote Assessment</strong> from the product list.</li>
    <li>
      Add a project:
      <div class="sub-point">
        a) Follow the 
<a href="/add-project/" style="color: #42b29d; font-weight: bold;" >How to Add a Project</a>
        steps for guidance.
      </div>
    </li>
    <li>Click on the newly added project.</li>
    <li>
      Attach the site to be audited:
      <div class="sub-point">
        a) In the left navigation bar, click on the “newly added project name” 
        to attach the sites that need to be audited to the project.
      </div>
    </li>

    <img src="{{ site.image_path }}/4img1.png" alt="" />


    <li>Select the site that needs to be audited.</li>
    <li>
      To add a location under a site:
      <div class="sub-point">
        a) Click on the site in the left navigation bar.
      </div>
      <div class="sub-point">
        b) Click on the hamburger button (three horizontal lines) next to the site 
        to add a location (e.g., a building).
      </div>
    </li>
    <li>
      To add equipment/system under a location:
      <div class="sub-point">
        a) Click on the newly added location in the left navigation bar.
      </div>
      <div class="sub-point">
        b) Click the hamburger button next to the location to add equipment/system 
        (e.g., cooling, heating).
      </div>
      <div class="sub-point">
        c) Repeat the process to add more systems relevant to the site.
      </div>
    </li>

        <img src="{{ site.image_path }}/4img2.png" alt="" />

    <li>
      Select the added location or equipment/system and click the 
      <strong>Audit</strong> button to start the audit:
      <div class="sub-point">
        a) Enter the required project information.
      </div>
      <div class="sub-point">
        b) Click <strong>Save</strong> to complete the process.
      </div>
    </li>
            <img src="{{ site.image_path }}/4img3.png" alt="" />

    <li>Recommendations are automatically generated.</li>
    <li>Photos, notes, and files can be attached to an audit.</li>
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

