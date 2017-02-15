# Melissa Bica Project 0: Visualizing Anscombe's Quarted
## INFO 5602 Information Visualization
Collaborators: Jennings Anderson

### Bells and Whistles
* **Tooltips:** All the graphs have tooltips that provide the x and y coordinates for the selected mark (bar or point).
* **Styling:** I chose a jewel tone color scheme, and added a mouseover color to all the marks (bars and points). (The click interaction, Part 4, is also implemented on all the visualizations.)
* **Best Fit Lines:** I added a best fit line to each of the small scatterplots in Part 5.
* **Transitions:** I added a button that allows the user to choose which of the four Anscombe's datasets to map to both the bar chart and the single scatterplot. There is a very quick D3 transition.
* **Replication:** I replicated the bar chart and the scatterplot for Anscombe's I dataset in Google Sheets. I imported the CSVs, and also added a column for the index to be able to have labels along the x-axis of the bar chart. I could only put all labels along the x-axis rather than having only even values labeled as in the D3 implementation. There was only a limited number of color options, so I could not specify the exact hex shade of purple that I used in the D3 implementation. The best fit line on the scatterplot was a simple addition in a menu, and I did not need to calculate anything, which was much simpler than in D3. Oddly, I could not get the left axis to appear in the Sheets implementation. Overall, building these visualizations in Sheets was much simpler, but does not allow for as much customization in terms of interaction.

### Online Sources
I used code from online sources in two places. For adding the best fit lines, I referenced https://bl.ocks.org/ctufts/298bfe4b11989960eeeecc9394e9f118 and used the ```create_data``` function and a small piece of code to create the variable for the best fit line to be added to the svg. I also referenced https://www.w3schools.com/howto/howto_js_dropdown.asp for making a nicely formatted dropdown menu for selecting the Anscombe's dataset. I used the JS functions almost exactly as provided, and used the HTML and CSS with many changes.
