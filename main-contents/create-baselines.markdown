---
layout: default
title: How to Create Baselines
permalink: /create-baselines/
---

<div class="styled-list">
  <h2>How to Create Baselines</h2>
  <p>To add a baseline, you can do the following:</p>
  <ol>
    <li>
      In the top navigation bar, click on your organization’s name 
      (e.g., if your company is named “ABC Consultant,” you will see 
      "ABC Consultant" displayed instead of “Your Org Name”).
    </li>

        <img src="{{ site.image_path }}/Addcustomer.png" alt="Add Customer" />

    <li>Select the customer for whom the goals need to be added.</li>
    <li>Click on the <strong>Hartree</strong> logo in the nav bar to return to the home page.</li>
    <li>Click <strong>Energy Management</strong> from the product list.</li>
    <li>Select the <strong>Site</strong> from the left nav bar.</li>
    <li>Select the <strong>Utility</strong> from the top nav bar.</li>
        <img src="{{ site.image_path }}/9img1.png" alt="" />

    <li>To add a Baseline:
      <ol>
        <li>Scroll down to the <strong>Actual Consumption vs baseline</strong> section.</li>
        <li>Click the <strong>Edit</strong> button to complete the process.</li>
        <li>The <strong>Baseline Management</strong> window will open by clicking the Edit button.</li>
      </ol>
    </li>
    <li>In the <strong>Baseline Management</strong> window:
      <ol>
        <li>Click the <strong>Plus (+)</strong> button to add a new baseline.</li>
        <li>In the <strong>Add baseline</strong> pop-up window:
          <div class="sub-point">
            a) Enter the required baseline information.
          </div>
        </li>
      </ol>
    </li>
    <li>Click <strong>Update</strong> and then <strong>Run</strong> to complete the process.</li>

        <img src="{{ site.image_path }}/9img2.png" alt="" />

    <li>Note: Click the <strong>Expand</strong> button to see the model information (ANOVA table & other statistical parameters of the model).</li>

            <img src="{{ site.image_path }}/9img3.png" alt="" />

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