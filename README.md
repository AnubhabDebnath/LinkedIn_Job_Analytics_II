# <img src="https://media.tenor.com/2ZexrTx-QSQAAAAC/linkedin.gif" width="48" height="48"> **Introduction**

In this depository we had to make the second stage of out prior project on linkedIn which was making a usuable search bar to search for job skills. The output given by the page would contain count, industry, seniority level and class which contained that particular skill and also show the table when asked for. We not only successfully made a search bar which can get the output for the relevent skills, we also made it so that if you type in a skill with spelling errors, it would simply get the closest search term and replace it with the wrong input.

![image](https://media.tenor.com/Y9pvgO_jITsAAAAC/business-card-career.gif)



# <img src="https://media.tenor.com/3yhRZ20Z0dUAAAAi/vinesauce-joel.gif" weight="48" height="48"> **Problems Faced**

This continuation of our previous project had its own new set of problems. We had to learn a new package - NLP(Natural Language Processing) in python which again we never came across prior to this. Then again, we had to make a webpage which none of us had made before using HTML and CSS. Even after all that there was a huge problem with making the search bar correct spelling errors from the user input. Still we managed to solve all these problems and more.
1. Adding a new column "skills" to our old dataset using NLP.
2. Text processing of user input and making model capable of rectifying spelling errors and can show related results.
3. Creating a backend with flask and returning output to webpage.
    
# <img src="https://media.tenor.com/wvFShvObfuIAAAAi/curiouspiyuesh-piyuesh-modi.gif" width="48" height="48"> **Steps Involved**

There were a few steps involved bofore we got to the analysis part which are as follows-
1. Pullin Data from LinkedIn - Scraped data from LinkedIn again with the help of python libraries i.e Selenium Webdriver and BeautifulSoup as we wanted a            bigger dataset to work with this time.
2. Cleaning - Cleaned the data using excel, removing irrelevant columns, rows and other noise values.
3. Adding new column - Processing Job Description in NLP, extracting skills from job description and finally adding "skills" column.
4. Data Preprocessing - Handling missing, null and duplicate values. Removing outliers from features.
5. Building ML model - Using the KMeans algorithm made the ML model.
    
# <img src="https://media.tenor.com/K8DuFxJuF50AAAAi/goal-circle.gif" width="48" height="48"> **Insights**


![Screenshot 2](https://user-images.githubusercontent.com/110715196/236049737-cb3cbd8f-d203-43f7-9690-a59c03dbb322.png)

Here we used the elbow method to find the optimum number of clusters which came out to be 4.


![Screenshot 3](https://user-images.githubusercontent.com/110715196/236050212-e16334cd-c77a-4357-bc21-a95a3ccf32ce.png)

3D scatter plot of the clusters


![Screenshot 4](https://user-images.githubusercontent.com/110715196/236050370-9bb34408-557c-46a8-b515-f17694542018.png)

A look into our search bar which gives out the required output whenever the user types in the skill or multiple skills, it also automatically corrects the spelling errors if their are any.

    
    
    
