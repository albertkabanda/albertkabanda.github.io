---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /Publications/
years: [2016, 2017, 2018, 2019, 2020, 2021]
---

<style>
.jumbotron{
    padding:3%;
    padding-bottom:10px;
    padding-top:10px;
    margin-top:10px;
    margin-bottom:30px;
}
</style>

<div class="jumbotron" style="background-color: transparent; border: none;">
### Articles
{% bibliography --query @article %}
</div>

<div class="jumbotron" style="background-color: transparent; border: none;">
### Thesis 
{% bibliography --query @phdthesis %}
</div>

<div class="jumbotron" style="background-color: transparent; border: none;">
### Refereed Conference Proceedings
{% bibliography --query @inproceedings %}
</div>
