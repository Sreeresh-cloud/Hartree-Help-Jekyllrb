---
layout: default
title: Add Project
permalink: /add-project/
---

<div class="styled-list">
  <h2>How to Add a Project in Remote Assessment</h2>
  <ol>
    <li>
      In the top navigation bar, click on your organization’s name 
      (e.g., if your company is named “ABC Consultant,” you will see 
      "ABC Consultant" displayed instead of “Your Org Name”).
    </li>
     
    <img src="{{ site.image_path }}/Addcustomer.png" alt="Add Customer" />
 
    <li>Select the customer for whom the audit needs to be done.</li>
     
        <li>
          Follow the 
          "<a href="/add-site/" style="color: #42b29d; font-weight: bold;">How to Add a Site</a>" 
          steps for guidance.
        </li>
      
    <li>Click on the <strong>Hartree</strong> logo in the navigation bar to return to the home page.</li>
    <li>Click <strong>Remote Assessment</strong> from the product list.</li>
    <li>Click the <strong>Plus (+)</strong> button to add a new Project.</li>
    
        <li>Enter the required project information.</li>
        <li>The <strong>‘project owner’</strong> name is mandatory.</li>
      
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

