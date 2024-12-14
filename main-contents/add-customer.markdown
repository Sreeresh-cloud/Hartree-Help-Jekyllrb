---
layout: default
title: Add Customer
permalink: /add-customer/
---

<div class="styled-list">
  <h2>Add a new Customer</h2>
  <ol>
    <li>
      In the top navigation bar, click on your organization’s name 
      (e.g., if your company is named “ABC Consultant,” you will see 
      "ABC Consultant" displayed instead of “Your Org Name”).
    </li>
    <img src="{{ site.image_path }}/Addcustomer.png" alt="Add Customer" />
    <li>Click Add.</li>
    <li>In the Add Customer pop-up window:</li>
    <li>Enter the required customer information.</li>
    <li>Click Save to complete the process.</li>
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

