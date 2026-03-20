Here I add Other things I have learned and other things I want to do

# To Do
 
 - [ ] I want to read this paper: [# Is Deep Learning finally better than Decision Trees on Tabular Data?](https://arxiv.org/html/2402.03970v2)
	 ![[taxonomy_tabular_class_models.png]]





# Learned

*  Here an interesting reddit thread  about [What algorithms are actually used the most in day-to-day as an ML enginner?](https://www.reddit.com/r/MLQuestions/comments/1pidvj2/what_algorithms_are_actually_used_the_most_in/)
	* The model selection depends on the trade-off between forecasting, data type and interpretability. GBDT are better than Neural Networks for tabular data, particularly with many categorical values and less than 50k samples. they also need less tuning and short training time.
	* *"An interesting question is **why** trees beat neural networks variants on tabular data so often. Neural networks rely on smooth, gradient based function approximation. That works well in domains with continuous, homogeneous structure like images or audio. Tabular business data is not like that. It mixes binary flags, integers, wide ranges, and many discontinuous interactions. Scaling helps, but when you have many features and only tens of thousands of samples the network struggles to learn sharp boundaries. Most tabular datasets are small relative to the capacity of even modest neural nets. Tree based models excel at learning irregular, piecewise constant or piecewise linear boundaries. They handle heterogeneous feature types without effort and do not assume smoothness. Boosting stacks many such trees, which is why these models tend to win on tabular benchmarks unless the dataset is extremely large."*
	* This visual is a good illustration of the difference between tree based boundaries and neural network boundaries and implies why trees excel on inhomogeneous data:
		![[mlpvsBGDTsmoothness.png]]

*