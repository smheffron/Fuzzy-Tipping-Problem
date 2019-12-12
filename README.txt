Understanding the code:
	1.) FuzzyLogic.ipynb is where all the generalized code for fuzzy operations,
	cylindrical closure for combining antecedents, implication operators, fuzzy
	implications, compositional rule of inference, defuzzification, real valued
	operations (chopping consequents, get min firing strength, etc), aggregations, and
	trapezoidal membership function creators is located.
	
	2.) TippingProblem.ipynb is where I use the generalized logic system in 
	FuzzyLogic.ipynb to produce a crisp tip value based on two crisp inputs (food and 	service)


How to run the code:
	1.) Ensure that all ipynb files are in the same directory. IrisClassifier.ipynb 	requires usage from FuzzyLogic.ipynb. Upload these files to Jupyter for usage.
	
	2.) To run the classifier on the UCI iris dataset, open IrisClassifier.ipynb in 	Jupyter
	
	3.) Click on Cell->run all
	
	4.) First you will be prompted for a value (0-10) of the food rating (10 highest 	quality, 0 lowest quality)
	
	5.) Then you will be prompted for a value (0-10) of the service rating (10 highest 	quality, 0 lowest quality)


Understanding the output:
	1.) The code will output three things:
		a.) The aggregated fuzzy outputs from the compositional rule of inference
		
		b.) A graphical representation of the aggregated consequents from all of 		the rules in the system and the centroid that is computed from those 			consequents
		
		c.) A crisp value that represents the percentage that one should tip based 		on the input food/service ratings