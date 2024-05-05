# Investigating Netflix Movies

![Netflix Logo](netflix.logo.png)

## Overview
This project explores the trends in the duration of movies available on Netflix, aiming to determine whether there's a discernible pattern of movie lengths changing over time. Utilizing a dataset containing information about various Netflix shows, including their release year and duration, we investigate the hypothesis that movie durations are decreasing.

## Data
The dataset (`netflix_data.csv`) includes the following columns:
- `show_id`: ID of the show
- `type`: Type of show (movie or TV show)
- `title`: Title of the show
- `director`: Director of the show
- `cast`: Cast of the show
- `country`: Country of origin
- `date_added`: Date added to Netflix
- `release_year`: Year of Netflix release
- `duration`: Duration of the show in minutes
- `description`: Description of the show
- `genre`: Show genre

## Methodology
We start by preprocessing the data, filtering out TV shows and creating a subset of relevant columns. Then, we examine the distribution of movie durations over the years, plotting a scatter plot to visualize any potential trends. Additionally, we categorize movie genres and assign colors accordingly to identify any patterns in the data.

## Results
Contrary to the initial hypothesis, the analysis suggests that there's no significant evidence to support the claim that movie durations on Netflix are decreasing over time. The scatter plot demonstrates a varied distribution of movie lengths across different years, with no clear trend of decreasing durations.

## Conclusion
Based on the analysis, we conclude that while there may be fluctuations in movie durations over the years, there's insufficient evidence to confirm a consistent decline in movie lengths on Netflix. Further research and analysis could explore additional factors influencing movie durations and provide deeper insights into the dynamics of the entertainment industry.
