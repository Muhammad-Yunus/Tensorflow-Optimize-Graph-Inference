# Tensorflow-Optimize-Graph-Inference
 Convert frozen graph Tensorflow (.pb) to optimized inference model for OpenCV DNN


- Train model using Neural Network Console (NNabla) dl.sony.com
	- Algorithm : Logistic Regression
	- Dataset : MNIST
	- Task : Recognize if image is 9 or 4
	- Export model to (.pb) Tensorflow Frozen Graph
	
- Convert (.pb) Tensorflow Frozen Graph to Optimized Model for Inference 
	- Check input & output layer on the graf (view on tensorboard)
	- run `transform tf frozen graph.ipynb` to transform
	
- Inference using OpenCV DNN on Jupyter Lab