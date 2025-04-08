# Chrome Extension Idea: CalNow

## Authors

Andrew Lukashchuk

## Problem Statement

Adding things to your calendar is a nuisance that can distract people when working on things. Additionally, its easy to make errors since you have to add the item to your calendar in a new tab and cannot actually view what you are putting on your calendar as you are adding it. It is also a nuisance to think of accurate descriptions and adding details to the item when adding it to your calendar. This extension aims to use LLMs to fill in all the details for something you are viewing on your Chrome tab, as well as adding a brief LLM-generated summary to the description to save time and make the process of adding things to users' calendars easier.

## Target Audience

The target audience includes students who will add things to their calendar often and have busy schedules, professionals who have busy schedules and have new things come up often that they need to keep tabs on, and regular people just browsing their email or viewing events that they would want to add to their schedule easier to keep track of things they have to or want to go to. 

## Description

CalNow is a Chrome extension that provides a single-click solution for adding online content as calendar events. By analyzing the page content, it extracts essential details such as event title, date, time, and description, then automatically populates the calendar event form for a swift entry process.

## Selling Points

1.   One-Click Simplicity
2.   Automatic Detail Extraction
3.   Time Efficiency
4.   External Calendar Support
5.   Verifiable & Customizable Input

## User Stories

1.  As a busy professional, I want a one-click button to add events from any webpage so that I can effortlessly schedule meetings without manual data entry.
2.  As a student, I want the extension to automatically detect event details from academic event pages so that I can quickly add them to my calendar for better schedule management.
3.  As an event organizer, I want to integrate the extension with my Google Calendar so that all my events sync across devices seamlessly.
4.  As a casual browser, I want to be able to customize extracted event details before saving so that I can make any necessary adjustments for accuracy.
5.  As a time-sensitive user, I want an automatic pop-up confirmation after adding an event so that I know my calendar has been successfully updated.

## Notes

Some webpages may not follow a standard format or use images to display data for the events, which would make it more difficult to extract infrmation and populate the calendar with.

## References & Inspiration

-  [Google Calendar Workspace](https://developers.google.com/workspace/calendar) will be required to have the calendar work with Google calendars
-  [Outlook API](https://learn.microsoft.com/en-us/outlook/rest/reference) will be required for integration with Outlook calendars
