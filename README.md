# <img src="https://media.tenor.com/2ZexrTx-QSQAAAAC/linkedin.gif" width="48" height="48"> **Introduction**

In this depository we had to make the second stage of our prior project on linkedIn which was making a usuable search bar to search for job skills. The output given by the page would contain count, industry, seniority level and class which contained that particular skill and also show the table when asked for. We not only successfully made a search bar which can get the output for the relevent skills, we also made it so that if you type in a skill with spelling errors, it would simply get the closest search term and replace it with the wrong input.

![image](https://media.tenor.com/Y9pvgO_jITsAAAAC/business-card-career.gif)




# <img src="https://media.tenor.com/Ay5KbGo9bLAAAAAC/hammer-and-wrench-objects.gif" weight="48" height="48"> **Tools Used**

![image](https://github.com/AnubhabDebnath/LinkedIn_Job_Analytics_II/assets/110715196/eff17d7e-832d-4248-8acd-872549896774)



# <img src="https://media.tenor.com/wvFShvObfuIAAAAi/curiouspiyuesh-piyuesh-modi.gif" width="48" height="48"> **Problems Aimed to be Solved**


The initial challenge we faced was the development of a search bar capable of querying our database and retrieving the necessary results. This search bar was not just a simple query tool; it needed to be intelligent enough to autocorrect any typing errors made by the user, ensuring that the search process remained seamless and efficient.

In addition to this, we were tasked with creating a fully functional webpage. This was a new experience for our team as none of us had previously built a webpage using HTML and CSS. This required us to quickly learn and apply these languages, adding another layer of complexity to our project.

To summarize, our project involved two main components: the development of an intelligent search bar and the creation of a webpage. The search bar needed to be capable of querying a database and autocorrecting user errors, while the webpage required us to learn and apply HTML and CSS. These challenges pushed us to expand our skills and deliver a product that met all the requirements.


    
# <img src="https://media.tenor.com/wvFShvObfuIAAAAi/curiouspiyuesh-piyuesh-modi.gif" width="48" height="48"> **Steps Involved**

There were a few steps involved bofore we got to the analysis part which are as follows-
1. Pullin Data from LinkedIn - Scraped data from LinkedIn again with the help of python libraries i.e Selenium Webdriver and BeautifulSoup as we wanted a bigger dataset to work with this time.
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

A look into our search bar which gives out the required output whenever the user types in the skill or multiple skills, it also automatically corrects the spelling errors if there are any.

# <img src="https://media.tenor.com/3yhRZ20Z0dUAAAAi/vinesauce-joel.gif" weight="48" height="48"> **Problems Faced**

We faced several new challenges in this project. Firstly, we had to learn a new package called NLP (Natural Language Processing) in Python, which we had never come across before. Secondly, we had to create a webpage using HTML and CSS, which none of us had done before. Even after all that, there was a huge problem with making the search bar correct spelling errors from the user input. However, we managed to solve all these problems and more. We added a new column called “skills” to our old dataset using NLP. We also processed the user input text and made the model capable of rectifying spelling errors and showing related results. Finally, we created a backend with Flask and returned the output to the webpage.





# <img src="https://media.tenor.com/F02KJwYr6yYAAAAC/conclusion-the-band-conclusion-bd.gif" weight="48" height="48"> **Conclusion**

After spending a lot of time with this project we came to a few pointers as conclusion:
1. Most of the jobs belong to the IT sector.
2. Most of the companies are in class 2.
3. The user interference can be made a bit more appealing but due to time constraints we could not make it.
 
 
 

# <img src="https://media.tenor.com/i8gF6Y8Q7CAAAAAi/luxury-tata-cliq-luxury.gif" weight="48" height="48"> **Future Scope**

The project can be made in a much more refined way if it is made in the future. In case that happens, a few pointers can be looked upon:
1. Use of python instead of excel for the data cleaning part for more accuracy and overall lesser time spent on cleaning.
2. Separate tool for visualizations, the use of power bi is recommended.
3. Accuaracy can be increased by improving the text processing.




    
    
    
