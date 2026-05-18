---
layout: page
permalink: /publications/
title: Publications
description:
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<div class="publications">

<h2>Preprints</h2>
{% bibliography --group_by none --query @*[abbr=Preprint]* %}

<h2>Conferences</h2>
{% bibliography --group_by none --query @*[abbr=Conference]* %}

<h2>Patents</h2>
<p>TBD — coming soon.</p>

</div>
