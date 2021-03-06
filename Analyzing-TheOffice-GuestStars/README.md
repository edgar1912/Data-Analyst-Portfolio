# Investigating guest stars in The Office

Technology: Python

Topics covered in the project:

+ Data Manipulation
+ Data Visualization

## Project description

In this notebook, I will take a look at a dataset of The Office episodes, and try to understand how the popularity and quality of the series varied over time. 

## Questions and tasks for the project

* Scatter plot of data that contains the following attributes:
  * Episode number
  * Episode viewership
  * A color scheme reflecting the scaled ratings of each episode
* Name of the guest stars who was in the most watched Office episode?

## Dataset

This dataset contains information on a variety of characteristics of each episode. In detail, these are:

datasets/office_episodes.csv
* episode_number: Canonical episode number.
* season: Season in which the episode appeared.
* episode_title: Title of the episode.
* description: Description of the episode.
* ratings: Average IMDB rating.
* votes: Number of votes.
* viewership_mil: Number of US viewers in millions.
* duration: Duration in number of minutes.
* release_date: Airdate.
* guest_stars: Guest stars in the episode (if any).
* director: Director of the episode.
* writers: Writers of the episode.
* has_guests: True/False column for whether the episode contained guest stars.
* scaled_ratings: The ratings scaled from 0 (worst-reviewed) to 1 (best-reviewed).

### Notes

The dataset was downloaded from Kanggle, and the project tasks were provided by Datacamp.
