---
layout: post
title: Digitizing Supply Chain and Manufacturing using PowerApps
feature-img: "assets/img/cvr1.jpeg"
tags: [Supply Chain, Industry 4.0, Digitization, PowerApps,  ]
---

I built my company's analytics framework and manage it to drive continuous improvement across all our sites. In 2019, I decided to revisit all our KPIs as I was struggling to get clean, usable, accurate data from our sites for a while. With the ulterior motive of having dependable data for my PowerBI dashboards and the guiding principle of [Occam's Razor](https://en.wikipedia.org/wiki/Occam's_razor), I needed to slash unnecessary KPIs and metrics.

I quickly realized that the current methods of data entry were not user friendly. So began the quest to find the right solution for data entry. The objective was clear - Build a solution which is user friendly to capture data.

## Choosing the Technology - [PowerApps](https://powerapps.microsoft.com/en-us/)
The only reason I chose PowerApps was because it was readily available in my Office suite tools. There is no fun in buying a solution off the shelf, when you can make one with the tools available to you. *Oh how fiscally responsible!*

The most important phase for making an app in my experience is the groundwork to collect the requirements. I devoted a major chunk of time to understand the requirements by speaking with operations leaders and most importantly my own experience as an Industrial Engineer.

## Design and Features
In this section I will discuss the features I built into this app. The guiding principle for my apps was 'Form follows function'. Once the app performs the desired function, I spent only a reasonable amount of time to make it look presentable.

### Usability and Accessibility
![Usability]({{ "/assets/img/scr1.jpeg" | relative_url }})
The app is primarily intended to be used on laptops or desktops. But the design is such that it can be used on a smartphone too.
The big and intuitive icons solve two problems - usability on a smartphone's smaller screen and the app caters to non-native English speakers.

### Tabbed Forms
![tabbedforms]({{ "/assets/img/scr2.jpeg" | relative_url }})

Tabbed forms create a convenient medium of data entry. Hint texts guide the user to fill the correct data. Defined data types for fields allow only numbers in a numerical field, or entries from a drop down only which increases accuracy and submits clean usable data. Poka-Yoke much?!

The arrows on the bottom can be used, especially on smartphones, to navigate between the tabs. Respective arrows get disabled if you are on either first or last tab (pic above shows left arrow disabled)

### Duplicate Entry Detection
![pokayoke]({{ "/assets/img/scr3.jpeg" | relative_url }})
To avoid duplicate data entries, I employ a simple and elegant code to disable and hide the save button if the date and shift combination is detected twice. User is prompted a message that says the chosen combination of date and shift is already submitted.

### Visual Feedback
![pokayoke]({{ "/assets/img/scr4.jpeg" | relative_url }})
On successfully submitting a shift report, the users are navigated to a different 'Success' screen. This is nothing genius, but the visual feedback loop I think is crucial.

### Email Feature
This feature was fun to build! It saves tens of minutes of time per shift for our teams and is very easy to implement. All you need to do is brush up on your HTML coding skills!

'''html
<easy> HTML is pretty easy </easy>
'''
![email]({{ "/assets/img/scr5.jpeg" | relative_url }})
On this screen I let users chose their recent shift reports. It took some clever IF() statements to show color on the selected items in the gallery on the left. On the right, it generates a preview of the email which took some HTML coding and choosing the right fields in the right places by concatenating. *Let the ampersands rain! &&&...*

Users can then click on the 'Email' icon ✉️ and they are directed to a similar success screen and back home.

## Signature of the creator
![easter]({{ "/assets/img/scr6.jpeg" | relative_url }})
*And now for the fun part. What good is an app which does not have an easter egg?! Users can find the app creator's name, yours truly, if they click on a specific location on the home screen!*

## Conclusion and Learning
Powerapps is a really nifty tool to learn and use for the right kind of use case. Powerapps or a similar low-coding platform can really help accelerate digitization of manufacturing and supply chain operations, and provide accurate, usable data downstream. In the end, it is 'Garbage In Garbage Out', no matter if you use Machine Learning or AI or a simple linear regression model downstream. This is my attempt in helping improve the source of data.

Let me know if you might have any feedback for me. I am always learning
