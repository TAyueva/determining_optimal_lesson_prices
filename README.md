# italki: determining optimal lesson prices

**Business model description**

 italki is a marketplace for online language teachers. A freelance teacher registers on the platform and their resume is made available for students to book.
 The teacher can offer various types of lesson duration in 6 lesson categories. For each lesson there could be different price.
 Commission: italki takes 15% out of the lesson fee as its commission for all completed lessons, excluding trial lessons.

**The business objectives and goals that the project helps to achieve**

 The main goal of any business is to maximise its profits
 Because italki assesses a fixed 15% of the lesson fee as the commission for all completed lessons, there are two ways:
— Increase the number of completed lessons
— Increase the lesson prices

Pricing policy is sensitive:
— If the lesson’s price is too high, there will be fewer booked lessons
— Conversely, if the lesson’s price is too low, there is an opportunity to increase it and earn more income in less time

So, the highest net revenue — for both italki and its partners — results from setting optimal lesson prices.

**Project overview**

For this project, I collected information about 2776 English teachers from the italki website, prepared a detailed analysis   of the available data, optimized existing features and created new ones.

Based on the prepared features using data science and machine learning, I built a model for optimal lesson price calculation.
Data for 60-minute lessons was used exclusively, as this lesson offering is mandatory and cannot be unselected.

**Project outcomes**

The Mean Absolute Error (MAE) was used as the evaluation metric.
MAE is defined as the average variance between an expected values and a predicted values, without considering their direction.

Results:

MAE in train dataset - $ 3.47

MAE in test dataset - $ 3.61
