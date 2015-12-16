---
layout: default
title: Build Control Rules
---
<table>
<tr>
  <th>Rule Name</th>
  <th>Dev</th>
  <th>Test</th>
  <th>Prod</th>
</div>
{% for rule in site.data.rules %}
<tr>
  <td>{{ rule.name }}</td>
  <td>?</td>
  <td>?</td>
  <td>?</td>
</div>
{% endfor %}
