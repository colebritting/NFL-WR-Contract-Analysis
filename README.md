# NFL-WR-Contract-Analysis
NFL teams need to plan their roster construction ahead of time to make sure they are making the most strategic decisions. Because of this, GMs would like to know how much they are going to have to pay a player ahead of time. This model allows them to predict if the receivers on their roster are going to command a top 10 WR contract after their rookie deal, based on their statistics from their first 3 years in the league. With this model, GMs can start to decide whether or not they plan to have a receiver in their future, and do it a year ahead of actually having to pay them.

Using NFL WR contract data, along with statistics from receivers' first 3 years in the league, I used Python to create various machine learning models to predict this. I first found contract data for NFL receivers, ranked them all based on APY value in each given year, and selected each second contract. I then found statistics for each receiver's first 3 years in the league, and used these statistics as my feature variables. After running my models, I cut down on my variables to strengthen the results, and came away with some great results. I used SVM, Decision Trees, Random Forest, Logistic Regression, Gradient Boosting, and Naive Bayes.

Data: https://overthecap.com/contract-history/wide-receiver
https://stathead.com/football/player-season-finder.cgi
