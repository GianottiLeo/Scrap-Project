# Scrap Project

Project developed during my course in USP SME0882 Consultoria Estatística

This is not a mandotory course, but one of the best ones I had during my time in ICMC. The idea was to separate the class in groups and give each of then a real case scenario, to be worked in the semester. Our case was about a logistics operator that manages a railway network in three Brazilian states. 

Their problem was the scrapping of electronic components impacting locomotive operation. At that point, there were no standardized criteria to decide when to scrap or withdraw recovered components from circulation, resulting in subjective decisions by maintenance technicians. With this, our goal was to create a model that made the decision on scrapping or not of these electronic components, in order to standardize and automate the determinative process. For this, the item codes were used, which identify each type of component, and from this, the return rate, the causes of return (failure mode described in free text), and the repair performed were analyzed. Despite the database having a status attribute that indicates whether a part was "Scrapped" or "Recovered", we noticed that several parts that were "scrapped" returned to function later, showing a flaw in filling out this attribute, which led us to disregard it and use excerpts from the "Description of Repair", composed of free text, to classify it as scrapped or not.

Having this initial insight, we proceeded with the problem of how to create a system/platform to assist in the decision-making process regarding scrapping or withdrawing parts from circulation. For this, we primarily used Survival and Reliability Analysis, and to be more specific, we delved into the issue of Repairable Systems Models. After some analysis and attempts at modeling, the ARAm model, a variation of ARA, was ultimately chosen. Additionally, an automated Dashboard, which I was majorly responsable for, was developed in Power BI to facilitate data visualization for the user with various types of filters and presentation layouts.

We used multiple tools to reach the final result, Excel and R for the exploratory analysis and to better format the data to be input in Python for the statistical analysis and Power Bi to create the dashboard. 

In summary, this project was a standout experience during my time at ICMC. This experience not only enhanced my technical skills, but also fostered my ability to work effectively in a team and communicate complex ideas clearly. Moreover, being responsible for the development of the Power BI dashboard was a significant learning opportunity for me, enhancing my skills in data visualization and project management. Overall, I am grateful for the opportunity to work on this project, and I believe it has significantly contributed to my growth as a student and prepared me for future challenges in my career.

All the code analysis in Python is in the .py file attached and the slides we used to present the project to our class and for the company is in the pdf file. Here are some images from the dashboard created

<p align="center">
<img width="12" />
<img src="https://github.com/GianottiLeo/Scrap-Project/assets/164948682/a4831ab6-d8ba-440a-baac-5b53912a8425" height="360" alt="powerbi logo" width ="630"  />
