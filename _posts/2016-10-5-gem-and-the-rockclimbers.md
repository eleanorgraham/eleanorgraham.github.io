---
layout: post
title:  "Gem and the Rock(climb)ers"
date:   2016-10-5 14:28:12 -0400
categories: learn-log
tags:
- tech
- learn-log
- ruby gems
- hiking
---
# Presenting: Hiking Guide

![hit the trails!](../../images/hit_the_trails.png)

I just finished building a Command Line Interface(CLI) Gem called [Hiking Guide](https://rubygems.org/gems/hiking_guide). It grabs information on hiking trails in the US mid-Atlantic off of [HikingUpward](http://www.hikingupward.com/) and presents that information to the user on the command line.

## But Why?
I’m working through the Flatiron school’s [Learn](https://learn.co/) curriculum, and building a CLI Gem is the final project for the section on Object Oriented Ruby. Coming up with a topic and a site to scrape is all up to us, and I decided to use my beautiful home — the Shenandoah Valley — as inspiration. I don’t really expect anyone else to use my little gem (is anyone besides me really interested in looking up hiking trail details from the command line?). Still, after spending so much time staring at my computer screen, I knew I could really benefit from hitting the trails and that was reason enough for me to proceed!

## Challenges
The web scraping turned out to be much more difficult than I anticipated. HikingUpward is a volunteer organization — this means that the website is maintained by multiple people, and the information presented there is anything but consistent. There were several times that I almost gave up and picked a different topic/project. One particular volunteer in NC added some fancy script to his trail descriptions that required a method all its own to clean up (Hi, Zach! Thanks for the challenge and added hours!) — and I almost decided to just leave NC trails off the list entirely because of this. But I didn’t — I kept at it and figured it out. It’s hard to describe how satisfying that is!

I also challenged myself to write some tests for the first time, which was great fun. It’s a skill I want to develop, but haven’t had the reason to really push myself. Although I don’t have anything close to full test coverage for this project, the few tests I do have are a good step for me (and it leaves me something to come back to and improve!)

## Good Enough
One of the things that keeps me interested in coding is the seemingly endless possibilities for improvement. Once I start thinking about a puzzle I have a hard time putting it down; I keep turning it over and over, polishing, refining. So, although I’m calling this gem ‘ready’ I have ideas for things I could improve, should the time and desire present itself. I also have a bundle of ideas for other projects that I feel ready to take on in the wake of this success. It feels good to say that what I’ve created is good enough and release it into the world.
