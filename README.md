# SHapley Addative eXplenations for Point Coud (SHAX-PC)

Created by Marc F. Harinck from the University of Twente

This project is part of a research into Explainable articifal Intelegence. THe already existing SHAP library contains explainers for two dimentionall imagery, text and tabular data. The library does not contain eplainers for more complex data structures such as point clouds. 
This code is an implementation of the Shapley values theory applied to pointcloud. By computing an individual contribution of a single point wiithin the cloud, relative to the cloud, and iterating over all points in the cloud using monte-carlo sampling, An three-axis  visual is created containing the origional pointcloud with a colorfilter representative of each point's Shaple value. 

![Image here](https://github.com/Mavisis/SHAP-for-Point-Cloud/blob/main/SHAX_PC_pipeline.png)


This code uses the Modelnet 10 library and a pretrained model prvided by the paper by Charles R. Qi et. al. in their paper titled; PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation. 


### Citation
If you find our work useful in your research, please consider citing:

	@misc{essay103223,
           title = {SHAX-PC : Adapting XAI methodology SHAP for point cloud data},
          author = {M.F. {Harinck}},
            year = {2024},
           month = {August},
             url = {http://essay.utwente.nl/103223/}
        
}

### Usage
When loading in a single instance, the following output can be observed: 
![Image here](https://github.com/Mavisis/SHAP-for-Point-Cloud/blob/main/SHAX_PC_pipeline.png)
