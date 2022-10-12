---
layout: page
title: Schedule
permalink: /schedule/
---

<table>
  <thead>
    <tr>
      <th style="width: 20%;">Time</th>
      <th style="width: 30%;">Talk</th>
      <th>Comments</th>
    </tr>
  </thead>
  <tbody>
    {%- for itm in site.data.schedule -%}
    <tr>
      <td>{{itm.time}}</td>
      {%- if itm.comments -%}
        <td>{{itm.talk}}</td>
        <td>{{itm.comments}}</td>
      {%- else -%}
        <td colspan="2" style="padding-left: 25%;">{{itm.talk}}</td>
      {%- endif -%}
    </tr>
    {%- endfor -%}
  </tbody>
</table>
