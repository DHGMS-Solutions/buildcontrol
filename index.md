---
layout: docs
title: Build Control Rules
---
<div class="row">
  <div class="col-md-6">Rule Name</div>
  <div class="col-md-2">Dev</div>
  <div class="col-md-2">Test</div>
  <div class="col-md-2">Prod</div>
</div>
{% for rule in site.data.rules %}
<div class="row">
  <div class="col-md-6">{{ rule.name }}</div>
  <div class="col-md-2">?</div>
  <div class="col-md-2">?</div>
  <div class="col-md-2">?</div>
</div>
{% endfor %}
