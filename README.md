# SPAX: A Shapley-based Point Attribution eXplanation for Interpreting 3D Point Cloud Classification

We propose an Explainable Artificial Intelligence methodology to interpret point cloud classification models. Our approach uses Shapley values from cooperative game theory which assigns contribution values to individual points towards a classification. Point cloud data contains rich spatial information, therefore it requires sophisticated deep learning models to make accurate predictions. However, these models often lack interpretability. Our methodology, Shapley-based Point Attribution eXplenations (SPAX), addresses this issue by quantifying and visualising the contribution of each point in a point cloud towards a prediction. To make it computationally feasible, a Monte Carlo approximation is used to estimate the Shapely values. To evaluate the method, a PointNet classifier trained on the ModelNet10 dataset is used to determine the Shapley values. These values are then coloured according to their magnitude and used to visually interpret their impact on the classification. The results show how spatial features become more interpretable because they identify key components to determine classification results. This study creates foundational principles to enable better point cloud interpretation, which produces opportunities to boost real-world deployments of transparent algorithmic systems.

Keywords: Explainable AI, PointNet, Point Cloud, Shapley Values, Interpretability, Classification, Monte Carlo Estimation

![Image here](SPAX_Pipeline.png)




### Citation
(Will Update once the pre-print is avaliable) 
If you find our work useful in your research, please consider citing:

	@misc{essay103223,
           title = {SHAX-PC : Adapting XAI methodology SHAP for point cloud data},
          author = {M.F. {Harinck}},
            year = {2024},
           month = {August},
             url = {http://essay.utwente.nl/103223/}
        
}

### Output
Subplots representing various data instances at incrementally increasing Monte Carlo sample sizes. From left to right, the number of samples increases. From top to bottom in descending order, the classes monitor, sofa, table, and toilet are shown.
![Image here](Variable_Monte_Carlo_Sampling_Size.png)
