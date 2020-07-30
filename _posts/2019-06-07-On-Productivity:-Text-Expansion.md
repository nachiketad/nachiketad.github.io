---
layout: post
title: On Productivity: Text Expansion
tags: [Productivity, Scripting, Macros ]
---
![Keys]({{ "/assets/img/keys.jpeg" | relative_url }})
  > If there is anything I hate more than bureaucratic red tape, it is typing the same thing over and over again, day-in and day-out.

If you are a normal professional, many things in your work life remain the same - your email id(s), your email signature, your full name ... and you get the idea. So till mid-2016 I have been doing some things the hard way. I wrote the same few fields in different places by typing it out. Towards the end of 2016, I heard about TextExpander, through a podcast. I was intrigued.

What TextExpander does is brilliantly simple. It expands on small snippets of text of your choice to the actual string of text you wished to type. For example:

```
#gm - expands to my gmail address
#P  - expands to my phone number
#D  - expands to today's date
```
![TextExpander]({{ "/assets/img/texp.jpeg" | relative_url }})
The above image really brings out the features of TextExpander to life. I built networking snippets, where I could fill fields in an expanded text for a particular person/company and send them a customized thank you letter. TextExpander is a great start if you're new to this concept. It has a simple, clean GUI and offers sharing functionality between teams. All in all, a really good ROI for the cost.

***And now the pièce de résistance...***

With some more research inside the Reddit multiverse, I stumbled upon a great replacement for TextExpander. Lo and behold - [AutoHotKey](https://www.autohotkey.com/) ! Autohotkey (AHK for short) does all that TextExpander does and a lot more. I have never come across a tool that is so simple yet so powerful. You can use any notepad-like service to write your code and save the file with a '.ahk' extension and run the script. Easy-peasy.

![ahk]({{ "/assets/img/ahknp.jpeg" | relative_url }})

Not only can I expand small snippets, or fetch system time or date, I can call and run applications by 2-3 keystrokes from any text field. Say I am in browsing in chrome and I need excel. I type '00.' and hit space - BOOM... Excel is opening in the background! How cool is that?! My work laptop does not have a dedicated 'AppsKey' which performs the right click function in Excel. If you're a power user like me, you don't want to use the mouse and do everything from the keyboard. I have used AHK to remap my Right Alt key to function like the Apps Key. I cannot overstate the copious amounts of time I have saved analyzing data in Excel. I almost feel like a wizard performing magic tricks with my clunky old work laptop.

So that is about it when it comes to text expansion. I make use of it a lot and I wanted to share it so that you save some time too. Share some cool applications you are using that boost your productivity.
