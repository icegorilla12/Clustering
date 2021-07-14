# Clustering
Clustering Passes to analyze what teams do frequently.

Most of this is the implementation of https://www.americansocceranalysis.com/home/2019/3/11/using-k-means-to-learn-what-soccer-passing-tells-us-about-playing-styles with a few changes of my own. 

## All Pass Clusters

I divided all the passes of the 2017-2018 Premier League Season in 50 clusters. This is how all of they look. 

![](/images/pass_clusters.png)


### Most Frequent Clusters

Based on the number of passes present in a particular cluster I looked at the ones that occur most frequently. 

![](/images/over_represented.png)

### Least Frequent Clusters

Long balls are the least frequent owing to less chances of being completed.

![](/images/udner_represented.png)


## Best Clusters?

I used pass accuracy and the average threat created by the passes in a particular cluster to find those which had the highest payoff. 

![](/images/high_payoff_index.png)

Here the linewidths suggest the average threat created by a pass in that cluster. Crosses, passes into the box or setting these up are the passes which have the highest payoff. 

# Clustering Progressive Passes

Trying to classify all progressive passes into 10 clusters. 

![](/images/progressive_clusters.png)

### Progressive Passes most frequently used by Manchester City 

![](/images/cityprog.png)

## How do different teams move the ball?

By comparing the percentage of passes in a particular cluster for a team to all the other teams we can get a sense of the kinds of passes they use more than the rest and the kind of passes they use less than an average team. Given below are the most freuent clusters used by Burnley.

![](/images/Burnley_clusters.png)
