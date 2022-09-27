---
layout: page
description: A database-driven web application for a fictional animal sanctuary
img: assets/img/aston-animal-sanctuary/homepage.png
importance: 2
category: uni
title: Aston Animal Sanctuary
permalink: /portfolio/aston-animal-sanctuary
---

Coursework completed for a second-year module focused on internet applications & web development.

## Brief

> The organisation has approached you to design and implement their new website. The website should allow a member of staff to record and manage adoptions, and allow members of the public to view & adopt animals.

## Screenshots

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.html path="assets/img/aston-animal-sanctuary/homepage2.png" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.html path="assets/img/aston-animal-sanctuary/animal-list.png" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.html path="assets/img/aston-animal-sanctuary/animal-details.png" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

## Key technologies used

- Laravel with a MySQL database
- TailwindCSS for styling
- Composer & Node.js for package dependencies

The project uses the MVC architecture, with database data passed to views through related Eloquent controllers.

**Project was assessed on:**

- Database design
- Interface design
- Security
  - Authentication
  - Authorisation
- Form validation
  - Password hashing
  - CSRF prevention
- Admin functionality
- Stretch goals
  - Table sorting based on headings
  - Multiple pictures for an animal
  - Animal types, listing animals with a selected type

## [GitHub](https://github.com/georgiamoore/aston-animal-sanctuary) | [Demo](https://aston-animal-sanctuary-2021.herokuapp.com/home) - limited functionality
