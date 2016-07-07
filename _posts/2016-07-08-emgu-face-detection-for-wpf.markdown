---
layout: post
title:  "Emgu CV Face Detection App for WPF"
date:   2016-07-08 01:02:49 +0800
categories: projects
---
Lately, I've been playing around with Emgu CV's face detection features and it works really well. As I am fond
developing apps for the WPF platform, I made one for it too. I'll try to update this one from time to time,
but please take note that the purpose of this app is to be a "base" app for your Face Detection needs.

Right now, the app has few number of features, here they are:

* Clean Material Design UI
* SQLite Database
* Ability to **Add User** with Name
* Ability to **Take Logs** with Date and Time
* Ability to **Show All Logs** in a list
* Ability to filter all logs
* And written in **MVVM Pattern** for scalibility

Just download the source, fire up the solution and you're good. I'll be adding the ability to edit users in 
the future and view the user's face on the Logs Tab. Meanwhile, take a look at the source on Github or 
view the screenies below.

<a href="https://github.com/zxcdani/EmguFaceDetectionWPF" target="_blank">
    <button type="button" class="btn btn-primary">
        <i class="fa fa-github" aria-hidden="true"></i>
        Source
    </button>
</a>

<div id="screens" class="carousel slide" data-ride="carousel">
    <ol class="carousel-indicators">
        <li data-target="#screens" data-slide-to="0" class="active"></li>
        <li data-target="#screens" data-slide-to="1"></li>
        <li data-target="#screens" data-slide-to="2"></li>
    </ol>
    <div class="carousel-inner" role="listbox">
        <div class="item active">
            <img src="https://raw.githubusercontent.com/zxcdani/EmguFaceDetectionWPF/master/Images/screen1.png" alt="Main Window/Monitoring Tab">
        </div>
        <div class="item">
            <img src="https://raw.githubusercontent.com/zxcdani/EmguFaceDetectionWPF/master/Images/screen3.png" alt="Main Window/Monitoring Tab">
        </div>
        <div class="item">
            <img src="https://raw.githubusercontent.com/zxcdani/EmguFaceDetectionWPF/master/Images/screen2.png" alt="Main Window/Monitoring Tab">
        </div>
    </div>
    <a class="left carousel-control" href="#screens" role="button" data-slide="prev">
        <span class="icon-prev"></span>
    </a>
    <a class="right carousel-control" href="#screens" role="button" data-slide="next">
        <span class="icon-next"></span>
    </a>
</div>