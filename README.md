# Causality "vs" Machine Learning

How does the knowledge of causal inference impact data science projects? Is it worth the effort?  
This experiment shows the huge value causal inference may have in real-world data science projects.

## Some conclusions

This is a very simple (silly?) experiment, but shows some important truths:

* Machine learning models (statistics in general) are very good at predicting when the unseen data is similar to the training data set, but they don't necessarily capture the real underlying patterns.

* If we want to predict what will happen if we change (force) the value a variable, ML will not help, as we are artificially changing the data set distribution.

* Causal inference is like an extra dimension that lets us see things we couldn't see before, and take decisions that were impossible to take without causal information.

