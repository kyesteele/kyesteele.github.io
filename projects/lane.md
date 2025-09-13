---
layout: project
type: project
image: lane-logo.png
date: 2025
published: true
labels:
  - Automotive Software
  - Computer Vision
summary: "A computer vision program written in Rust to detect lane positioning while driving."
---

## The Motivation
The car I drive is not old, but too old to have any of the fancy safety features in newer cars. This includes lane detection, collision avoidance/braking, etc. For this project, I wanted to tackle the challenge of adding lane detection to an older car. 

## The Algorithm
To start off, this program does not use any kind of machine learning. First, I convert the image to grayscale, and blur it to remove a lot of the unwanted information in the image. Next, I apply canny edge detection to get a black and white image containing only the stronger outlines of shapes. To only get outlines that are straight lines, I apply a Hough transform, followed by a region of interest masking to only keep the lines directly in front of the car.This, in combination with thresholding, allows the lines to be detected properly. Using Bresenham's line drawing algorithm (because the line does not constrain to the 2d matrix), the detected lane can be highlighted in yellow.

## Challenges
Perhaps the biggest challenge of this project is optimizing it. As of now, it takes a few seconds to complete the entire frame. This is too long of a computation time. I would need to figure out a workaround, or a different approach to speed it up.

<div class="text-center p-4">
  <img width="300px" src="https://github.com/kyesteele/kyesteele.github.io/blob/main/lane1.jpg?raw=true">
  <img width="300px" src="https://github.com/kyesteele/kyesteele.github.io/blob/main/lane2.png?raw=true">
  <img width="300px" src="https://github.com/kyesteele/kyesteele.github.io/blob/main/lane3.png?raw=true">
  <img width="300px" src="https://github.com/kyesteele/kyesteele.github.io/blob/main/lane4.png?raw=true">
</div>
