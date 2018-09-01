---
title: 'Are You Trying'
draft: false
type: 'project'
description: 'A test site'
image: '/img/jobs.png'
languages: 'Python, Node.js, MySQL'
github: 'https://github.com/dvontrec/CSS-color-selector'
website: 'https://github.com/dvontrec/SQL-job-viewer'
---

<div class="text-center">
	<img class="img-fluid float-center rounded img-thumbnail" src="/img/jobs.png" alt="Screenshot of Are You Hiring">
</div>
<div class="description">
	<p>This is a project I had seen on blog posts about projects similar to this, so I knew this would be something I created.  This project is broken up into 2 parts.  The first part i built was a python web crawler that uses beautiful soup to crawl the jobs on indeed that are entry level Software Engineering jobs in Louisville, Kentucky.  The program grabs the job, job title, job summary, and the link to the posting and saves them into a csv file.  There is also a writer program that reads from the saved csv of scraped jobs and adds new unique jobs to a SQL database.  The writer filters out duplicates by checking for a matching job post url within the database.  I also chose to filter out Revature jobs, because there was at least 20 of them in my first 130 job scrape, and they require you to have a degree.  The second part of the application is an express app that serves data from the database as a page to view jobs.  The page tracks the number of jobs I have applied to against the total number of jobs.  This is a great way of seeing if I am actually trying.  I plan to create an automated script that scrapes for new jobs every 5 weeks, that way I can keep myself motivated and continue to apply for jobs until I am an employed software developer.</p>
</div>
<div style="display:flex;justify-content:space-around;">
	<a href="https://github.com/dvontrec/indeed-scraper"><i class="fab fa-github fa-2x"></i></a>
	<a href="https://github.com/dvontrec/SQL-job-viewer"><i class="fas fa-github fa-2x"></i></a>
</div>
