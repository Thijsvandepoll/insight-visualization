# insight-visualization

In this case you are asked to help us visualize critical strategic insights for Focus’ customers, based on an example patent data set. You will get 1 day to complete the case. If you have any question, please reach out to me (Jard van Ingen) via email or phone.

## General explanation of the Focus platform

Focus enables its customers to gather crucial business intelligence from patent data. Traditionally, patent data has been very difficult to search and transform into strategic insights. For this reason, only expertly trained professionals have been able to search patent data successfully. To open up patent data to non-expert searchers, Focus developed machine learning models that enable a user to train a classifier which can identify all relevant patents for them. The only thing the user needs to do, is perform a simple search, label which patents are relevant and irrelevant, train the algorithm, and repeat for a few cycles. After a few training iterations, the classifier’s performance will be strong enough to perform a wide search and identify all relevant patents.

## Case explanation

Imagine that user X works for a company that has invented a revolutionary way of producing graphene. To find out who else is active in this industry, user X has trained a classifier to look for other graphene production and application patents. The resulting patent set contains roughly 3.800 patent families. User X would like to quickly learn key strategic insights from visualizations of the data, so that he/she can take action as soon as possible. You are free to visualize the insights in whatever way you think is most informative (graph, chart, dashboard, go nuts!). If you have little time, a sketch could be enough, it is up to you. Finally, please add a very short explanation of why you took the approach that you did.

### Question 1 – Who owns what patents?

User X wants to know who the company’s largest competitors are. Every patent family has an owner which you can find in the Excel sheet. Please find an informative way of visualizing who owns what number of patents.

### Question 2 – How strong are the top competitors?

User X wants to know who the company’s most technologically advanced competitors are. Just because a company owns many patents, does not mean they are of high quality. To address this, Focus calculates a technological impact score. Intuitively visualize the average impact score for the entire portfolio of those competitors that own >20 patents.

### Question 3 – What patenting trend can be observed?

User X wants to know if the domain of graphene production is growing, shrinking, or stagnant. Every patent has a ‘patenting date’, which represents when the patent was filed. Please visualize the patenting trend over time in this domain.

### Question 4 – Visualize 1 extra insight.

Imagine one more insight user X might find interesting based on the data that was provided and visualize it to the best of your ability.
 
## Bonus - Recommending improvements to existing UI

Focus launched a first version of its interface. Only the very basics are present, and we are curious about how you would improve it. There are 4 screenshots attached to the case. For each screenshot, there is a small explanation below for what the user does in that part of the UI. Please recommend one or two improvements per element, either visually or in words, and argue your case.

### 1 – Focus dashboard

The Focus dashboard is the first thing users see when they log into the platform. Here they will see every classifier they have created, in the order in which they were last used. The version of the classifier is also displayed (every time a user performs a new training iteration, a new version is created). 

![alt text](https://github.com/Thijsvandepoll/insight-visualization/blob/main/1%20Focus%20dashboard.png)

### 2 – Focus search

After creating a new classifier, users can search for relevant patents to label in this interface. On the right side, there is a search form and left of that are the patents that show up after searching.  

![alt text](https://github.com/Thijsvandepoll/insight-visualization/blob/main/2%20Focus%20search.png)

### 3 – Focus labeling

After searching for patents, the user will start labeling which patents are relevant and which are irrelevant. This is done by clicking the positive and negative buttons which are represented by the green and red circles. When the user feels like enough patents have been labeled for this round, the training button can be clicked to initiate training.

![alt text](https://github.com/Thijsvandepoll/insight-visualization/blob/main/3%20Focus%20labeling.png)

### 4 – Focus patent badges

To display information about individual patents, Focus works with patent badges. Key information about the patents is displayed here.

![alt text](https://github.com/Thijsvandepoll/insight-visualization/blob/main/4%20Focus%20patent%20badge%20and%20relevancy%20score.png)
