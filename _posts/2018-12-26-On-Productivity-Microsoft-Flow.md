---
layout: post
title: On Productivity - Microsoft Flow
tags: [Productivity, Scripting, Macros, Business Process Automation, Flow]
---
![flow]({{ "/assets/img/flow.jpeg" | relative_url }})
I work in a manufacturing/warehouse environment and you might think there is not much room for digital automation on a day-to-day basis. But think again! There are some ways you can automate..
Enter [Microsoft Flow](https://flow.microsoft.com/en-us/){:target="_blank"} [^1]

[^1]: Microsoft changed the name of Flow to 'Power Automate'

I use the Office 365 Business Premium license when one fine and dandy day, I stumbled upon Flow, the *deus ex machina* I didn't know I needed. On a fundamental level, Flow lets you automate 'actions' by connecting a wide variety of services. By this time, I already had some experience using [IFTTT](https://ifttt.com/). Right off the bat, I had intuitive understanding of how Flow is supposed to work.

I will give two examples of how I made use of Flow. The whole point of the examples was to design a solution without purchasing extra software/services and making use of available resources.

### Example 1: Real-time Data Transfer System
I spearheaded my company's quest to be analytics-savvy and designed all our dashboards in [Sisense](https://www.sisense.com/){:target="_blank"}. As a manufacturing service provider, all our data is located in Excel Online files, making it easier for corporate to view raw data whenever required. Our package with Sisense did not have a dedicated connector[^2] for OneDrive Excel files (as of mid-2017). Being the problem solver that I am, I had to figure out a way to get all the data to Sisense. Sisense did connect to Google Sheets, which we had access to. I used Flow to connect OneDrive Excel files to the Google Sheets account. The trigger was any sort of data entry - whenever my field team updated data in Excel Online, my 'flow' would run and copy all data into a specific Google Sheet that I had assigned it to.

Thus, I made a carbon copy of the daily KPIs in Google, which was further linked to Sisense dashboards. Thus creating an 'almost real-time' KPI tracking tool for all our sites.

[^2]: We have since moved away from Sisense to PowerBI. Sisense is a good product, but PowerBI just fit our workflows really well.

### Example 2: Overtime Request Approval System

I was looking into developing a system for capturing overtime requests through our clients at our site in LaGrange, GA. My primary method to capture information was through [Microsoft Forms](https://forms.office.com/){:target="_blank"}. Whenever a client would request overtime for our staff, an automated email would be sent to the site leadership team with key details about the overtime request. The site manager would then be able to accept or decline the request, which would further trigger either an 'Accepted' or 'Declined' email to the leadership team as well as the client who requested overtime.

This workflow was made possible by using Flow and some clever programming to get key details from the form and feed it into the email.

<hr>

I have shared this article as a reference or perhaps an inspiration for you folks to check out Flow and build something out of it. But most importantly, do share the solutions you've built so I can take inspiration to build another cool system
