---
title: The dreaded front end framework
author: Cathy Dutton
layout: post
category: post
---
As a Front End Developer I am reluctant to use a framework on any of my web projects. I have spent a lot of time looking at the various options including things like Bootstrap and Foundation.

I guess one reason for this is that I&#8217;m protective of my code and my projects, I want to write the code myself and ensure it&#8217;s as compact and as scalable as possible.

<h2 class="heading">What&#8217;s The Problem?</h2>

Front End Frameworks often take away too much of the decision making process including things like grid systems, naming conventions, style guides and scripts with the aim of making the development quicker and simpler.

This can cause a few issues such as&#8230;

**Bloat** &#8211; The included files and CSS are not always utilised. It can be time consuming to go through and remove un-necessary code, especially if it has been written by someone else. Leaving all the excess selectors, mixins and jQuery plug-ins can add weight to a site and make it more difficult to maintain in the future.

**Template Sites** &#8211; A lot of frameworks have styles pre-defined for key elements such as buttons, form elements and banners. If left alone sites are left with a distinct look and feel to them.

**Scalability **- The front end architecture of a site can be key to how easy it is to maintain and build upon in the future. Using an already written set of selectors may create problems further down the line especially if they are not relevant or semantic.

<h2 class="heading">Solution</h2>

Having start up files can be helpful and having a folder structure already in place will speed up any project build. Links to essential files such as the favicon and apple touch icon can also be included in a template HTML file.

These files though should be structural only, setting out the project and removing the need to re-write code and create numerous files. No specific CSS or JavaScript should be included, just a simple CSS re-set and Js Library&#8217;s such as jQuery and Modernizer. All other files should be left blank to be added to as and when required.

Some good examples of this are <a href="http://html5boilerplate.com/" title="HTML 5 Boilerplate" target="_blank">HTML 5 Boilerplate</a> and <a href="http://getfireshell.com/" title="Fireshell " target="_blank">Fireshell</a>.

Both of these examples provide everything needed to quickly get up and running with a new development project without the need to run through and remove any unwanted functionality, scripts or styles.

The two examples above give complete creative control the user, allowing them to define their own unique website. Projects built using these start up&#8217;s can be tailored to suit any project.

<h3 class="heading">Roll Your Own</h3>

The best solution however would be to create a file structure and way of working that suits you. Creating your own workflow and boilerplate allows you to go into much more detail and to tailor each mixin or placeholder to the exact needs of your project.
