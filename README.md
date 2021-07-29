# COVID_tracking_project_retrospective
 Testing Matplotlib animation with COVID data

In this project, I've used Matplotlib to build a COVID data visualization. It's a pretty busy graph, since I was trying out a variety of things. For a more practical visualization, I'd trim down the amount of information presented. It was an interesting exercise, though, and serves as a retrospective on the COVID Tracking Project, a volunteer group that compiled the most complete and accurate data available about COVID in the US in its early months, when the federal government was not moving rapidly to catalog its spread.

The goal of the visualization is to show how COVID has spread in individual states. The graph organizes states from smallest to largest in population, spaced out across the X axis in proportion to the population of the state. Each state is represented with a circle, which has varying size, color, and Y position. The Y position shows the total fraction of the state that has tested positive since the beginning of the pandemic; the size of the circle shows the total number of positive tests in the past month; the color of the circle shows the number of people per million that have tested positive in the last week. These variables overlap, so you can predict a change in shape based on a change in color, and a change in position based on shape (and to a lesser extent color). There is also manual commentary added, to point out important events in the course of the pandemic. 

I initially updated this visualization to its final version in May, following the last update of the COVID tracking project, and at the time I hoped it would also be a good view of the final stages of uncontrolled spread in the US. Thanks in part to the Delta variant, though, it's not looking great as I publish this in late July.
