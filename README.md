# My-Work-Day-Scheduler

## Description

Workday Scheduler App designed to help schedule and save activities throughout the day. The App was designed with HTML and CSS dynamically powered by a jQuery library. Date & Time features are powered by day.js.

## Acceptance Criteria

- GIVEN I am using a daily planner to create a schedule
- WHEN I open the planner
- THEN the current day is displayed at the top of the calendar
- WHEN I scroll down
- THEN I am presented with timeblocks for standard business hours
- WHEN I view the timeblocks for that day
- THEN each timeblock is color coded to indicate whether it is in the past, present, or future
- WHEN I click into a timeblock
- THEN I can enter an event
- WHEN I click the save button for that timeblock
- THEN the text for that event is saved in local storage
- WHEN I refresh the page
- THEN the saved events persist

## Work Completed

- Imported starter code with libraries including jQuery, bootstrap, awesomefonts, googleapis, and day.js
- Set basic styling to HTML elements
- Created time blocks by hourly basis to represent hours of the workday
- Created function to identify time blocks and color-code by past, present, and future tense.
- Created function to refresh color based on time of the day it currently is
- Created function to recognize and save text entries into local storage, even when page is refreshed 
- Created function to implement day.js for 'real-time' date & time input

## Website Link

https://jalarcon95.github.io/My-Workday-Scheduler/

## Screenshot

![screenshot](/assets/images/_Users_jalar_bootcamp_My-Workday-Scheduler_index.html.png)