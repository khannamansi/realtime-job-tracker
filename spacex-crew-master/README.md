# SpaceX Crew Angular Coding Challenge

Clone the repository and run **index.html** on **live-server** to understand the webpage structure and responsiveness.

Write Angular 9+ code on IDE of your choosing - [StackBlitz](https://stackblitz.com) or [Visual Studio Code](https://code.visualstudio.com/) to meet below requirements:

## Requirements

1. Create new Angular project get SpaceX Crew data from the following REST API: https://api.spacexdata.com/v4/crew
2. Replace the static data from index.html to map to data collected from above REST API. The cards on the page must reduce or grow depending on number of crew data returned.
3. Map Crew "name", "agency", "wikipedia" link and "status" to corresponding location on webpage template. Code must provision for 2 retries to get data from API upon failure.
4. Code must be properly modularized, have unit tests and handle errors gracefully.
