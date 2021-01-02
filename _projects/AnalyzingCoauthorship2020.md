---
title: "Analyzing co-authorship network: Centrality Measure, Link Prediction, and Community Detection"
collection: projects
permalink: /projects/AnalyzingCoauthorship2020
excerpt: 'This research project analyzes pre-birth factors, such as birth history, maternal history, reproduction history, socio-economic condition, etc. for the early classification of child mortality. Manuscript in Preparation.'
#date: '2019-06-03'
#venue: 'In Proceedings of the 32nd International Conference on Software Engineering Knowledge Engineering, 2020 (SEKE 2020)'
#paperurl: 'http://galib19.github.io/files/SigAPI_SEKE_2020.pdf'
#citation: 'Galib, A. H., Hossain, B. M. (2020, July). Significant API Calls in Android Malware Detection (Using Feature Selection Techniques and Correlation Based Feature Elimination). In Proceedings of the 32nd International Conference on Software Engineering Knowledge Engineering (pp.566-571).'


---

[[Github]](https://github.com/galib19/Analyzing-co-authorship-network-centrality-measure-link-prediction-community-detection)

This is the course project of CSE 891 (Fall 2020) at Michigan State University. 

In this project, I have extracted a network of co-authorship relations between researchers (i.e., those in the top-300 highest hindex according to Google scholar and have collaborated at least once with each other) and analyzed centrality measure, link prediction, and community detection using machine learning techniques. The distinct parts of this project:  

## Network data creation 

The goal is to create a co-authorship network from the
given input files (DBLP XML Files) and store their relation in an output ASCII text file named coauthor.csv,
which contains 2 comma-separated columns, (authorID1, authorID2), if the two authors have
collaborated at least once in the past. The mapping from author name to author ID is given
in the file authors.txt. Finally, I have visualized n co-authorship network with co-authorship links.

## Data exploration (Centrality Measure)

<ol>
<li>Compute the number of nodes (vertices) and links (edges) of the network</li>
  <li><strong>Centrality Measure:</strong></li>
  <ol>
  <li><strong>Degree Centrality</strong>: Compute the degree (i.e., number of collaborators) associated
with each author.</li>
  <li><strong>Eigenvalue Centrality</strong>: Find the principal eigenvector of the adjacency matrix
using power method. </li>
    <li><strong>Local Clustering Coefficient</strong>: Compute the local clustering coefficient of each node in the graph. </li>
  </ol>  
</ol>


## Link Prediction 
The objective of link prediction in network analysis is to infer missing
links or recommend new links in a network. For this step, tasks include:
<ol>
<li>Removing some of the links in the original network to create a new, modified network.</li>
<li>Using the modified network to train a logistic regression model.</li>
<li>Applying the logistic regression model to predict the links that were removed in part 1.</li>
</ol>

## Community Detection

The objective of community detection is to partition the network
into a set of connected components (communities) such that nodes in the same community are
more similar (connected) to each other compared to those belonging to different communities.
