---
layout: page
permalink: /research/
title: research
description: This page describes research projects I am currently working on. My work examines how political information, identity, and behavior interact across electoral, online, and everyday settings. Please reach me at ml4967@columbia.edu if you have any questions or are interested in collaborating.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2 class="bibliography">Cross-Border Political Communication and Online Discourse</h2>

{% bibliography --group_by none --query @*[keywords~=cross-border] %}

<h2 class="bibliography">Political Identity, Group Attachments, and Voting Behavior</h2>

{% bibliography --group_by none --query @*[keywords~=identity-voting] %}

<h2 class="bibliography">Campaigns, Participation, and Everyday Political Behavior</h2>

{% bibliography --group_by none --query @*[keywords~=campaigns-everyday] %}

</div>
