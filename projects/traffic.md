---
layout: project
type: project
image: traffic-logo.png
date: 2025
published: true
labels:
  - Web Development
  - Data Visualization
summary: "A web-based dashboard to provide more insight into everyday traffic accidents, as unsafe roads and drivers become an increasing issue in the state."
---

## The Motivation
Every day, there are traffic backups -- a lot of which are caused by car accidents. If you were to view the public HPD traffic incident log on any given day, you would see about 200 traffic incidents. About 100 or more of those are collisions and crashes. With this project, I wanted to explore the idea of creating a visualization dashboard to bring more attention to this increasing problem, and provide insight on specific problem areas or roads. Making the roads a safer place for everyone is the responsibility of each and every one of us.

## Behind the Scenes
As previously stated, there is an existing website with logs on the last 24 hours of traffic incidents. However, this is hard to decipher and get meaningful insights from. However, the data itself is very useful. In order to use this public data, I built a web scraper in Python that would run every hour, grabbing the latest incidents. When the SQL database is updated, the JavaScript heatmap, table, and charts all update as well. Because I wanted to see problem roads and areas, I decided to map out incidents on a heatmap. Of course, you may notice that the H-1 contains most of the incidents. This makes sense, since it is likely the most traveled highway. However, when you zoom into the map. you start to see individual portions of that highway where accidents are more common than others. Is this due to bad signage? Bad on-ramps and off-ramp design? This is exactly the type of questioning I wanted to encourage with this dashboard. As for the charts, we can see what areas specifically have more overall accidents than others, and what type of call was made (collision, complaint, hazardous driver, etc.).

## Future Work
Although I have not published this site yet, I do hope to do so in the future. Before doing so, I would like to do some polishing on the frontend, and add more helpful information on the dashboard.

<div class="text-center p-4">
  <img width="300px" src="https://github.com/kyesteele/kyesteele.github.io/blob/main/traffic.jpg?raw=true">
</div>
