# From Reddit to Wall Street: The role of committed minorities in financial collective action
***Authors:*** *Artem Minakov, Elena Putilova, Diana Sharafeeva*

## Project goals 
The paper replicates the research conducted in the article titled ["From Reddit to Wall Street: The role of committed minorities in financial collective action"](https://arxiv.org/pdf/2107.07361.pdf), authored by Lorenzo Lucchini, Luca Maria Aiello, Laura Alessandretti, Gianmarco De Francisci Morales, Michele Starnini, and Andrea Baronchelli in 2021. 
    This replication project involves the comprehensive analysis of data from Reddit and financial markets to investigate the mechanisms by which commited individuals initiate cascading behaviors in financial markets and social networks, using Reddit data and GameStop stock data. In the context of this work, we conducted a comparative analysis between the findings obtained in the current research project and those presented by the authors in the referenced article.  

## Project questions:
- Quantify commitment of individual Reddit users of  r/wallstreetbets (WSB) subreddit;
- Compare commitment dynamics with stock shares daily returns;
- Investigate the growth of the social identity of WSB participants;
- Study the dynamics of social interactions between committed individuals and other WSB users.

## Data
- The activity on the subreddit r/wallstreetbets retrieved on April 6, 2021 (gained by [Academic Torrents](https://academictorrents.com/details/c398a571976c78d346c325bd75c47b82edf6124e))
- The price of GameStop shares, ticker GME (parsed from Yahoo Finance).

In overall number of posts: 138 766  
Number of comments: 4 209 560 

## Time period: 
All the data from January 1, 2016 until April 6, 2021
Analyzed data: from November 27, 2020 up to February 3, 2021 (as in the Article) 

## Quantifying commitment
### Quantifying commitment: number of posts
![map](https://github.com/elenaputilova/network_science/blob/main/project/images/number%20of%20posts.png) 

### Composition of commitment events by flair
![map](https://github.com/elenaputilova/network_science/blob/main/project/images/events%20by%20flair.png)

### Quantifying commitment: flairs
![map](https://github.com/elenaputilova/network_science/blob/main/project/images/flairs.png)  

## Group identity
![map](https://github.com/elenaputilova/network_science/blob/main/project/images/group%20identity.png)

### Alternative measure of group identity
![map](https://github.com/elenaputilova/network_science/blob/main/project/images/group%20identity2.png)

## Network dynamycs analysis 
![map](https://github.com/elenaputilova/network_science/blob/main/project/images/Jan%208-12.png)

## Network evolution
![map](https://github.com/elenaputilova/network_science/blob/main/project/images/Evolution.png)

## Network metrics 
### Reciprocity
![map](https://github.com/elenaputilova/network_science/blob/main/project/images/Reciprocity.png)

### Heterogeneity
![map](https://github.com/elenaputilova/network_science/blob/main/project/images/Heterogeneity.png)

### Average degree of the networks
![map](https://github.com/elenaputilova/network_science/blob/main/project/images/Average%20degree%20of%20the%20networks.png)

## Outcome
Though we didn't get absolutely the same numbers, we got similar trends and we can do similar conclusion except one, where the shortage of data influenced the result.  

Commitment comes before higher prices and stays consistent. This applies to both the article and the analysis.
In the article, people started showing their identity more when they became more committed, but in the analysis, identity expressions went down over time (likely because of deleted posts). Nevertheless, employing an alternative approach to measure group identity based on the number of post rewards reveals a comparable upward trend in group identity, aligning with the findings presented in the original article.   

On the network dynamics our findings aligned with the original article's observations. We noted an increase in heterogeneity and average degree within the network with a decline in reciprocity. This indicates that  the diversity and average connections in the evolving  network grow, but the mutual connections of users decrease.   

Furthermore, our analysis reinforced the original article's observation that commitment activity remained concentrated within the core while gradually spreading towards the periphery. This network evolution underscored the interplay between central and peripheral participants in collective action dynamics. Lastly, in the concluding stages of collective action, marked by significant price increases, we observed peripheral users actively engaging and displaying commitment, reaffirming the dynamism of participant roles within the studied phenomenon.  



