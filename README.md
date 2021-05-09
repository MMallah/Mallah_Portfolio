# Mallah_Portfolio
Data Science Portfolio

# [Project : E-commerce A/B test](https://nbviewer.jupyter.org/github/MMallah/E-Commerce-A-B-test/blob/master/E-commerce%20A_B%20Test.ipynb)

![a/b test](https://github.com/MMallah/E-Commerce-A-B-test/blob/master/images/abtest.png)

A/B test run by an e-commerce website. The company has developed a new web page in order to try and increase the number of users who convert, meaning the number of users who decide to pay for the company's product. our goal is to work through this notebook to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.

* After <code>data wrangling</code>, we calculate the average conversion rate for both the {old page} & {new page}.
* Then we test the conversion rate using the <code>central limit therom</code> after taking 10k samples.
* From the tests conducted, we summarize that we don't have enough evidence to reject the <code>null hypothesis</code> which stated that the old paage has better average conversion rate. 



---
# [Project : Cookie Cat Game A/B test](https://nbviewer.jupyter.org/github/MMallah/Cookie-Cat-Game-A-B-Test/blob/main/Cookie%20Cat%20Game%20A-B%20Testing.ipynb)

<p><img src="https://github.com/MMallah/Mallah_Portfolio/blob/main/images/cookiecat_gates.png"></p>

We will examine the impact of changing an in game mechanic on one of the most important customer KPI's, which is retention metric. As players progress through the levels of the game, they will occasionally encounter gates that force them to wait a non-trivial amount of time or make an in-app purchase to progress. In addition to driving in-app purchases, these gates serve the important purpose of giving players an enforced break from playing the game, hopefully resulting in that the player's enjoyment of the game being increased and prolonged
But where should the gates be placed? Initially the first gate was placed at level 30, but in this notebook we're going to analyze an AB-test where we moved the first gate in Cookie Cats from level 30 to level 40.

* The data <code>randomly assigned</code> to control and test groups.
* <code>A/B testing</code> using <code>Bootstraping</code> techniques.
* Testing for difference in retention rate. 


---

# [Project : Moby Dick Word Frequency Counter](https://nbviewer.jupyter.org/github/MMallah/Word-Frequency-Counter-for-Moby-Dick-Novel/blob/main/Moby%20Dick%20Word%20Frequency%20counter.ipynb)

<p><img src="https://github.com/MMallah/Mallah_Portfolio/blob/main/images/moby%20dick.jpg"></p>

<p>What are the most frequent words in Herman Melville's novel, Moby Dick, and how often do they occur?</p>
<p>In this notebook, we'll scrape the novel <em>Moby Dick</em> from the website <a href="https://www.gutenberg.org/">Project Gutenberg</a> (which contains a large corpus of books)
 
*  Using the Python package <code>requests</code>.
*  Then we'll extract words from this web data using <code>BeautifulSoup</code>. 
*  Finally, we'll dive into analyzing the distribution of words using the Natural Language ToolKit (<code>nltk</code>) and <code>Counter</code>.</p>

---

# [Project : Investigating Patients not showing for check-ups ](https://github.com/MMallah/Why-Patients-miss-appointments/blob/master/Why%20Patients%20don't%20show%20Up..ipynb)

The data set in hand, has information about the attendance of patients after making an appointment for a check up, it has 110.527 medical appointments it's 14 associated variables. We will be analysing trends for patients who showed up Vs. Patients who didn't show for the appointment, and how they differ.

<p><img src="https://github.com/MMallah/Mallah_Portfolio/blob/main/images/project%201%20image1.jpg" alt="" width="650" height="250""></p>

* Here we have our first finding, for Age having a sort of relation ship on showing up or not, from the right graph we notice, that the IQR and the median are shifted to the left Vs. the left figure, which gives some indication that younger people might have higher chance to miss an appointment, and we notice for ages starting 39 years old and above people are more likely to adhere to their appointment.
* It is noticable that percentage of patients not showing up having received multiple SMS, shows a much stronger association compared for patients attending, and it is one the Variables having largest association with Not showing to the appointment.
* We find an interesting insight, that people with scholarships might have a relationship, with not showing, as the number of patients having a scholarship and missed the appointment increased a little bit compared to patients with no Scholarships,after refering back to the wikipedia page for the scholarship.
* Now after knowing that Scholarship variable, is an indication of funding based on School attendance, it clears the logic, behind healthy people reserving an appointment in a clinic, perhaps for Vacination or to check on the students attendance at school, and having about 80% of Healthy people making up the bulk of the attendies missing the appointment, it is more likely for healthy individual to miss an appointment in comparison to a patient going for a treatment.
* Waiting time seems to have some relationship with missing an appointment, as people are more associated to attend if the time between the reservation date and actual appointment is only one day, while the No-show is observed to have higher percentages of not showing up if the period is larger than 7 days


 
---

# [Project : Comparing Cosmetics Products By Ingredients](https://nbviewer.jupyter.org/github/MMallah/Comparing-Cosmetics-Ingredients/blob/bf4d84812d880be9d5845b0ec1c9c91d6d9a2d0d/Comparing%20Cosmetics%20Products%20By%20Ingredients.ipynb)
Content-based recommendation system based on ingredients

![ingredients breakdown](https://github.com/MMallah/Mallah_Portfolio/blob/main/images/project%202%20image_3.PNG)

* Create a <code>content-based recommendation system</code> based on ingredients.
* Focused on one <code>sample</code> of products.
* Use <code>Tokenization</code> and <code>Dcoment-term-Matrix (DTM)</code> per product.
* Utilizse <code>T-SNE</code> for <code>dimensionality reduction</code> to make it easier to compare products.
* Visualize the composition similiarty between products.
* Now it is easier to find similar products and compare prices.



---

# [Project :PISA 2012 Students Results](https://mmallah.github.io/PISA-2012-Students-Results/)

![ingredients breakdown](https://github.com/MMallah/Mallah_Portfolio/blob/main/images/Pisa%20Score.png)

 The data consists of information regarding 485,490  students, including Gender, country, class size, ICT possessions , learning times and habits,  subjective norms about studying math and 3 main Test scores for Mathematics,  reading language, and Science. The dataset can be found in the PISA survey page   [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisa2012.csv.zip&sa=D&ust=1554482573645000), with feature documentation available [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisadict2012.csv&sa=D&ust=1554482573645000).

* <code>Explore</code> the Dataset and examin the relationships between variables and the three main Target features; Mathematics, Reading and Science scores.



---
