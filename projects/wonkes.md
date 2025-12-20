---
layout: project
type: project
image: ../img/workbench/finalDraftSquare.png
title: "Final Project: wonkes"
date: 2025
published: true
labels:
  - Software Engineering
  - GitHub
summary: "Final project for ICS 314 Fall 2025"
---

<img class="img-fluid" src="../img/workbench/glueUp.png">

# Introduction
The goal of this project is to enable students at UH Manoa the ability to sell to other students. It was built using Github, Vercel, next.js, Bootstrap, node.js, and PostgresSQL. It uses Vercel and Prisma to store user account information and all the items being sold/have been sold.

# Contributions
It was difficult trying to find a project idea to work on, but we eventually decided on the marketplace idea based on a team poll, along with what we knew and learned in class. It felt very similar to what we already learned, so starting off with our main function (listings) and getting it working felt the easiest to do. On the implementation of getting a user’s profile listing, I had problems with my own local branch. Because there was an issue with node packages compatible with my computer and with the database, the listings had to be hardcoded temporarily just so I could get a workable mockup on the User‘s page. 
I also worked on playwright testing and adding it to Github’s Actions workflow. This enables any pushed code related to user permissions to be checked if it breaks. It was difficult because of how different browsers are. The testing makes sure the code works on Edge, Firefox, and Chrome, but Firefox would always present issues. I added a modification so that past saved instances of a user token (a temporary “key” that could be used as a login instead of the actual login details) would get deleted, just to make sure the current key is up to date for the tests to run correctly.

# What I Learned
What I learned the most on this project was collaboration between other students. It was hard to find times to meet because of the varied schedules of everyone on the team. Some worked, some had class, and we all did our best to work around it. Another thing I learned was the scaling complexity as the project progressed. Project scope was something I only heard of in passing, so having to cut features at the end made me think about managing and prioritizing projects in the future. Communication was also huge. I knew that it was good to reach out if I ever ran into issues, but after working on this project, it made me more comfortable with doing so, as it was always easier for me to spend more time on an issue instead of getting help from my peers.


Source: <a href="https://www.3x3custom.com/store/portable-work-bench-plans"><i class="large github icon "></i>Workbench Plans Used</a>