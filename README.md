# EVA4
EVA4
Model 	S5 First Try 
Params 	5890
Best test accuracy 	97.95%
Best train accuracy	97.95%
Analysis 	The model is prforming well and is not overfitting - I would like to increase the capacity of the model by using Batch Norm
	
	
Model 	S5 Second Try 
params 	6050
Best Test accuracy	98.99%
Best Train accuracy	99.17%
Analysis 	I added batch norm for all the layers and added an extra layer after the GAP to add capacity and now I am able to see some overfitting 
	
	
Model 	S5 Third Try 
params 	6050
Best Test accuracy	98.68%
Best Train accuracy	99.25%
Analysis 	After adding dropout, the overfitting is gone - We just need to add more capacity to the model and it will train and reach a better test accuracy
	
	
Model 	S5 Fourth Try 
params 	9860
Best Test accuracy	99.32%
Best Train accuracy	99.08%
Analysis 	The model is reaching the potential - we just need to add the image augmentation and the LR scheduler as our last few tools to give it the extra push 
	
Model 	S5 Final try
params 	9860
Best Test accuracy	99.41%
Best Train accuracy	98.91%
Analysis 	The model has reached its goal but we can see if pushed a bit more - it would train better and reach better accuracy as its still not overfitting
