# New_Yourk_CitiBike_Analysis
Module 18 (Tableau) Challenge 
Solution : https://public.tableau.com/app/profile/pinal.mistry/viz/MyFirstViz1_17014089526980/Dashboard1?publish=yes

Before You Begin
Save this assignment to your Tableau Public account rather than GitHub.

If you haven't already, make sure to create a Tableau Public accountLinks to an external site..

The free tier of Tableau only lets you save to their public server. So, each time you save your file, it will be uploaded to your Tableau Public profile.

You can load and continue working on the same workbook.

When you finish your assignment, you will submit the URL to your Tableau Public workbook along with any additional files used in your analysis.

Files
You will be selecting files to download from the Citi Bike DataLinks to an external site. source, as described in the following instructions.

NOTE
Do not download every zip file available, as combining this much data will cause issues in Tableau. 1-3 zip files should be sufficient to meet the challenge requirements. Tableau restricts data file size to 1GB.

Note also that the data structure has changed over time, so it may be simpler for you to select data that uses the same columns across multiple files, preferably from within the past year.

Instructions
Your task in this assignment is to aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena.

Design 2–5 visualizations for each discovered phenomenon (4–10 total). You may work with a timespan of your choosing. Optionally, you can also merge multiple datasets from different periods.

The following are questions you may wish to answer. Do not limit yourself to these questions; they are suggestions for a starting point. Be creative!

How many trips have been recorded in total during the chosen period?

By what percentage has total ridership grown?

How have the proportions of short-term customers and annual subscribers changed?

What are the peak hours when bikes are used during the summer months?

What are the peak hours when bikes are used during the winter months?

Today, what are the top 10 stations in the city for starting a journey? Based on data, why do you hypothesize these are the top locations?

Today, what are the top 10 stations in the city for ending a journey? Based on data, why?

Today, what are the bottom 10 stations in the city for starting a journey? Based on data, why?

Today, what are the bottom 10 stations in the city for ending a journey? Based on data, why?

How does the average trip duration change by the type of user? (This may be under "User Type" or "member_casual" depending on the period the data is from).

What is the average distance in miles for a bike trip?

Which bikes (by ID) are most likely due for repair or inspection in the timespan?

How variable is the utilization by bike ID?

Use your visualizations (not necessarily all of them) to design a dashboard for each phenomenon. The dashboards should be accompanied by an analysis explaining why the phenomenon may be occurring.

Create one of the following visualizations for city officials:

Basic: A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey, with zip code data overlaid on top.

Advanced: A dynamic map that shows how each station's popularity changes over time (by month and year). Again, with zip code data overlaid on the map.

The map you choose should also be accompanied by a write-up describing any trends that were noticed during your analysis.

Create your final presentation:

Create a Tableau story that brings together the visualizations, requested maps, and dashboards.

Ensure your presentation is professional, logical, and visually appealing.

Considerations
Remember, the people reading your analysis will NOT be data analysts. Your audience will be city officials, public administrators, and heads of New York City municipal departments. Your data and analysis need to be presented in a way that is focused, concise, easy to understand, and visually compelling. Your visualizations should be colorful enough to be included in press releases, and your analysis should be thoughtful enough to inform programmatic changes.

Assessment
Your final product will be assessed on the following metrics:

Analytic Rigor

Readability

Visual Appeal

Hints
You may need to get creative with how you combine each of the CSV files. Don't just assume Tableau is the right tool for the job. At this point, you have a wealth of technical skills and research abilities. Dig for an approach that works, and go with it.

Don't assume that the CSV format hasn't changed since 2013. Subtle changes to the formats in any of your columns can interfere with your analysis. Ensure that your data is consistent and clean throughout your analysis. (Hint: Start and End Time change at some point in the history logs).

Consider building your visualizations with small extracts of the data (like single files) before attempting to import the whole thing. What you will find is that importing all 20+ million records of data will create performance issues quickly. Welcome to "Big Data."

While utilizing all of the data may seem like a nice power play, consider the time course in making your analysis. Is data from 2013 the most relevant for making bike replacement decisions today? Probably not. Don't let overwhelming data fool you. Ground your analysis in common sense.

Remember, data alone doesn't answer anything. You will need to accompany your data visualizations with clear and directed answers and analysis.

As is often the case, your clients are asking for a LOT of answers. Be considerate about their “need to know” and the importance of not "cramming in everything.” Of course, answer each question, but do so in a way that is organized and presentable.

Since this is a project for the city, spend the appropriate time thinking through decisions on color schemes, fonts, and visual storytelling. The Citi Bike program has a clear visual style. As a suggestion, look for ways to have your data visualizations match their aesthetic.

Pay attention to labels. What exactly is "time duration?” What's the value of "age of birth?” You will almost certainly need calculated fields to get what you need.

Look for obvious outliers or false data. Not everyone who signs up for the program is answering honestly.

In answering the question of "why" a phenomenon is occurring, consider adding other pieces of information, like socioeconomic or geographic data. Tableau has a map "layer" feature that you may find helpful.

Don't be afraid to manipulate your data and play with settings in Tableau. Tableau is meant to be explored. We haven't covered everything that you’ll need—so keep an eye out for new tricks!

Treat this as a serious endeavor! This is an opportunity to show future employers that you have what it takes to be a top-notch analyst.