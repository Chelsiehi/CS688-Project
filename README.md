# Gesture-Recognition-Algorithm-For-Yoga-Videos
Created a visualization of the physical activity as a GIF and Built a UMAP &amp; K-means clustering model


The pose-output.csv file is the result of feeding many exercise videos file into a pose- estimation algorithm (i.e., posenet https://github.com/tensorflow/tfjs- models/tree/master/posenet).
Each exercise is a tensor (three-dimension data, i.e., x,y,z and time)
(1) You need to create a visualization that as an input we feed an exercise and creates a visualization of the physical activity as an animation or gif. Look at 4th Figure in this file: https://miro.medium.com/max/1400/1*4Y0ZVDQKPpr- fLQcq1aaDg.gif
Your visualization should be the same (of course not the video)
(2) Apply three dimensionality reduction methods on the tensors (PCA, tSNE and UMAP).
(3) Experiment with different clustering methods (at least one partitional, one density based, one hierarchical and one soft clustering) on the result of dimensionality reduction, based on the annotation the videos have you should be able to decide about the best clustering approach.
