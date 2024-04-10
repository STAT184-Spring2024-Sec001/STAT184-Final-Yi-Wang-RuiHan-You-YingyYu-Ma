# Stat 184 - Xinyue Wang (Spring 2024) Final Project

This repo will serve as the template file for the course project. Further, this README file will contain the project specifications (details), check points, and the list of learning outcomes being assessed. Be sure to read through all portions of the README carefully.

## Project Purpose

The purpose of this project is to provide you with an opportunity to put into practice *everything* that you have learned over the course of the semester and to push yourselves. To this end, you'll be posing your own research question(s) which you'll use to guide yourselves in exploratory data anlysis. An example report (that has a few extra features) is found in this repo.

## Project Specifications 

Use the following checklist to ensure that you have completed all of the tasks.

- [ ] Read through README
- [ ] Find 1 or 2 other individuals who you want to work with and form a team.
- [ ] Create a repo using this repo as the template. Name your repo "FP_Name1_Name2_Name3" where Name# are the team member's names. (More details are available in the lecture note from Week12_Fri.pdf.)
- [ ] Make sure that each team member has access to the repo.
- [ ] Come up with a topic and set of research questions your team will explore.
- [ ] Make a plan for your work.
  - [ ] __Target Completion: <mark>Sunday, Apr. 7, 2024</mark>__
- [ ] Locate appropriate data sources for your project.
  - [ ] Your main data source may __not__ be one that we used in class nor be found in any R package.
  - [ ] Supplementary data sources may come from anywhere.
- [ ] Read in your data and perform any necessary data wrangling and cleaning.
- [ ] Conduct Exploratory Data Analysis.
- [ ] Prepare a reproducible report
  - [ ] Use a RMD file; output type is your choice.
  - [ ] The report should be well organized with section headings
  - [ ] __Code should be collapsed/hidden for HTML, and R Notebooks or in a Code Appendix at the end for a PDF.__
  - [ ] All outputs should be accompanied by narrative text to explain what the reader should be seeing.
  - [ ] State your research questions and explain them.
  - [ ] Describe your data sources (where they come from, what was their original purpose, who/what comprise the cases in each).
  - [ ] Describe what attributes you'll focus your analysis on (mention if they are part of your data sets or if you created them out of your data sets).
  - [ ] Create __multiple types of__ data visualizations that assist both the team and readers in understanding the data.
    - Data visualizations should show a variety of your skills and geometries.
    - __Optional__: If your research question/data make sense to do so, try creating a map.
  - [ ] Create __at least one visual table (not a display of raw data)__ that assists both the team and readers in understanding the data.
  - [ ] Have narrative text explaining every data visualization and table as well as setting a framework.
  - [ ] All code should be written according to a Style Guide of your choice. List this Style Guide as a code comment in your first code chunk.
  - [ ] __Optional:__ For those who want to challenge themselves further, feel free to include a section on using other statistical methods such as hypothesis testing, regression, ANOVA, or machine learning--see Chapter 18 of the Data Computing eBook.
- [ ] Use GitHub to share changes and edits; there should be multiple commits to your repo and __at least 2 by each team member__. Ensure that your instructor has access to your repo
- [ ] You'll submit an output file of your choice, the RMD, and a link to your GitHub Repo to the appropriate submission portal in Canvas.
    - __Due Date: Monday, Apr. 29th, 2024 by 5:00pm ET__
- [ ] During the last two weeks of classes (Apr. 17, Apr. 19, Apr. 24, and Apr. 26), your group will need to share a short presentation of what you've investigated and learned so far. __The schedule can be found on the detail page in Canvas by Apr. 7th.__
- [ ] Each member of the team needs to complete Peer/Self Evaluations using the included Evaluation template and upload the knitted PDF to the appropriate submission portal in Canvas.
    - __Due Date: Wednesday, May. 1st, 2024 by 11:59pm ET__
- [ ] Update this README file to check off all elements you have completed by placing an x inside the square brackets: [x]

## Learning Objectives and Outcomes Assessed
+ Code: Students will develop their ability to create reproducible code that others can understand.
  + Code.1: The student will learn to generate documentation for their code that not only they, but others can use to help make sense of the code.
  + Code.2: The student will learn to organize their code to assist with the code’s readability.
  + Code.3: The student will learn to implement a coding style for their code.
+ Prog: Students will develop their skills in programming with statistical software.
  + Prog.3: The student will learn to apply the core programming principles to their work.
  + Prog.5: The student will learn to plan their functions and code out in advance of writing syntax.
  + Prog.6: The student will learn to write their own code to engage in data analysis.
  + Prog.7: The student will learn to write their own functions in order to achieve their goals.
+ DA: Students will develop their skills in using statistical software to engage in data analysis.
  + DA.1: The student will learn to import files into R from a variety of sources and file types.
  + DA.4: The student will learn to create data visualizations that support data analysis.
  + DA.5: The student will learn to generate descriptive statistics to support data analysis.
  + DA.6: The student will learn to prepare a report that details their data analysis.
+ Collab: Students will develop their skills in collaborative programming.
  + Collab.1: The student will learn to implement version control as a means of creating reproducible work.
  + Collab.2: The student will learn to work collaboratively with other individuals on projects.
  + Collab.3: The student will learn to provide assistance to others without resorting to sharing answers.
+ CompThink: Students will develop ways of thinking which make use of computing power.
  + CompThink.1: The student will learn to incorporate statistical software (R) into their thinking.
  + CompThink.2: The student will learn to use statistical software to solve problems.
  + CompThink.3: The student will learn to draw upon the idea that there is no one “correct” way to program.

## FAQs
+ __Where can we get ideas for good data sources?__
  - Kaggle, Tidy Tuesday, and other outlets post lots of data analysis examples--if any group submits a project that looks too similar to work done by someone else it would be an academic integrity violation.  
  - https://www.data.gov/ --home of US government open data initiative.  Similarly, many states & communities have their own open data websites as well if you search the Internet
  - https://www.kaggle.com/datasets --Kaggle has tons of data sets freely available on a wide range of topics
  - https://github.com/fivethirtyeight/data --FiveThirtyEight (https://fivethirtyeight.com/) is a media outlet known for doing some excellent data analysis in many of their articles and stories.  Much of their data is shared in a GitHub Repo
  - https://github.com/nytimes --New York Times GitHub Repo with supporting data from many stories they have published
  - https://github.com/rfordatascience/tidytuesday --Your primary data set must NOT come from an R package.  You can usually download a CSV of the data hosted by Tidy Tuesday (if needed for your primary--they give you the `read_csv` code) or you can use their R package directly for a secondary source.
+ __What does a good example of the Final Project look like?__
  - Check out the various projects listed at the end of the Data Computing eBook as well as the example report. Those as well as the activities, especially towards the later parts of the course can help give you a sense of the scope for this project.  
+ __Can I use Python (or another language)?__
  - STAT 184 is an R programming course, and the project is intended to evaluate learning objectives of this course so you should mostly be using R and your entire analysis must be self-contained in a single R Markdown file. However, if you want to do something in the project that we have not learned about in class (using R) and prefer to use Python or some other language for that purpose it's fine to include some Python chunks in your R Markdown.
+ __We're really stuck on what to do. Help?__
  - What shared interests does your team have?
    - Do you all like a particular sport? Do you like a particular type of music? Do you like to play video games?
  - More general but interesting topics available.
    - Ever wondered if double stuf Oreos(R) actually have twice the amount of créme filling as regular Oreos(R)?
    - Does the type (thin, regular, double, mega, most) and flavor (regular, mint, lemon, dark chocolate) impact the amount of créme filling and/or the ratio of créme filling mass to wafer mass?
    - Be creative!
