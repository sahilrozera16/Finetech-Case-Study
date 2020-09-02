# Finetech-Case-Study

**NOTES ON DATA**

The data for these projects are manufactured fields based on trends found in real world Case Studies. The fields describe what companies usually track from their users, and the distributions are based on observed distributions in real world analysis. This means that, although the data has been artificially created, the patterns, associations, and distributions are not random . 

The data serves as a good representation of what you may encounter in the workplace. That is the data is rarely clean, and a lot of pre-processing is needed to get it ready for modeling.


**NOTE ON MODELS BUILDING:**

The Model Building Process is composed of multiple parts. Some of the things we will cover include:

• Plotting with Matplotlib and Seaborn -A lot of time will be spent on Exploratory Data Analysis (EDA).

• Data Manipulation - We will use Pandas (and Numpy) for all of our data formatting steps.

• Classification Models from the Sklearn Library (Logistic Regression, and Regularization)

• K-Fold Cross Validation, Grid Search (Parameter Tuning), and Feature Selection algorithms.

Previous knowledge of some of these concepts and tools will help you understand the model building process quicker. Nonetheless, we will still review them as we go along, as a refresher. The libraries we will be using (and which you should have installed on your version of Python) are:

• Pandas, Seaborn, Numpy, Date,util, Matplotlib, Time, Random.

**INTRODUCTION**

In today's market, many companies have a mobile presence. Often, these companies provide free products/services in their mobile apps in an attempt to transition their customers to a paid membership. Some examples of paid products, which originate from free ones, are YouTube Red, Pandora Premium, Audible Subscription, and You Need a Budget. Since marketing efforts are never free, these companies need to know exactly who to target with offers and promotions.

• Market -  The target audience is customers who use a company's free product. In this case study, thisrefers to users who installed (and used) the company's free mobile app.

• Product: The paid memberships often provide enhanced versions of the free products already given for free, alongside new features. For example, Youtube Red allows you to leave the app while still listening to a video.

• Coal: The objective of this model is to predict which users will not subscribe to the paid membership, so that greater marketing efforts can go into trying to convert them to paid users.


**BUSINESS CHALLENGE**

• In this Case Study we will be working for a fintech company that wants to provide its customers with a paid mobile app subscription that will allow them to track all of their finances in one place. To attract customers, the company releases a free version of their app with some of the main features unlocked.

• The company has tasked you to identify which users will most likely NOT enroll in the paid product, so that additional offers can be given to them. Because of the costs of these offers, the company does not want to offer them to everybody, especially customers who were going to enroll anyways.

**DATA**

• By working for the company, we have access to each customer's app behavior data. This data allows us to see the date and time of app installation, as well as the features the users engaged with within the app. App behavior is characterized as the list of app screens the user looked at, and whether the user played the financial mini-games available.

• The app usage data is only from the user's first day in the app. This limitation exists because users can enjoy a 24-hour free trial of the premium features, and the company wants to target them with new offers shortly after the trial is over.
