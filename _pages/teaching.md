---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

Brief summary of my teaching assistant work, followed by itemized entries.

### Summary
<table class="teaching-table">
  <thead>
    <tr>
      <th>Role</th>
      <th>Course(s)</th>
      <th>Institution</th>
      <th>Term(s)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Teaching Assistant</td>
      <td>LTE and 5G Communications; Introduction to Signals, Circuits and Systems</td>
      <td>North Carolina State University, USA</td>
      <td>SP'22, F'23</td>
    </tr>
    <tr>
      <td>Teaching Assistant</td>
      <td>Linear Algebra; Calculus for Engineering</td>
      <td>Özyeğin University, Turkey</td>
      <td>SP'18 to SP'21</td>
    </tr>
  </tbody>
</table>

---

### Teaching items
{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
