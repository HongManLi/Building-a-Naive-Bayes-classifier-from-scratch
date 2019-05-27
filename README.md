# Building-a-Naive-Bayes-classifier-from-scratch

Abstracts of research papers from Medline database concerning proteins are used in this Naive Bayes algorithm. The aim of this algorithm
is to predict one of the 4 topics: Archaea, Bacteria, Eukaryota or Virus, which the research paper may be about.

Initially built only by following the Bayesian formula: Posterior Probability = likelihood x prior probability of class.
The logged posterior probability for each word in each new instance are added together and this process is done for each of the 4 class - 
the class producing the highest probability will be the class assigned to the new instance.

Extended with 2 extensions - likelihood are adjusted based on how many times a word occurs, and how long the abstract is.
More explanations to follow....
