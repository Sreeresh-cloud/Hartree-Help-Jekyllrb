---
layout: default
title: How to Calendarize Data & Baselines
permalink: /calendarize-data/
---

<div class="styled-list">
  <h2>How to Calendarize Data & Baselines</h2>
    <p style="margin-bottom: 16px; padding: 16px;">To add a calendarized data & baseline, you can do the following:</p>
    <p style="margin-bottom: 16px; padding: 16px;">
        Calendarization is applied when production or occupancy data is available only on a monthly basis, but utility data is recorded for non-calendarized time periods. This process aligns the utility data with calendar months for more accurate comparison and analysis.
    </p>
    <p style="margin-bottom: 16px; padding: 16px;">
      <strong>Note:</strong> Assumption, the group is added, the site is attached to the group, and data is uploaded.
    </p>


    
    <li>In the <strong>Baseline Management</strong> window: Follow the steps in the "How to Create Baselines" section for guidance.
        <div class="sub-point">
           a) Click the <strong>Plus (+)</strong> button to add a new baseline.
        </div>
        <div class="sub-point">
            b) In the <strong>Add baseline</strong> pop-up window:
        </div>
        <div class="sub-point">
            c) Enter the required baseline information.
        </div>     
    </li>

    <li>In the <strong>Add baseline</strong> pop-up window:
      <div class="sub-point">
        <div class="example-item" style="padding-bottom: 15px;">a) Change <strong>Calendarized [Yes/No]</strong> button to <strong>Yes</strong>.</div>
        <div class="example-item" style="padding-bottom: 15px;">b) <strong>Note:</strong> Default is always not to calendarize.</div>
    </div>
    </li>
    <li>Click <strong>Update</strong> and then <strong>Run</strong> to complete the process.</li>

    <img src="{{ site.image_path }}/10img.png" alt="" />

    <li>Note: Click the <strong>Expand</strong> button to see the model information (ANOVA table & other statistical parameters of the model).</li>
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