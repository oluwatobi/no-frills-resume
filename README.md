# no-frills-resume

A simple application of css and html that allows web designers to create a
basic, mobile friendly, resume.

## Uses
This project is underthe MIT License and will updated as needed.
Simply put, I'm creating this template for anyone to use and it is free
of charge. I only ask that if you use it, please do give credit back to me.

## Quick Start
For a template on setting up a resume, view the [sample.html](https://github.com/oluwatobi/no-frills-resume/blob/master/sample.html)
file in this repository.

## Getting Started
Include this CSS link in your web application.

To create a resume block in your application first start off with the
following html code:
```html
<div class="cv ...">
  ....
</div>
```

This will serve as the container for the resume.

To add a resume section and/or header add the tags as follows:
```html
<div class="cv ...">
  <!-- Resume Section -->
  <div class="resume-section">
    <!-- A resume header should be contained within a resume section-->
    <div class="resume-header">Section Name</div>
  </div>
</div>
```

To add educational experience, build upon the template in a similar manner as follows:
```html
<div class="cv ...">
  ...Unneeded code hidden for generality...
  <!-- Resume Section -->
  <div class="resume-section">
    <div class="resume-header">Section Name</div>
    <!-- Resume Entry -->
    <div class="resume-entry">
      <!-- Any experience (educational or general) should be contained within a "resume-entry" classed div-->
      <div class="education-description">
        <div class="education-title">College or University</div>
        <div class="education-subtitle">
          <div class="education-position">Degree Title</div>
          <div class="education-date">May 20XX</div>
        </div>
      </div>
      <div class="education-highlights">
        <ul>
          <li class="education-bullet">Relevant Coursework</li>
          <li class="education-bullet">Honors</li>
          <li class="education-bullet">Thesis</li>
        </ul>
      </div>
    </div>
  </div>
  ...Unneeded code hidden for generality...
</div>
````

To add other experience, build upon the template:
```html
<div class="cv ...">
  ...Unneeded code hidden for generality...
  <!-- Resume Section -->
  <div class="resume-section">
    <!-- Resume Header -->
    <div class="resume-header">Experience</div>
    <!-- Resume Entry -->
    <div class="resume-entry">
      <!-- Any experience (educational or general) should be contained within a "resume-entry" classed div-->
      <div class="experience-description">
        <div class="experience-title-container">
          <div class="experience-title">Experience Title</div>
          <div class="experience-date">August 20XX-August 20XX</div>
        </div>
        <div class="experience-position">Experience Short Description</div>
      </div>
      <div class="experience-highlights">
        <ul>
          <li class="experience-bullet">Experience highlight 1</li>
          <li class="experience-bullet">Experience highlight 2</li>
          <li class="experience-bullet">Experience highlight 3</li>
        </ul>
      </div>
    </div>
  </div>
  ...Unneeded code hidden for generality...
</div>
```


## Changes
If you find yourself using this template and you make any changes that you
think others would find to be awesome, please don't hesitate to share. Simply
fork this repository, make your changes, and issue a pull request. I'm excited
to see when people use my projects no matter what the extent of use is!
