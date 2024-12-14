---
layout: default
title: How to Upload Utility Data Using Excel
permalink: /upload-utility-data/
---

<div class="styled-list">
  <h2>How to Upload Utility Data Using Excel</h2>
  <p>To upload utility data, you can do the following:</p>
  <ol>
    <li>
      In the top navigation bar, click on your organization’s name 
      (e.g., if your company is named “ABC Consultant,” you will see 
      "ABC Consultant" displayed instead of “Your Org Name”).
    </li>

    <img src="{{ site.image_path }}/Addcustomer.png" alt="Add Customer" />

    <li>Select the customer for whom the Group needs to be added.</li>
    <li>
      Add a Site in site management for the customer:
      <div class="sub-point">
        a) Follow the 
        <a href="/add-site/" style="color: #42b29d; font-weight: bold;">How to Add a Site</a> 
        steps for guidance.
      </div>
    </li>
    <li>Click on the <strong>Hartree</strong> logo in the navigation bar to return to the home page.</li>
    <li>Click <strong>Energy Management</strong> from the product list.</li>
    <li>
      Add a Group in Energy Management:
      <div class="sub-point">
        a) Follow the 
        <a href="/add-group/" style="color: #42b29d; font-weight: bold;">How to Add a Group</a> 
        steps for guidance.
      </div>
    </li>
    <li>
      Attach a Site to the group:
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
    <li>
      Click the <strong>Connect/Upload</strong> button to upload utility data:
      <div class="sub-point">
        a) In the file upload tab, click the <strong>Choose File</strong> button to select the Excel file to upload.
      </div>
      <div class="sub-point">
        b) Click on the file name to upload the data.
      </div>
    </li>

    <img src="{{ site.image_path }}/7img1.png" alt="" />

  </ol>
  <p><strong>Note:</strong></p>
  <div class="sub-point">
    <div class="example-item" style="padding-bottom: 15px;">a)<strong>Ignore:</strong> will only add new timestamp data (if available), and the existing data will not be changed..</div>
    <div class="example-item" style="padding-bottom: 15px;">b)<strong>Replace:</strong> will add a new timestamp (if available) and replace all the old timestamps if repeating.</div>
</div>
</div>


<div class="other-topics">
      <h2> Recommended Topics</h2>
      <ul>
        {% for topic in site.data.shortcuts %}
          {% unless topic.url == page.permalink %}
            <li><a href="{{ topic.url }}">{{ topic.title }}</a></li>
          {% endunless %}
        {% endfor %}
      </ul>
    </div>



