## Deployed Application

View the Work Day Time Block Planner at: https://codemasterbrown.github.io/App-Calendar/

## Table of Contents

1. [Description](#Description)
2. [Technologies](#technologies)
3. [Requirements](#Requirements)


## Description

This project is a calendar application that allows a user to plan hourly time blocks in a day. The application displays each hourly block from 9 am to 5 pm and users can save events in each time block. Hourly blocks are color coded: Gray blocks are in the past, red is the present hour, and green blocks are future hours. A clear button allows the user to clear all calendar events from the day.


## Technologies
- HTML
- CSS
- JavaScript
- Bootstrap - https://getbootstrap.com/
- Moment JS - https://momentjs.com/ 

## Requirements

### User Story

```
AS AN employee with a busy schedule
I WANT to add important events to a daily planner
SO THAT I can manage my time effectively
```

### Acceptance Criteria

```
GIVEN I am using a daily planner to create a schedule
WHEN I open the planner
THEN the current day is displayed at the top of the calendar
WHEN I scroll down
THEN I am presented with timeblocks for standard business hours
WHEN I view the timeblocks for that day
THEN each timeblock is color coded to indicate whether it is in the past, present, or future
WHEN I click into a timeblock
THEN I can enter an event
WHEN I click the save button for that timeblock
THEN the text for that event is saved in local storage
WHEN I refresh the page
THEN the saved events persist
```
