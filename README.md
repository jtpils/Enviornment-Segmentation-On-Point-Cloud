# Enviornment-Segmentation-On-Point-Cloud

本代码应用于点云的环境分割。为了将附近的障碍物分割出来。我们使用应用最广泛的欧几里得聚类的方法对环境中的点云进行聚类分割。最后将聚类好的出的点云框出来。本代码中运用到了点云的降采样，地面与非地面的分割，点云的过滤的技术。从点云的、之间的距离进行出发，来实现点云的聚类与分割。