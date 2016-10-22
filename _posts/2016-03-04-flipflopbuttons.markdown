---
author: No Content Found
comments: true
date: 2016-03-04 05:46:29+00:00
layout: post
link: /writing/flipflopbuttons
slug: flipflopbuttons
title: To Flip Flop or not? A UX question
wordpress_id: 84
tags:
- Flip flop buttons
- UX
- UI
---

This week I'm cat-sitting for friends who are in Hawaii. The first night I got to the house, I couldn't figure out how to turn the lights on in the kitchen. Each light switch had a rectangular panel that was either glowing or off. I figured that the glowing switches corresponded to the lights that were currently on, and the not glowing switches corresponded to the lights that were currently off.


  
      ![](http://static1.squarespace.com/static/54fcde57e4b07e462fdd69b4/5528a6ace4b0a8996a246af1/56d91f379f726613800bf967/1457069930553/monica.s.houston%40gmail.com.houston%40gmail.com?format=original)
  



 

Of course I was wrong, and ended up turning all of the lights up and standing in the dark. Standing there in the dar, the design finally made sense to me - of course the lights that are turned off have glowing switches - that's so that you can find the switch in the dark! The switches indicate what you want the light to do (turn on), not what it is currently doing. I ran into a similar problem two months ago while doing UX for a Windows Phone 8 App. It was a GPX tracker and it had 4 buttons in the Application Bar: a , a navigation button, a stats button, play/pause/stop recording button, and a settings button. The play/pause/stop recording button turned out to be the one that caused the problems.

After looking at other apps with "play/pause" buttons I realized that in every single one, when you are "playing" the play button is a pause button, and when you are paused, the button turns into the play button. In User Interaction speak, these are called "flip/flop buttons." This brings up an interesting question: should the label on the button define the action you want to perform pushing it or the state that that button represents?

Besides play/pause buttons, I can only think of a few other flip/flop buttons that I regularly encounter. One would be the TweetDeck "follow" vs "unfollow" button (the button on the normal Twitter interface when you are following someone reads "following" and only says "unfollow" if you hover over it.) In fact, an extremely commonly used binary setting,


  
       [caption id="" align="alignnone" width="272.0"]![ok, it's in French but you know what it means...](http://static1.squarespace.com/static/54fcde57e4b07e462fdd69b4/5528a6ace4b0a8996a246af1/56d91fa1f850821330663975/1457069988194/monica.s.houston%40gmail.com.houston%40gmail.com?format=original) ok, it's in French but you know what it means...[/caption] 
  



 

In the UI for "GPX Viewer" I decided to go the route of consistency. Because the play/pause buttons had to show the action you wanted to perform when pushing it, all of the other buttons in the AppBar would have to follow the same rule to avoid confusion. I still felt somewhat uncomfortable with this solution.

In _[About Face 2.0](http://rads.stackoverflow.com/amzn/click/0764526413),_ Cooper and Reimann (2003, pp. 341-2), arguably the experts on Interaction Design, say

<blockquote>"Flip-flop button controls are very efficient. They save space by controlling two mutually exclusive options with a single control. The problem with flip-flop controls is that they fail to fulfill the second duty of every control - to inform the user of their current state. If the button says ON when the state is off, it is unclear what the setting is. If it is OFF when the state is off, however, where is the ON button? Don't use them. Not on buttons and no on menus!"
> 
> </blockquote>

So was I wrong to use flip/flop buttons in the AppBar? The exception, as stated by Cooper and Reimann on page 445, is when the current state is obvious. For instance, if you have one minimize/mazimize button on your browser window, when the current state is maximize the button should read "minimize" because it's clear that the browser is already maximized.

After user testing for 3 years (the app is in the [Windows Phone app store](https://www.microsoft.com/en-us/store/apps/gpx-viewer/9nblggh080t1)), I've received nothing but positive feedback. I take this to mean that I made the correct choice.

 
