Springboard Data Science Career Track Unit 4 Challenge - Tier 3 Complete

# 4. Conclusion
What can you conclude? Type out your conclusion below. 

Looks like the house values in Hackney increased the most between 1995 and 2025: 9.1x as compared to 7.6x for London overall and 5.8x for England. However, if we look at the top 4 Boroughs (plotted above) Southwark increased 8.0x, but the graph is almost superimposable with Hackney. Because of a the way the answer was calculated (Southwark started a tad bit more expensive and trended down slightly AFTER the major price increase) - Southwark is probably a close 2nd (not 3rd as indicated by my calculations).

Look back at your notebook. Think about how you might summarize what you have done, and prepare a quick presentation on it to your mentor at your next meeting.

I have imported the excel, converted it to a Pandas dataframe, transposed the df, reset the index. Then I cleaned up the data: got rid of the blank columns as well as most of the ones that aren't Boroughs. Made sure the data types are correct in the date and price columns. Made a new column with just the year and not the whole date. Finally averaged the house prices for each year and Borough and stored them in a new df. What was then left is just to take a ratio of the average value between 2025 and 1995 prices for each Borough by taking a cross section of the df and find the one with the largest ratio by sorting the results. Finally, I went back to plot the data for the 4 top growing Boroughs: Hackney, Waltham Forest, Southwark, Lewisham.

We hope you enjoyed this practical project. It should have consolidated your data hygiene and pandas skills by looking at a real-world problem involving just the kind of dataset you might encounter as a budding data scientist. Congratulations, and looking forward to seeing you at the next step in the course! 
