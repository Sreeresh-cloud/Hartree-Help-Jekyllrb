---
layout: default
title: How to Create an ASHRAE Energy Audit Report
permalink: //create-audit-report/
---

<div class="styled-list">
  <h2>How to Create an ASHRAE Energy Audit Report</h2>
  <p>To create an ASHRAE Energy Audit Report, you can do the following:</p>
  <ol>
    <li>
      Complete an Audit:
      <div class="sub-point">
        a) Follow the 
        <a href="/energy-audit/" style="color: #42b29d; font-weight: bold;">How to do an ASHRAE Energy Audit</a> 
        steps for guidance.
      </div>
    </li>
    <li>Click on the <strong>Report</strong> tab in the navigation bar.</li>
        <img src="{{ site.image_path }}/5img1.png" alt="" />

    <li>Click the <strong>Plus (+)</strong> button to create a new report.</li>
    <li>
      To create an energy report:
      <div class="sub-point">
        a) Select the template (<strong>ASHRAE Level 1</strong> or <strong>Level 2</strong>) from the dropdown.
      </div>
      <div class="sub-point">
        b) Select the site for which the report needs to be created.
      </div>
      <div class="sub-point">
        c) Select the month/year for which the report needs to be created 
        (Utility analysis will be done for the last 12 months ending on the month selected).
      </div>
      <div class="sub-point">
        d) Keep or edit the ‘report title’ as required. This is the name that will be shown on the report cover page.
      </div>
      <div class="sub-point">
        e) Select the report category – <strong>ASHRAE</strong>.
      </div>
      <div class="sub-point">
        f) Select the checkbox in the relevant section to add that content to the report 
        (Utility types like Elec, Water, Gas, etc., should be selected for utility analysis of the corresponding utility. 
        Systems in the audit summary should be selected to add system summary and recommendations to the report).
      </div>
      <div class="sub-point">
        g) Click <strong>SAVE</strong> to complete the process.
      </div>
    </li>
    <li>Click the <strong>Download</strong> button to download the Word report.</li>

    <img src="{{ site.image_path }}/5img2.png" alt="" />

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
