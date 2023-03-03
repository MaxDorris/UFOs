# UFOs

## Overview
### Purpose and Background
This project served to introduce myself with the fundamentals of creating web-based visualization tools. Using HTML, CSS, and Javascript I created a list of UFO sitings that allows users to filter by several criteria.

### Functionality
To use the filter function, simply input values into the boxes in the given formats (example search below).

<p align="center">
  <img width=auto height="500" src=static/images/filter.png>
  </p>

The search results will narrow if any records match the inputs (example results below).

<p align="center">
  <img width=auto height="200" src=static/images/results.png>
  </p>

### Conclusion
One drawback with the current search design is that input data must exactly match the data within the table to retrieve accurate results. This could be fixed in two ways.

The first fix would use Regular Expression to allow more leniancy in the table output. Some examples are: the date searchbox accepting dashes or period formats in place of slashes, all leter entries allowing capital and lowercase letters, and partial entries for both dates and letter entries updating as they are typed (in case only the month in the date is known, for example, OR if someone is unsure about the spelling of a city).

The second fix would be to provide pre-filled expanding menus for each criteria that allow the user to scroll through all possible values for each column and select which ones are visible in the resulting table. This would be the best option if a user wants to simultaneously view multiple values for the same criteria.