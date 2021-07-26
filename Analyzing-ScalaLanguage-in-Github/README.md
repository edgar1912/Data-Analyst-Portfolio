# The GitHub History of the Scala Language

Technology: Python

Topics covered in this project:

* Data Manipulation
* Data Visualization
* Importing and Cleaning Data

## Project Description

With almost 30k commits and a history spanning over ten years, Scala is a mature programming language. It is a general-purpose programming language that has recently become another prominent language for data scientists.

Scala is also an open source project. Open source projects have the advantage that their entire development histories -- who made changes, what was changed, code reviews, etc. -- are publicly available.

I am going to read in, clean up, and visualize the real world project repository of Scala that spans data from a version control system (Git) as well as a project hosting site (GitHub). We will find out who has had the most influence on its development and who are the experts.

## Project Tasks

1. Import Scala's real-world project repository data
2. Preparing and cleaning the data
3. Merging the DataFrames
4. Is the project still actively maintained?
5. Is there camaraderie in the project?
6. What files were changed in the last ten pull requests?
7. Who made the most pull requests to a given file?
8. Who made the last ten pull requests on a given file?
9. The pull requests of two special developers
10. Visualizing the contributions of each developer

## Dataset

The dataset we will use, which has been previously mined and extracted from GitHub, is comprised of three files:

* pulls_2011-2013.csv contains the basic information about the pull requests, and spans from the end of 2011 up to (but not including) 2014.
* pulls_2014-2018.csv contains identical information, and spans from 2014 up to 2018.
* pull_files.csv contains the files that were modified by each pull request.

### Notes

The dataset was downloaded from Kanggle, and the project tasks were provided by Datacamp.
