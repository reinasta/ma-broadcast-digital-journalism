---
siteHead: "Registration form"
title: Registration
layout: 'layouts/base.html'
permalink: '/register/index.html'
---


<img src="../_includes/images/camera.svg" alt="camera picture" />

<article id="registration-form">

<h1>Register for a hands-on session in our studios</h1>
<h2>Wednesday 4th May from 2-4pm</h2>
<h2>Broadcast House, St George's Works, 47 Colegate, Norwich NR3 1DD</h2>

<form action="" method="POST" name="registation-form-uea" data-netlify="true" netlify-honeypot="bot-field">
  <div class="hidden">
    <label>
      Are you a bot? If yes, please fill this in. Otherwise ignore this. <input name="bot-field" />
    </label>
  </div>
  <div class="form-entry">
    <label for="name">Full name: </label>
    <input type="text" name="name" id="name" required>
  </div>
  <div class="form-entry">
    <label for="email">Email address: </label>
    <input type="email" name="email" id="email" required>
  </div>
  <div class="form-entry">
    <label for="course">Current course: </label>
    <input type="text" name="course" id="course" required>
  </div>
  <div class="form-entry">
    <label for="year">Year of study: </label>
    <input type="text" name="year" id="name" required>
  </div>
  <div class="form-entry">
    <fieldset>
    <legend>Experience of media (optional): </legend>
      <input type="checkbox" id="some-experience" name="some-experience" value="SomeExperience">
      <label for="some-experience"> I have some experience (e.g. social media)</label><br>
      <input type="checkbox" id="specific-experience" name="specific-experience" value="SpecificExperienceEgConcrete">
      <label for="specific-experience">I have been involved in student media (e.g. Concrete, Livewire, other)
      </label><br>
      <input type="checkbox" id="work-experience" name="work-experience" value="WorkExperience">
      <label for="work-experience"> I have work experience of media</label><br>
      <input type="checkbox" id="no-experience" name="no-expereince" value="NoExperience">
      <label for="no-experience"> No experience, really. I'm keen to learn more.</label><br>
    </fieldset>
  </div>
  <div class="form-entry submit-div">
    <input type="submit" value="Subscribe!">
  </div>
</form>

</article>
