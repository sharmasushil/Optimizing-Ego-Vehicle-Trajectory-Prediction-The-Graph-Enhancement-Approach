<p align="center">
    <h4 align="center"><a href="https://library.imaging.org/ei/articles/36/17/AVM-115">📑 Article</a>  | <a href="https://drive.google.com/drive/folders/1JPb64bGV88ymZkJrUBaKQg12tToZVF7T?usp=sharing">📂 Dataset</a> | <a href="https://docs.google.com/presentation/d/1L2y97B4u0trTz-H3UHlgdsDDh2rs03XE/edit#slide=id.p1">🎙️Talk</a>    </h4> 
</p>

# Optimizing-Ego-Vehicle-Trajectory-Prediction-The-Graph-Enhancement-Approach

Abstract:Predicting the trajectory of an ego vehicle is a critical component of autonomous driving systems. Current state-of-the-art methods typically rely on Deep Neural Networks (DNNs) and sequential models to process front-view images for future trajectory prediction. However, these approaches often struggle with perspective issues affecting object features in the scene. To address this, we advocate for the use of Bird’s Eye View (BEV) perspectives, which offer unique advantages in capturing spatial relationships and object homogeneity. In our work, we leverage Graph Neural Networks (GNNs) and positional encoding to represent objects in a BEV, achieving competitive performance compared to traditional DNN-based methods. While the BEV-based approach loses some detailed information inherent to front-view images, we balance this by enriching the BEV data by representing it as a graph where relationships between the objects in a scene are captured effectively.

# Our proposed architecture: ⛓️
Semantic segmentation derives bounding box coordinates and mask details from a BEV, this information is then utilized by a DNN to inform a KNN, which establishes connections between the boxes to create a graph. A GNN, enhanced with positional encoding, captures spatial features, while LSTM layers integrate temporal dynamics for the prediction of the ego vehicle’s trajectory.

![EIAMSGNN1_ARCH_resize](https://github.com/sharmasushil/Optimizing-Ego-Vehicle-Trajectory-Prediction-The-Graph-Enhancement-Approach/assets/70905483/140fda00-482d-448f-bc57-663990356165)

