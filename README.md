# velo_filter
velo_filter : Voxel Grid Filter, Statistical Outlier Removal Filter, Crop Box Filter 적용


velo_filter_add : 기존 velo_filter에 RANSAC(RANdom SAmple Consensus)를 적용하여 지면 제거


euclidean_cluster : velo_filter_add에서 지면이 제거된 PointCloud를 Euclidean 방식 Clustering을 적용하여 객체 인식
