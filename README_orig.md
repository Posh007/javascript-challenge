# JavaScript Homework - JavaScript and DOM Manipulation

## Background

WAKE UP SHEEPLE! The extra-terrestrial menace has come to Earth and we here at `ALIENS-R-REAL` have collected all of the eye-witness reports we could to prove it! All we need to do now is put this information online for the world to see and then the matter will finally be put to rest.

There is just one tiny problem though... our collection is too large to search through manually. Even our most dedicated followers are complaining that they are having trouble locating specific reports in this mess.

That's why we are hiring you. We need you to write code that will create a table dynamically based upon a [dataset we provide](StarterCode/static/js/data.js). We also need to allow our users to filter the table data for specific values. There's a catch though... we only use pure JavaScript, HTML, and CSS, and D3.js on our web pages. They are the only coding languages which can be trusted.

You can handle this... right? The planet Earth needs to know what we have found!

## Your Task

### Before You Begin

1. Create a new repository for this project called `javascript-challenge`. **Do not add this homework to an existing repository**.

2. Clone the new repository to your computer.

3. Inside your local git repository, create a directory for the Javascript challenge. Use the folder names to correspond to the challenges: **UFO-level-1** and **UFO-level-2**.

4. Add your **html** files to this folder as well as your static folder containing your javascript. This will be the main script to run for analysis.

5. Push the above changes to GitHub or GitLab.

6. Ensure your repository has regular commits and a thorough README.md file

### Level 1: Automatic Table and Date Search (Required)

* Create a basic HTML web page or use the [index.html](StarterCode/index.html) file provided (we recommend building your own custom page!).

* Using the UFO dataset provided in the form of an array of JavaScript objects, write code that appends a table to your web page and then adds new rows of data for each UFO sighting.

  * Make sure you have a column for `date/time`, `city`, `state`, `country`, `shape`, and `comment` at the very least.

* Use a date form in your HTML document and write JavaScript code that will listen for events and search through the `date/time` column to find rows that match user input.

### Level 2: Multiple Search Categories (Optional)

* Complete all of Level 1 criteria.

* Using multiple `input` tags and/or select dropdowns, write JavaScript code so the user can to set multiple filters and search for UFO sightings using the following criteria based on the table columns:

  1. `date/time`
  2. `city`
  3. `state`
  4. `country`
  5. `shape`

- - -

### Dataset

* [UFO Sightings Data](StarterCode/static/js/data.js)

- - -

## Rubric

[Unit 14 Rubric - JavaScript Homework - JavaScript and DOM Manipulation](https://docs.google.com/document/d/1KWNS-xCwYBONjvlrIz4zyGkcUu0mP2kpMQh6qj0hKf8/edit?usp=sharing)

- - -
Introduction
UFO enthusiasts, today is your lucky day! Large data sets are often required to be available to the public, especially in collective tasks such as UFO sightings. Web applications are perfect to accomplish this! This project uses basic Javascript to create a simple web application which can retrieve UFO sightings data from the USA and Canada based on filtered selections. The webpage was created using Javascript, HTML and Bootstrap, using the Bootswatch CDN templates(https://www.bootstrapcdn.com/bootswatch/). The project is divided into two search levels, each one with its own directory within the repository:

Level 1: Automatic sightings table from date search. You can see the deployed visualization here.
Level 2: Multiple search categories. You can see the deployed visualization here.
Data sets
The complete data set can be found in the data.js file contained in the static > js folder of both directories. This data set was provided by the Tecnológico de Monterrey Data Analytics Bootcamp for the February - August 2020 term.

Code description
This repository contains the folders UFO-level-1 and UFO-level-2. Each of these directories works on the corresponding task level. To run any of these sripts, make sure to have the complete static folder available in your working directory, since this contains the required css, images and js to run the code. The final visualizations are shown in the index.html template.