---
layout: project
type: project
image: yummyfoologo.png
date: 2023
published: true
labels:
  - Final Project
  - Full Stack Application
summary: "An information hub where UHM students can find and share recipes."
---

<div class="text-center p-4">
  <img width="400px" src="https://github.com/kyesteele/kyesteele.github.io/blob/main/yummyfoologo.png?raw=true">
</div>

## The Vision

For our final project in ICS 314 (Software Engineering I), my group and I were tasked with creating an information hub where UH Manoa students can find and share budget-friendly recipes. Due to factors such as lack of time or money, college students may oftentimes find themselves making unhealthy or suboptimal eating decisions such as purchasing take out. The goal of this project, Yummy Foo, was to provide a platform for students to expand their culinary knowledge and enable them to make healthier meals. Users can browse the current selection of recipes, add new ones, and save their favorites! We hope that this project will benefit all students of UH Manoa and encourage them to eat healthier, even on a budget.

## Major Contributions

My biggest contributions to this project include implementing search functionality, adding translation capabilities, building the back-end, and deploying the application. Although, I would typically be debugging or assisting teammates in addition to my primary tasks.

The first task I worked on was adding search functionality to our website. Having a large collection of recipes, it was crucial that users are able to search for recipes easily. For this, I created a separate page with a search bar to find recipes by the following: name, time, cost, ingredients, and more. Students can find a specific recipe or figure out what they can make with what they have. This search functionality was then added to the admin page as well, so that administrators can easily find the recipe they need to edit or delete.

In addition to the search page, I had added translation capabilities across the application. This was done by relying on the Google Translate API, and placing a translation element within the Navbar. Currently, around 20 languages are supported. Fortunately, I had already done something very similar for a hackathon project.

After completing search and translation implementation, I worked on the majority of the application’s backend. Prior to this, everything had been hard coded to allow us to start with the frontend as this was our preferred process. First, I needed to structure the schema for a collection, and handle publishing and initialization processes. Afterwards, I added favoriting functionality. This involved updating recipe documents within our recipe collection when a user clicks the favorite button as well as removing them from the respective document if they unfavorite it. As a result, I needed to update the publishing logic as well in order for all users to see any recipes on the search page, but only their specific favorite recipes on the favorites page.

Throughout the development of our application, in accordance with our assignments for this class, I deployed the application multiple times. This was done utilizing a remote virtual machine with DigitalOcean.

## Takeaways
After learning a variety of technologies and skills in this course, I loved being able to apply these skills toward a real application. Although it seemed like a rather daunting task given the time constraints, I am very grateful for the teammates I had. Working with a team was significantly more enjoyable and less stressful than when I work on personal projects alone. I even (finally) realized how beneficial pair programming can be! Not only do you have someone to talk through ideas with, you have someone to rely on when you run into problems. In addition to this, the project solidified the importance of thinking through a problem before starting to code. For instance, we ran into a problem implementing favoriting functionality. After taking a step back to really think about what we were trying to accomplish, I found a much simpler, cleaner way to complete this task. If we had taken more time in the beginning to consider different approaches, we could have saved time and spent that extra time on other additional features. Overall, I am very happy with what my team and I were able to accomplish in the given time frame.


Here is a link to our project home page for more information: [Yummy Foo](https://eat-sleep-fortnite-repeat.github.io/eat-sleep-foo-repeat.github.io/){:target="_blank"}

<div class="text-center p-4">
  <img width="400px" src="https://github.com/kyesteele/kyesteele.github.io/blob/main/search.jpg?raw=true">
  <img width="400px" src="https://github.com/kyesteele/kyesteele.github.io/blob/main/favenglish.jpg?raw=true" >
  <img width="400px" src="https://github.com/kyesteele/kyesteele.github.io/blob/main/favkorean.jpg?raw=true" >
</div>
