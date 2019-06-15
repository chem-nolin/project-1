# Project 1

OUTLINE OF PRESENTATION:
Our Question and Motivation
Where we got our data and how we used it to answer our questions
Data Exploration and Cleanup in Jupyter
Analysis - Show Jupyter Notebook
Conclusions drawn from data - show charts/visualizations
Implications of our Findings - Limitations of Data Used
Open-ended -- what our data "means"

REQUIREMENTS FOR PRESENTATION:
The questions you and your group found interesting, and what motivated you to answer them
Where and how you found the data you used to answer these questions
The data exploration and cleanup process (accompanied by your Jupyter Notebook)
The analysis process (accompanied by your Jupyter Notebook)
Your conclusions. This should include a numerical summary as well as visualizations of that summary
Discuss the implications of your findings. This is where you get to have an open-ended discussion about what your findings "mean".

PROJECT REQUIREMENTS:

Use Pandas to clean and format your data set(s)
 Create a Jupyter Notebook describing the **data exploration and cleanup** process
 Create a Jupyter Notebook illustrating the **final data analysis**
 Use Matplotlib to create a total of 6-8 visualizations of your data (ideally, at least 2 per "question" you ask of your data)
 Save PNG images of your visualizations to distribute to the class and instructional team, and for inclusion in your presentation
 Optionally, use at least one API, if you can find an API with data pertinent to your primary research questions
 Create a write-up summarizing your major findings. This should include a heading for each "question" you asked of your data, and under each heading, a short description of what you found and any relevant plots.


June 10th Tasks:
Kristine:
Figure out top authors - overall from Authors 1-5


Carol:
Normalize sentence case for First authors
see if I can figure out % of total publications for each
Plot those on Bar Graph
Incorporate Author Image to PowerPoint
==============================================================================


JUNE 8th:
Kristine:
Figure out top 10 authors per year
Overall top 10 authors - per # of publications


Carol:
Combined notebooks for MASTER charts/data
Outline presentation contents
Draft PowerPoint - images/contents


JUNE 3:
CrossRef - Affiliation - over 6 million records with University of Richmond.
Issues: not all actually included University of Richmond in areas that reflected UR faculty, and in a DOI check, UR wasn't showing up for all DOIs that actually were from UR.
Used Web of Science - database to focus on UR publications - provides a fast save of up to 5k records at once. 
Saved as csv file to use in Jupyter to query.
Cleaned up data in Excel for csv before importing to Jupyter:
Deleted unnecessary columns
Text to columns to separate individual authors into separate columns
Standardizing the publication date format
Identify Author number - narrowing Authors 1-6 for further analysis (some disciplines have over 100 authors)

Kristine
Emailing Institutional Effectiveness to get a list of faculty and departments since 1975 to cross-reference with our list of authors for further analysis.

Research Questions:
How many...
UR publications - Determine that from Web of Science search - 4708
Titles of Unique Journals?
Articles per journal?
Per journal breakdown: individuals, department, and frequency
Per department? Per faculty?


Carol
Work on finding documentation to help with future searches to answer our research questions:
Document keys and relevant search parameters for above research questions.

So far - useful discoveries to discuss and make visuals for:
CrossRef overview - what it is and what it includes - why we chose this instead of Web of Science or another one...
Affiliation - what that means and the challenges of discovery for a name like Richmond
how to unpack the API results
Identifying an individual item, such as journal, etc..make visual of how publication has grown

FOR NEXT CLASS:
Cleanup Dataframes
Figure out what data we need to actually use in presentation
Great graphs for dataframes used
Work on author-department correlation - depending on what we find out - HOW?
REVISED - Kristine -- working from data to identify top authors


