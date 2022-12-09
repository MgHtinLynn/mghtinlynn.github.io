---
layout: page
title: About Me
permalink: about
---

<div style="text-align: justify">

<h2 class="dark:text-stone-200 mt-32">Skills</h2>
<p class="dark:text-stone-300">
PHP In Laravel, React, NextJS, VueJS, NuxtJS, Golang (Gin, Gorm), SQL, PostgreSQL, Elasticsearch, XML, Javascript, JQuery, AlpineJS, Livewire, Tailwind, Docker, CI/CD, Unit Testing, REST, GraphQL, Elasticsearch, Redis, Git and SVN.
</p>

<h2 class="dark:text-stone-200 mt-32">Summary</h2>

<ul class="list-disc dark:text-stone-300">
<li>Experienced full-stack developer with a demonstrated history of working in the software industry.</li>
<li>Passionate and a cool guy with a very hardworking mindset, eager to assist others in need, fluent in many technical skills and expertise, and capable of delivering good artefacts on time.</li>
<li>software engineer with seven years of experience and has developed his skills around full-stack web development, DevOps practices, and cloud-based applications.</li>
<li>>Advanced knowledge of design patterns, architecture patterns, and databases.</li>
</ul>

<h2 class="dark:text-stone-200">Work Experience</h2>
<div>
  {% for experience in site.experiences %}
    <div>
  <h4><a class="!mb-0" href="{{ experience.link }}" class="dark:text-stone-300" target="_blank">{{ experience.title }}</a></h4>
  <p class="text-md text-stone-500 dark:text-stone-300 !mt-0">{{ experience.description }}</p>
    </div>
  {% endfor %}
</div>
</div>
