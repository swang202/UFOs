# UFOs

### Overview of Project

The goal of this project is to provide easily find information about UFO Sightings using JavaScript and HTML.

### Results: 

We first created an introduction of the project in HTML.

![Intro_image](https://github.com/swang202/UFOs/blob/main/static/images/intro_page.png?raw=true)

We used JavaScript to created filter tables in HTML. By typing filter information in the placeholder, the data table on the right will automatically update.

![Filter_table](https://github.com/swang202/UFOs/blob/main/static/images/filter_table.png?raw=true)

### Summary

Although this html provide a good tool to filter data for tailored imformation, there are some drawbacks might hurt the user experiences.

First, user must know the exact key values for filtering data. For something like "shape", it take some effort to guess the correct word to describe the shape in mind. 

Second, when entering the filter value, it's case sensitive. For example, if the users would like to look at the data from California, they can only use "ca" which is not a common way to indicate state and there won't be any data for "CA". So we recommand to fix the input to be more generalizable.

Third, when filtering date, users can only select a specific day but not the data for a period of time, for example, January of 2021 instead of 1/1/2010 only. We also recommand to add in this feature to improve our html.
