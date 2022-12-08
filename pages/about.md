---
layout: page
title: About Me
permalink: about
---

<div style="text-align: justify">

<h2 class="dark:text-stone-200 mt-32">Skills</h2>
<p class="dark:text-stone-300">
PHP In Laravel, React, NextJS, VueJS, NuxtJS, Golang (Gin, Gorm), SQL, XML, Javascript, JQuery, AlpineJS, Livewire, Tailwind, Docker, Unit Testing, REST, GraphQL, Git, SVN
</p>

<h2 class="dark:text-stone-200 mt-32">Summary</h2>
<p class="dark:text-stone-300">
Lynn is an experienced full-stack developer with a demonstrated history of working in the software industry. Passionate Developer. A cool guy with a very hardworking mindset, eager to assist others in need, fluent in many technical skills and expertise, and capable of delivering good artefacts on time.
 <br>
He is a software engineer with seven years of experience and has developed his skills around full-stack web development, DevOps practices, and cloud-based applications. He has advanced knowledge of design patterns, architecture patterns, and databases.
</p>

<h2 class="dark:text-stone-200">Formation</h2>
<p class="dark:text-stone-300">
Since fall 2022, Lynn is part-time final-year student in <a href="https://www.test02.nccedu.com/qualification/bsc-hons-business-information-technology">B.Sc (Hons:) Business IT </a> University of Greenwich in UK.
<br>

Prior to that, Lynn has been a part-time final-year student in the B.Sc. (Hons.) Business IT programme at the University of Greenwich, UK, Myanmar campus since the fall of 2022. He worked for over seven years as a full-time software engineer before dropping out of university in 2014 with a bachelor's degree in computing. In March 2021, he attempts to return to university and receives the trophy for his bachelor's degree, a B.Sc. (hons.) in business information technology.
</p>

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
