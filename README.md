# Causality "vs" Machine Learning

How does the knowledge of causal inference impact data science projects? Is it worth the effort?  

This set of experiments shows the huge value causal inference may have in real-world data science projects.

## Some conclusions

This is a set of very simple experiments, but shows some important truths:

* Machine learning models (statistics in general) are very good at predicting when the unseen data is similar to the training data set, but they don't necessarily capture the real underlying patterns.

* If we want to predict what will happen if we change (force) the value a variable, ML will not help, as we are artificially changing the data set distribution.

* Causal inference is like an extra dimension that lets us see things we couldn't see before, and take decisions that were impossible to take without causal information.

* Using only well-selected causal variables to predict the outcome helps the model on finding the **true underlying causal relationships**.

* This also works with non-linear models!

* If we don't have data of a needed confounder variable, not everything is lost! An instrumental variable will let us find the real relationship between two confounded variables without data of the confounder one.
