# Project Name
> Meditation App!

## Table of contents
* [General info](#general-info)
* [Screenshots](#screenshots)
* [Technologies](#technologies)
* [Code Examples](#code-examples)
* [Features](#features)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info
A meditation style app using HTML, CSS and JavaScript 

## Screenshots
![Example screenshot](https://github.com/TarrMarr/meditationApp/blob/main/screenshot.JPG)

## Technologies
* HTML5
* CSS
* JavaScript  

## Code Examples
Show examples of usage:
`song.ontimeupdate = function() {
  let currentTime = song.currentTime;
  let elapsed = fakeDuration - currentTime;
  let seconds = Math.floor(elapsed % 60);
  let minutes = Math.floor(elapsed / 60);
  timeDisplay.textContent = `${minutes}:${seconds}`;
  let progress = outlineLength - (currentTime / fakeDuration) * outlineLength;
  outline.style.strokeDashoffset = progress;

  if (currentTime >= fakeDuration) {
    song.pause();
    song.currentTime = 0;
    play.src = "play.svg";
    video.pause();
  }
};`

## Features
List of features ready and TODOs for future development
* Timer with moving countdown
* Changable background and sounds
* Clean Outline 

To-do list:
* Wow improvement to be done 1 -> Needs some better scalability and responsiveness  

## Status
Project is: _finished_

## Inspiration
Created alongside: https://www.youtube.com/watch?v=oMBXdZzYqEk

## Contact
Created by TarrMarr(https://www.tarrynmarr.me) - feel free to contact me!
