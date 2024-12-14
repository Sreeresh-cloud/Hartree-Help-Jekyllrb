---
layout: default
title: How to Add Groups in Energy Management
permalink: /add-groups/
---

<div class="styled-list">
  <h2>How to Add Groups in Energy Management</h2>
  
  <p>To add Groups in Energy Management, you can do the following:</p>
  <ol>
    <li>
      In the top navigation bar, click on your organization’s name 
      (e.g., if your company is named "ABC Consultant," you will see "ABC Consultant" displayed instead of "Your Org Name").
    </li>

        <img src="{{ site.image_path }}/Addcustomer.png" alt="Add Customer" />

    <li>Select the customer for whom the Group needs to be added.</li>
    <li>
      Add a Site in site management for the customer:
      <div class="sub-point">
        a) Follow the 
        <a href="/how-to-add-a-site" style="color: #42b29d; font-weight: bold;">How to Add a Site</a> steps for guidance.
      </div>
    </li>
    <li>Click on the Hartree logo in the nav bar to return to the home page.</li>
    <li>Click <strong>Energy Management</strong> from the product list.</li>
    <li>Click the <strong>Add Group (+)</strong> button to create a new group.</li>
    <li>
      In the Add Group pop-up window:
      <div class="sub-point">
        a) Enter the required group information.
      </div>
    </li>
    <li>Click <strong>Save</strong> to complete the process.</li>
    <li>
      Attach a Site to the Group:
      <div class="sub-point">
        a) Click on the “newly added group” in the left navigation bar to attach the sites.
      </div>
      <div class="sub-point">
        b) Right-click on the newly added group to add sites under a group.
      </div>
      <div class="sub-point">
        c) Click the <strong>Add (+)</strong> button to attach the selected sites to the group.
      </div>
    </li>
  </ol>
  <p>Grouping can be done by country/region or by type:</p>
  <div class="sub-point">
    <div class="example-item" style="padding-bottom: 15px;"><strong>a) Example Region:</strong> USA, Canada, Mexico, etc.</div>
    <div class="example-item" style="padding-bottom: 15px;"><strong>b) Example Type:</strong> Office, Hospital, Retail, etc.</div>
    <div class="example-item" style="padding-bottom: 15px;"><strong>c) Example Type:</strong> Cookie, Chocolate, Brewery, etc.</div>
  </div>

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

