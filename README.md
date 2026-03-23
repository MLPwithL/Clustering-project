# Clustering-project
This is a task-driven project.
# Clustering

## 📌 问题背景
> Imagine a city buzzing with drone deliveries. A logistics company wants to partition the city into zones so that drones can serve customers efficiently without wasting battery life. Each zone should group customers who live close to one another. The customers’ coordinates are provided in the Google Drive (HW3 q4 data.csv). Image source: Shutterstock / Built In We will use Agglomerative Hierarchical Clustering, a bottom-up approach that starts with each customer as its own cluster and merges them step by step. Consider three different linkage criteria below: • Single linkage: Merge clusters based on the minimum distance between any two points in different clusters, dC(A, B) = min a∈A, b∈B d(a, b). • Complete linkage: Merge clusters based on the maximum distance between any two points in different clusters, dC(A, B) = max a∈A, b∈B d(a, b). • Average linkage: Merge clusters based on the average distance between all pairs of points across clusters, dC(A, B) = 1 |A| |B| X a∈A X b∈B d(a, b). Suppose we want k = 4 clusters. Using a programming language you are familiar with, complete the following tasks for each of the above linkage methods:
 (a) Draw the dendrogram and indicate the cut that yields 4 clusters (you may use the dendrogram function in MATLAB/Python). 
(b) Assign cluster labels to all points and create a scatter plot with all points colored according to their cluster labels. 


本项目的目标是使用scipy.cluster.hierarchy对数据集进行分类，执行数据分类

## 📊 数据集
- **文件**：`HW3_q4_data`
- **样本数**：1000个样本
- **特征数**：x，y坐标
- **目标变量**：分类
- **数据来源**：课程作业

## 🔧 技术栈
- Python 3.x
- pandas, numpy（数据处理）
- scipy.cluster.hierarchy
- dendrogram，matplotlib（可视化）
