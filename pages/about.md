---
layout: page
title: About Me
permalink: about
---

<div style="text-align: justify">

<h2 class="dark:text-stone-200 mt-32">Summary</h2>
<p class="dark:text-stone-300">
Lynn is a experienced Full-Stack Developer with a demonstrated history of working in the software industry. Passionate
Developer. A cool guy with a very hard-working mindset, willing to help when other people are in need,
fluent with many technical skill and expertise, delivering good artefacts in time.
 <br>
He is a Software Engineer with seven years of experience and has developed his skills around fullstack web development, DevOps practices, and cloud-based applications. He has advanced knowledge of design patterns, architecture patterns and databases.
</p>

<h2 class="dark:text-stone-200">Formation</h2>
<p class="dark:text-stone-300">
Since fall 2022, Lynn is part-time final-year student in <a href="https://www.test02.nccedu.com/qualification/bsc-hons-business-information-technology">B.Sc (Hons:) Business IT </a> University of Greenwich in UK.
<br>

Prior to that, he worked during over seven year as a full time software engineer when he drop-out from university in 2014 with a bachelor's degree Diploma In Computing. Then 2021 he is trying return back to attend the university and received the trophy bachelor Degree B.Sc (Hons:) Business IT in 2023 March.
</p>

<h2 class="dark:text-stone-200">Work Experience</h2>
<div>
  {% for experience in site.workExperences %}
    <div>
  <h4><a class="!mb-0" href="{{ experience.link }}" class="dark:text-stone-300" target="_blank">{{ experience.title }}</a></h4>
  <p class="text-md text-stone-500 dark:text-stone-300 !mt-0">{{ experience.description }}</p>
    </div>
  {% endfor %}
</div>
</div>
