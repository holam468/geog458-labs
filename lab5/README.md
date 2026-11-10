## Study area and dates
I chose to focus on vessel traffic around waterways near Seattle in Washington State, using data from 1/3/23 to 1/4/23. I chose this area because I am familiar with Seattle and wanted to better understand how different types of vessels move through the surrounding waterways.

I selected a relatively small study area of around 75 square miles and limited the data to two days to keep the dataset manageable. I converted the  CSV file to JSON using google colab so it could be used in an interactive map. The original timestamps are in UTC, while the map displays the time in Seattle's local time zone (PST).

## Interpretation
I noticed the 3 different types of vessels have different movement patterns around my study area. Passenger vessels with 23 paths had the most selected paths, followed by cargo vessels with 18 and tankers with only 2. 

One of the most noticeable patterns was that passenger vessels followed more  defined routes. For instance, several paths are shown consistently sonnecting two areas, suggesting that passenger vessels regularly travel in between these locations. In comparison, cargo vessels had fewer long routes visible. Tankers had the least selected paths, and their movements were much less noticeable on the map.

The time slider in particular made it easier to understand how vessel activity changes throughout the day. Rather than showcasing all vessel movements at once, the animation allowed me to focus on the routes during a particular period. The filters also helped separate different vessel types and made their movement patterns easier to compare. Overall, I think these features make the map easier to understand vessel activity than a static map showing all the routes together.

## Feature proposal for a potential user
I propose a feature that'd allow users to click on each vessels to view detailed information, like their vessel type, name, speed, and location. I think this feature would be particularly useful for people who constantlly needs to monitor vessel movements and identify areas with high traffic in case sudden accidents happen. While the current map allows users to filter different vessel types and observe their movements over time, it does not provide much information about individual vessels.

When a user click on a vessel, a popup would appear, allowing users to analyze specific vessels without having to look through the entire dataset. 