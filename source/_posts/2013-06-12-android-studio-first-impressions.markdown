---
layout: post
title: "Android Studio - First Impressions"
date: 2013-06-12 13:16
author: <a href="https://twitter.com/jubaborgohain">@jubaborgohain</a>
comments: true
categories: Android AndroidStudio
---
For an app we are developing for the android platform, I wanted to prototype a camera with some custom controls and an overlay instructing the user what to do. Instead of using Eclipse I decided to give Android Studio a try. 

First for some keyboard shortcuts (OSX):

1. ctrl-r -- to run the application.

2. ctrl-d -- to debug the application. Thankfully you don’t have to switch perspectives.

3. shift-cmd-F9 -- to compile the application. 

Some things that I like over Eclipse...

You don’t have to remember which methods to override or go to a separate view to see the methods to override. Say for instance you want to override the onResume() method in your activity. Just start typing “onRes...” and you will see

{% img center /images/2013-06-12-android-studio-first-impressions/on_resume.png %}

Press enter and you are done:

{% img center /images/2013-06-12-android-studio-first-impressions/on_resume_done.png %}

Suppose you are missing an import for a namespace, you can hit option-enter to quickly add it without having to lift your hand to use the trackpad. And for someone who wants to do more with the  keyboard, this feature is really handy. 

Something even better is the awareness that Android Studio has about its context. So, if my goal is to get the camera parameters, Android Studio will actually show me the appropriate method to call at the top of the list.

{% img center /images/2013-06-12-android-studio-first-impressions/get_parameters.png %}

Yet another awesomeness is the ability to just use Ctrl-R to run the app from a layout file. In Eclipse, I always had to chose the activity if I was in a layout file. 