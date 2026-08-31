---
layout: post
title: About
permalink: /about/
comments: true
---

## As a conversation beginner..............


 My favorite places to go
<style>
  .grid {
    display: grid;
    grid-template-columns: repeat(7, 250px);
    grid-auto-rows: auto; /* rows will size based on content */
    padding: 0;
    width: fit-content;
    gap: 0;
  }

  .grid > div {
    display: flex;
    width: 100%;
    height: auto; /* shrink to fit images */
  }

  .grid img {
    width: 50%;       /* side by side */
    height: auto;     /* maintain aspect ratio */
    object-fit: cover;
    display: block;
    border: 3px solid blue;
    box-sizing: border-box;
  }
</style>

<h2>My favorite places to go</h2>

<div class="grid">
  <div>
    <img src="{{site.baseurl}}/images/about/disnleyland.png" alt="My image"> 
    <img src="{{site.baseurl}}/images/about/beach.png" alt="My image 3">
  </div>
  <div></div><div></div><div></div><div></div><div></div><div></div>
  <div></div><div></div><div></div><div></div><div></div><div></div><div></div>
  <div></div><div></div><div></div><div></div><div></div><div></div><div></div>
  <div></div><div></div><div></div><div></div><div></div><div></div><div></div>
  <div></div><div></div><div></div><div></div><div></div><div></div><div></div>
</div>

<comment>
Here is a little bit about where me and my family have previously lived 
</comment>
</comment>

<style>

    .grid-container {

        display: grid;

        grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));

        gap: 10px;

    }

    .grid-item {

        text-align: center;

    }

    .grid-item img {

        width: 100%;

        height: 100px;

        object-fit: contain;

    }

    .grid-item p {

        margin: 5px 0;

    }

</style>

<div class="grid-container" id="grid_container">

    <!-- content will be added here by JavaScript -->

</div>

<script>

    var container = document.getElementById("grid_container");

    var http_source = "https://upload.wikimedia.org/wikipedia/commons/";

    var living_in_the_world = [

        {"flag": "f/f2/Flag_of_Massachusetts.svg", "greeting": "Hello", "description": "Massachusetts"},

        {"flag": "0/01/Flag_of_California.svg", "greeting": "Hey", "description": "California"},

        {"flag": "4/41/Flag_of_India.svg", "greeting": "Namaste", "description": "India"},

    ];

    for (const location of living_in_the_world) {

        var gridItem = document.createElement("div");

        gridItem.className = "grid-item";

        var img = document.createElement("img");

        img.src = http_source + location.flag;

        img.alt = location.flag + " Flag";

        var description = document.createElement("p");

        description.textContent = location.description;

        var greeting = document.createElement("p");

        greeting.textContent = location.greeting;

        gridItem.appendChild(img);

        gridItem.appendChild(description);

        gridItem.appendChild(greeting);

        container.appendChild(gridItem);

    }

</script>
 🇺🇸 I have lived in massachusetts, chelmsford for about three years as I was born there, and my parents ahs lived there for about 10 years.
 🇮🇳 my ethnicty is from india, both my parents are from india, as i was born here my culture is hindiusm.

### Journey through Life

Here is a little bit about me 

- 🏫 My Elementary school (Monterey Ridge Elementary School) 2022 promotion 
- 🏫 My Middle school (Oak Valley Middle School) 2025 promotion
- 🏫 My Highschool ( Delnorte Highschool ) Class of 2029
- 🏐 Volleyball, I was on the delnorte volleyball team, and I play for san diego travel 
- 🏡 Where I was Born, I was born in Boston and moved to San Diego when I was three
- 🧑‍🧑‍🧒‍🧒 Family, I live with my mom, dad, and my little sister who is in second grade 
- 🏝️ Places I've been, Dubai, Cabo, Miami, Hawaii, Boston, Washington, NY
- 🏫 Dream College, my dream college is UCSD, or UCLA

### Culture, Family, and Fun

 A little bit about my family 

- I live with my mom, dad, and my younger sister who is 7 years old 
- I was born in Boston as my parents lived there for 10 years before we moved to san diego when I was 3.
- We intially lived in La Jolla, then we moved to 4s ranch for another 10 years, and latley we moved  closer to black mountai

<comment>
 my family picture
</comment>
<div class="images">
  <img src="{{site.baseurl}}/images/about/family_picture.png" alt="Image 1">

