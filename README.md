# DataScience-and-MachineLearning-Portfolio

![image](https://github.com/toluibiwoye/DataScience-and-MachineLearning-Portfolio/assets/72495445/6ecccb20-8935-45bd-8324-4f52cec650d7)

## Table of Contents

- [Introduction](#introduction)
- [Technical Skills](#technical-skills)
- [Education](#education)
- [Work Experience](#work-experience)
- [Project Section](#project-section)
  - [Collibra Implementation at Sunlife](#collibra-implementation-at-sunlife)
  - [QA Testing Across Environments at Sunlife](#qa-testing-across-environments-at-sunlife)
  - [Predicting Football Player Performance Using Historical Data (To be confirmed)](#predicting-football-player-performance-using-historical-data-to-be-confirmed)
- [Additional Section](#additional-section)
- [Reference](#reference)

## Introduction

My passion for data first started with basketball, particularly with the club I support Arsenal. I concluded that data would help me better understand the game in terms of tactics, strategies and player actions. During my data engineering internship at Sunlife, this made much more sense and helped bring my ideas to life. I didn’t know what to expect going in, but it made me fall head over heels for data work.

Looking ahead, I hope to work with data, perhaps for a basketball team. Whether I am working with a basketball team or by myself, I always give it my all. I’m always willing to learn more and delve deeper. 

What makes me unique? Data are stories to me. Every piece of data tells us something different, just like every dish has a unique tale to tell. I think data can link people together and make things plain, much like a meal can.

Arsene Wenger, the legendary arsenal manager once said “The biggest things in life have been achieved by people who, at the start we would’ve judged crazy” I am confident that I am headed towards accomplishing something truly spectacular in the field of data due to my passion and perseverance.


## Technical Skills
•	Languages: HTML5, CSS, JavaScript, Java, MySQL, SQL Databases, C++, Python.  
•	Software: MS Word, Excel, Access, Adobe Development Studio, Cisco Packet Tracer.
•	Data Governance tools: Collibra, Splunk
•	Frameworks & Libraries: Bootstrap, AngularJS, React, Sass.
•	Other skills Git commands, SDLC knowledge, Database Architecture & Optimization, System analysis and design testing

## Education

Institute of Technology, Carlow 	 	 	  	  	  	2019 - Present 
Course: Bachelor of Science (Honours) Software Development – 
Year 4 subjects: Agile software development and verification, Data science, concurrent development. 

Year 3 subjects: Data Structures and Algorithms, Advanced programming, Operating systems, Software Engineering for Web, Cloud and Mobile Apps, Web and Cloud Development.

Year 2 subjects & GPA 60%
Web Programming and Databases, Data Structures and Algorithms, Object Oriented, Systems Analysis and Design Testing, Computer Architecture, Project( SoftwareDev)

Year 1 GPA 63%  
Institute of Technology, Carlow  	  	  	  	  	  
•	Course: Preparation for Higher Education  
•	Certificate: Certificate in Preparation for Higher Education  	2018 – 2019  

Premiere Academy, Lugbe, Abuja, Nigeria  	  	  	  	  
•	 	Second Level Student  	2012 - 2018  

## Work Experience

### Grayscare Support and Logistics LTD	  	  	  	 Jun 2021 – Jul 2021  
#### Position Held: Sales Assistant
#### Duties:   
-	Write a weekly Sales report merging word and excel.
-	Respond and engage physically or through emails and enquiries with customers.
-	Regularly check that all the systems are up to date  
### Sunlife Financial	  	  	  	March 28  – Sept 1st  2022
Position Held: Data Engineer  
 Duties:   
-	Promoted and put into use Collibra, a platform for effective data distribution across Sunlife departments, in collaboration with the data governance team.
-	Handled numerous corporate databases with a focus on data security and accuracy.
-	Reverse engineered stored procedures, simplifying SQL scripts to produce the required information.
-	Ensured data consistency across several environments, including development, QA, staging, and production, as part of my work with the QA team.



## Project Section

### Collibra Implementation at Sunlife

Brief Description:
Development and implementation of the Collibra tool, which enables easy data transfer between Sunlife's departments. The project aims to improve report providing procedures while improving immediate data accessibility.
#### Infrastructure:
- Data Storage: Multiple company databases.
- Platform: Sunlife's internal data platform.
##### Tools & Technologies Used:
-	Data-related tool: Collibra
-	Programming & Scripting: SQL for reverse engineering stored procedures.
-	Data Import/Export: Excel for data transformation before Collibra import.


### QA Testing Across Environments at Sunlife

#### Brief Description:
Quality Assurance (QA) testing that ensures data accuracy and consistency across various platforms. The project ensures easy data flow from development stages to production.
#### Infrastructure:
 -	Data Storage: Sunlife's internal databases (Development, QA, Staging, and Production).
 -	Platform: Sunlife's internal testing platform.
#### Tools & Technologies Used:
 -	Data-related tools: Internal QA tools.
 -	Environment Management: Tools for switching and comparing between Dev, QA, Staging, and Production.


### Comparing different Basketball Player Eras Using Historical Data 

#### [Google Collab Access](https://colab.research.google.com/drive/11xsX1llPt32-5icMyoP_8KPLB0wiwBRe?usp=sharing)

Comparing the excellence of players from different eras is a topic of considerable controversy and curiosity in the ever-changing game of basketball. The game has seen radical transformations in the last 20 years, evolving from the physicality of the 1990s to the pace-and-space age of the present. Through the use of an extensive dataset spanning more than 20 years, we are able to examine and contrast the performance measures of basketball players from various historical periods. This method enables us to analyse the subtleties of the game that are captured by statistics, such as player effect and scoring efficiency, giving the age-old debate of which players stand out historically a quantitative foundation. We seek to provide insights by bridging the gap between various eras of basketball through careful data analysis.

#### Cleaning the Dataset

![Cleaning the dataset](https://github.com/toluibiwoye/DataScience-and-MachineLearning-Portfolio/assets/72495445/509e1b5f-1dc0-40a5-a8ac-92120e40d40b)

The code snippet demonstrates data cleaning steps using pandas in Python. It loads a CSV file containing basketball box score data, prints the first 23 rows to view initial data, and then performs cleaning by removing rows where the 'PER' column is empty, contains a placeholder value "#VALUE!", or where the 'MP' column indicates the player was not available for the game. The cleaned data frame is then printed to confirm the changes.

![Lebron vs MJ](https://github.com/toluibiwoye/DataScience-and-MachineLearning-Portfolio/assets/72495445/2010a398-cb7c-4abd-a707-b157650c970d)

The LeBron vs. Jordan debate is longstanding in basketball circles. However, based on our graph comparing Player Efficiency Rating (PER) and Field Goal percentage (FG%), Jordan emerges as the more efficient player. This data adds a new dimension to the discussion about who truly is the GOAT in basketball.


![Steph vs Stockton](https://github.com/toluibiwoye/DataScience-and-MachineLearning-Portfolio/assets/72495445/cc1e62f7-3182-42ad-8dc0-96f233cef4f8)

The graph compares the shooting efficiency of modern sharpshooter Stephen Curry against traditional playmaker John Stockton. My goal is to compare Curry's high-volume scoring, shown in green, with Stockton's consistency, marked in purple, juxtaposing a modern scorer with an old-school passer. This visual debate mirrors comparisons of past and present basketball point guard styles, as we are seeing the game evolve into point guards taking a lot more shots rather than making plays.

![Best NBA player in each position based on efficiency rate](https://github.com/toluibiwoye/DataScience-and-MachineLearning-Portfolio/assets/72495445/06e409a0-5c90-406c-a8e0-fa5eea301589)

This bar chart showcases the top NBA players in different positions based on their Player Efficiency Rating (PER). From left to right, we see the best performers in positions: Center (C), Power Forward (PF), Small Forward (SF), Shooting Guard (SG), and Point Guard (PG). This sheds a different light on how I now see the game because you may scoring the most points, getting the most assists or racking up the most boards. All does not mean you are efficient it also takes into account how rounded your game is Field percentage, turnovers etc. Some players will have also played more games than others which would bring their efficiency down.

![image](https://github.com/toluibiwoye/DataScience-and-MachineLearning-Portfolio/assets/72495445/080ef785-f73b-49bd-8591-fdf84b386717)

The chart displays the best players from various NBA teams ranked by their Player Efficiency Rating (PER). It spans a wide array of teams with the players' names listed along the bottom. Each vertical bar represents a player's PER, with the highest achievers like Lamar Odom and J.J. Redick standing out. This visual representation serves to compare the top-performing players within their respective teams, providing a clear comparison of individual contributions and impact.

![image](https://github.com/toluibiwoye/DataScience-and-MachineLearning-Portfolio/assets/72495445/5f0a1d57-b4ae-46b3-8350-2c20afe192ec)

This scatter plot compares the Field Goals (FG) and Player Efficiency Rating (PER) between Giannis Antetokounmpo, Tim Duncan, and Kevin Garnett. The horizontal axis measures FG from 0 to 17.5, while the vertical axis shows PER from -10 to 50. Antetokounmpo's data is in purple, Duncan's in orange, and Garnett's in green. The spread and density of the points offer a statistical insight into their performance, contrasting Antetokounmpo's modern dynamism with Duncan and Garnett's consistent excellence over their careers.

![image](https://github.com/toluibiwoye/DataScience-and-MachineLearning-Portfolio/assets/72495445/c24889dd-d842-4d79-98a9-65775c6a6a3f)

The scatter plot illustrates a comparison of Field Goals (FG) and Player Efficiency Rating (PER) between Shaquille O'Neal, represented in red, and Dwight Howard, in green. The horizontal axis displays FGs up to 25, while the vertical axis shows PER up to 40. The distribution of points allows for analysis of both players' performance metrics, offering a visual comparison of two dominant centers from different NBA eras.

![image](https://github.com/toluibiwoye/DataScience-and-MachineLearning-Portfolio/assets/72495445/580e2c6d-1e2c-4293-ac08-1bede3005f9c)

The scatter plot contrasts the Field Goals (FG) and Player Efficiency Rating (PER) of Kobe Bryant, in purple, against James Harden, in orange. Displayed along the horizontal axis are FGs up to 25, and the vertical axis lists PERs from below 0 to above 50. The pattern of dots reflects the scoring prowess and efficiency of two of basketball's elite guards who put up crazy numbers in their prime, allowing for comparison of their performance over their respective careers

![image](https://github.com/toluibiwoye/DataScience-and-MachineLearning-Portfolio/assets/72495445/071771cb-fc46-4465-a034-1d43850de416)


This code illustrates the use of pandas to load a basketball game box score CSV file and matplotlib to plot a scatter plot. It filters the data for players Kobe Bryant and James Harden, converts their 'Player Efficiency Rating' (PER) and 'Field Goals' (FG) to numeric types, and plots these metrics on a scatter plot, with Kobe's data in purple and Harden's in orange. The plot is labeled and titled to compare the FG and PER between the two players.


### Decision Trees and Random Forests

In the updated Jupyter notebook, I've implemented several key changes to the original Decision Tree model to explore different tree complexities, robustness, and overall prediction accuracy. Specifically, I adjusted the max_depth parameter to 10 to allow the tree to capture more complex patterns in the data, and set min_samples_leaf to 4 to reduce overfitting by ensuring that leaf nodes have a sufficient number of samples. The splitter parameter was changed to 'random' to introduce more variability in the tree structure, which can sometimes lead to better generalization on unseen data. Moreover, I've introduced a new accuracy evaluation step after predictions to quantify model performance more precisely. These modifications are part of a broader exploration to see if we can improve the algorithm's performance or make it behave differently for varied datasets or under different constraints.

[Original Notebook](https://colab.research.google.com/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/05.08-Random-Forests.ipynb)
[Edited Notebook](https://colab.research.google.com/drive/1_K5YgGix_L-_YWfbJ72wZ6nabAQNzEme#scrollTo=mSgqsRFijmeR)

![image](https://github.com/toluibiwoye/DataScience-and-MachineLearning-Portfolio/assets/72495445/6a422e88-7a3f-43d6-bca9-e970aef114b3)
### Original

![image](https://github.com/toluibiwoye/DataScience-and-MachineLearning-Portfolio/assets/72495445/825ff2e1-33e0-4104-8388-a1c61d948a44) ![image](https://github.com/toluibiwoye/DataScience-and-MachineLearning-Portfolio/assets/72495445/5b103c20-e6a7-4162-b13d-b6da773fa3d0)
### Edited

![image](https://github.com/toluibiwoye/DataScience-and-MachineLearning-Portfolio/assets/72495445/400657ee-95f4-4d5d-a0b2-acc68b99470f)
### Original

![image](https://github.com/toluibiwoye/DataScience-and-MachineLearning-Portfolio/assets/72495445/824126d8-ed56-4291-9deb-c81e1644d818) ![image](https://github.com/toluibiwoye/DataScience-and-MachineLearning-Portfolio/assets/72495445/029afe3a-3e77-474b-b2d0-82b79410a080) ![image](https://github.com/toluibiwoye/DataScience-and-MachineLearning-Portfolio/assets/72495445/1ef403d8-20e7-45a4-bab5-4c7a74ef9e51)
### Edited

## Additional Section

ACHIEVEMENTS:  
• Selected by U.N. to be Director (Data Specialist) of NISSMUN in 2017
• Cisco Academy Certificate

Blog  
• My Journey with Collibra at Sunlife

## Reference

- [Machine Learning Frameworks](https://hackr.io/blog/machine-learning-frameworks)
- [Better Storage Options Than CSV Files](https://towardsdatascience.com/csv-files-for-storage-no-thanks-theres-a-better-option-72c78a414d1d)
- [Premier League News](https://www.premierleague.com/news/67261)
- [Data Visualization Tools](https://www.toptal.com/designers/data-visualization/data-visualization-tools)
- [Data Science Portfolio Guide](https://www.springboard.com/blog/data-science/data-science-portfolio/#:~:text=A%20data%20science%20portfolio%20should,you%20think%20about%20problem%2Dsolving.)
- [Understanding Simple Linear Regression](https://towardsdatascience.com/deep-understanding-of-simple-linear-regression-3776afe34473)
-  [NBA Dataset](https://www.kaggle.com/datasets/patrickhallila1994/nba-data-from-basketball-reference?select=boxscore.csv)
-  [CHAT GPT]
-  [Jupyter Notebooks](https://www.alphr.com/vs-code-open-jupyter-notebook/)
-  [ Idxmax method](https://www.w3schools.com/python/pandas/ref_df_idxmax.asp#:~:text=The%20idxmax()%20method%20returns,maximum%20value%20for%20each%20row)
-  [groupby function](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.groupby.html)
-  [pandas](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.idxmax.html)
-  [pandas](https://www.geeksforgeeks.org/python-pandas-dataframe-groupby/)
-  [Decision Trees](https://learn-eu-central-1-prod-fleet01-xythos.content.blackboardcdn.com/60d4531e78936/4503126?X-Blackboard-S3-Bucket=learn-eu-central-1-prod-fleet01-xythos&X-Blackboard-Expiration=1700838000000&X-Blackboard-Signature=%2ByGCz0Ll3hinFwxcIrBrXfpPvMjS1Gjfrbz9WetD7as%3D&X-Blackboard-Client-Id=680538&X-Blackboard-S3-Region=eu-central-1&response-cache-control=private%2C%20max-age%3D21600&response-content-disposition=inline%3B%20filename%2A%3DUTF-8%27%27Chapter%25208%2520Data%2520Science%2520Decision%2520Trees.pdf&response-content-type=application%2Fpdf&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAAaDGV1LWNlbnRyYWwtMSJHMEUCIQDeAxP0UVS3BR8lwnJ%2F%2B6YTu%2FEerkgMFh92EZ2yo2vrxwIgOwLXHPnD1CggIXzjpJKvfI8gs%2FhU7bMY%2BmTtWarPzkUqvgUIWRADGgw2MzU1Njc5MjQxODMiDJNkHMmE%2B74YiZBBPyqbBXSafN6KqIUKw%2Fvc%2FjU9EovbwdZ6gKKSMJz0cqwciJM3u7fqSkam8%2BAxvphCgQCyDHmvdyCw%2FPIm8ivlN%2F1Bhn2VKtbhSJkMi0Wl55RYT8hkGDNCzM2inBbjkrGUABXRRRptwtAjV3StJsagpG3doid%2FmRaFVT4jiMry9wgUvRh3FO%2BzAR1ihyKRYI8hSkFU7s2CU1Str7wYPRmLZx67q9dWnM%2BiUHiAkSUM25ZNmoTKZmqzg3Tb4Zj18iZOHcNuEtmYZyM%2BZDQXVx80QBFD3bahma2Ck6YEZUEQVlr7FrSdZSNMb9YPk4jEDm17y4hU0qCafyPJ%2BDMyDOuTKU0tIie813PhJ1JLWafPesPtV9FekxeBEMivBAFK9xLfohzwOe2BqBcpm8nOX5a%2FK4YcBdtvyndq%2FxwuG2DOxRLK66jwjanL7mJviwlql2AbLAznTHgNCrxOdtB0L7LtrmTpFtFTVG%2BRvEAPFhv6Ppg7zpxa6AeXNLoKOGMacRkJhoKsXUDhZler2wh3gfw3vxFRpAuH%2BkbNiezjXp2viXG7lPDSLKA6e8Jm7ceoE5LeWNiO4TNrc3yL0dcXi7RVGr7OrKxE4TPscZysUxtQ61Tjhf8GgQ%2BYTga9yv2blqVhKLq4pvyX4%2BW8NvyNhEVNZbPluUfZZD84DTz%2BEcdC%2FPfPZ%2FJ4TjjL8GAZpe8AQTRidpFWZVrlyaKHcILjbAbRRQxiiIvahyR4TV0po1i%2FpSMMWJ0byjoTKpfxhlULfm7BMugticS0LvMbY%2Bafp44E9kb%2FvjPUh9vXeqNu3TOXEk%2BRD0wWR6tJSRcDMpVGbS%2BNKrauwG1EHBZrnpodPO4biq6u0%2BIjAkHyzsqcl%2Fd0%2FIahpdNR4%2BVaQaQLDh5iGkgwkrOBqwY6sQH2XfixgAW9e9SLjm7ODfVcDgnYRjoM%2FUUH3Kr6pmRkX4W9j6VJ61TQztBwxws0b5UIluC%2BMWUdoheeFbeDUPD%2FOBfVZLzpdUJQIbJl3EVUenReflG6ztlMTPx%2FRjP4a%2Fvq8yGZxEZS1jxvRCf7PNYOmwY4hEYzVG6jbJfWcPEZadgPOaQ3Jr2EKH3DBDCOh1e1KMe2vWh%2Bu5a1dcWPHUqkAx7MfkuCtd3BJjJVCVVRRDg%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20231124T090000Z&X-Amz-SignedHeaders=host&X-Amz-Expires=21600&X-Amz-Credential=ASIAZH6WM4PLW7546ONS%2F20231124%2Feu-central-1%2Fs3%2Faws4_request&X-Amz-Signature=ff743d4333fb3c93efd2b73327db53dd06922bc44ec60925f326de47b4337dd6)
-  [Random Forests Notebook](https://colab.research.google.com/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/05.08-Random-Forests.ipynb)
-  [Scikit](https://scikit-learn.org/stable/)

Contact Information:
- Catherine Moloney, Lecturer - [catherine.moloney@itcarlow.ie](mailto:catherine.moloney@itcarlow.ie)
- Dale Egan, Sunlife - [dale.egan@sunlife.com](mailto:dale.egan@sunlife.com)


