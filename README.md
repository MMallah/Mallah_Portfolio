# Mallah_Portfolio
Data Science Portfolio

# [Project 1: E-commerce A/B test](https://nbviewer.jupyter.org/github/MMallah/E-Commerce-A-B-test/blob/master/E-commerce%20A_B%20Test.ipynb)

A/B test run by an e-commerce website. The company has developed a new web page in order to try and increase the number of users who convert, meaning the number of users who decide to pay for the company's product. our goal is to work through this notebook to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.

* After data wrangling, we calculate the average conversion rate for both the {old page} & {new page}.
* Then we test the conversion rate using the central limit therom after taking 10k samples.
* From the tests conducted, we summarize that we don't have enough evidence to reject the null hypothesis which stated that the old paage has better average conversion rate. 

![a/b test](https://github.com/MMallah/E-Commerce-A-B-test/blob/master/images/abtest.png)

---


# [Project : Investigating Patients not showing for check-ups ](https://github.com/MMallah/Why-Patients-miss-appointments/blob/master/Why%20Patients%20don't%20show%20Up..ipynb)

The data set in hand, has information about the attendance of patients after making an appointment for a check up, it has 110.527 medical appointments it's 14 associated variables. We will be analysing trends for patients who showed up Vs. Patients who didn't show for the appointment, and how they differ.

* Here we have our first finding, for Age having a sort of relation ship on showing up or not, from the right graph we notice, that the IQR and the median are shifted to the left Vs. the left figure, which gives some indication that younger people might have higher chance to miss an appointment, and we notice for ages starting 39 years old and above people are more likely to adhere to their appointment.
* It is noticable that percentage of patients not showing up having received multiple SMS, shows a much stronger association compared for patients attending, and it is one the Variables having largest association with Not showing to the appointment.
* We find an interesting insight, that people with scholarships might have a relationship, with not showing, as the number of patients having a scholarship and missed the appointment increased a little bit compared to patients with no Scholarships,after refering back to the wikipedia page for the scholarship.
* Now after knowing that Scholarship variable, is an indication of funding based on School attendance, it clears the logic, behind healthy people reserving an appointment in a clinic, perhaps for Vacination or to check on the students attendance at school, and having about 80% of Healthy people making up the bulk of the attendies missing the appointment, it is more likely for healthy individual to miss an appointment in comparison to a patient going for a treatment.
* Waiting time seems to have some relationship with missing an appointment, as people are more associated to attend if the time between the reservation date and actual appointment is only one day, while the No-show is observed to have higher percentages of not showing up if the period is larger than 7 days


<p><img src="https://github.com/MMallah/Mallah_Portfolio/blob/main/images/project%201%20image1.jpg" alt="" width="650" height="250""></p>
---


# [Project 2: Comparing Cosmetics Products By Ingredients](https://nbviewer.jupyter.org/github/MMallah/Comparing-Cosmetics-Ingredients/blob/bf4d84812d880be9d5845b0ec1c9c91d6d9a2d0d/Comparing%20Cosmetics%20Products%20By%20Ingredients.ipynb)
Content-based recommendation system based on ingredients

* Create a content-based recommendation system based on ingredients.
* Focused on one sample of products.
* Use Tokenization and Dcoment-term-Matrix (DTM) per product.
* Utilizse T-SNE for dimensionality reduction to make it easier to compare products.
* Visualize the composition similiarty between products.
* Now it is easier to find similar products and compare prices.

![ingredients breakdown](https://github.com/MMallah/Mallah_Portfolio/blob/main/images/project%202%20image_3.PNG)

---

# [Project :PISA 2012 Students Results](https://mmallah.github.io/PISA-2012-Students-Results/)

 The data consists of information regarding 485,490  students, including Gender, country, class size, ICT possessions , learning times and habits,  subjective norms about studying math and 3 main Test scores for Mathematics,  reading language, and Science. The dataset can be found in the PISA survey page   [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisa2012.csv.zip&sa=D&ust=1554482573645000), with feature documentation available [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisadict2012.csv&sa=D&ust=1554482573645000).

* Explore the Dataset and examin the relationships between variables and the three main Target features; Mathematics, Reading and Science scores.

![ingredients breakdown](https://github.com/MMallah/Mallah_Portfolio/blob/main/images/Pisa%20Score.png)

---
