---
title: "Machine Learning Engineer (Internship)"
description: "Omdena- Carryt"
dateString: Jan 2022 - April 2022
draft: false
tags: []
showToc: false
weight: 314
--- 
## Project: Delivery Route Optimization in LATAM using AI Planning

### Introduction
In collaboration with Omdena and partner Carryt, I contributed to a project focused on optimizing last-mile logistics in congested cities like Bogota, Lima, Mexico City, and Rio de Janeiro. The goal was to improve logistics using artificial intelligence and route planning to address the challenges posed by urban congestion, especially with the rise of e-commerce after the COVID-19 pandemic.

### About Carryt
Carryt, a Colombian technology company, aims to optimize routes for last-mile logistics. They provide gig economy opportunities for drivers, ensuring a livable wage while offering efficient delivery services. The company operates in Mexico and Brazil, with a significant increase in deliveries from 200K per month in 2021 to a target of 1 million per month in 2022.

### Data Processing and Modeling
The internship involved working with proprietary geospatial data and exploring alternative modeling approaches. We utilized Operational Research tools (OR-tools) from Google AI for finding near-optimal routes, addressing two types of vehicle routing problems: deliveries picked up from a depot and delivered across the city, and items picked up and then dropped off in various parts of the city.

### Data Wrangling
The project included processing datasets provided by Carryt to create a map of Bogota for routing. This involved using shapefiles and Open Street Maps (OSM) files to extract critical information such as average speeds for road segments. Python's GeoPandas and NetworkX were employed for efficient data handling and creating a routing map.

### Modeling
Over ten weeks, the team built algorithms using OR-tools to find optimal routes for vehicles with various constraints. These constraints included vehicle start/stop locations, capacity, time windows for pickups and dropoffs, time spent at each location, and priority considerations. The project addressed challenges akin to the Traveling Salesman Problem (TSP) and the Vehicle Routing Problem (VRP), utilizing state-of-the-art techniques in analytics and machine learning for real-world applications.

### Optimization Techniques
The project explored various optimization techniques, including Divide and Conquer using a grid of cells, finding the nearest edge for correct routing, incorporating OSM restriction sets in the A* algorithm, modifying A* to track optimal edge costs, and implementing a Redis cache for performance improvement.

### Future Work
The internship laid the groundwork for future enhancements, including handling infeasible routing problems, exploring additional parameters in OR-tools for better user feedback, providing alternate solutions, building a more efficient caching strategy, and implementing a hierarchical A* path search algorithm.

### [Read More on Omdena's AI Water Management Project](https://www.omdena.com/projects/ai-water-management)

This experience deepened my understanding of AI planning, route optimization, and real-world applications of machine learning in addressing complex logistics challenges.
