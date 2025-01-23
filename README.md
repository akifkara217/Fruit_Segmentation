# Fruit Segmentation

Different traditional segmentation methods were used in the project and evaluated with different success metrics. The working mechanisms of success metrics were examined. The kernel sizes of the segmentation methods were changed and their effects on the success rate were examined. In addition, combinations of different methods were tried and the results were recorded.

Kaggle project link: https://www.kaggle.com/code/akifkara217/fruit-segmentation

Kaggle dataset link: https://www.kaggle.com/datasets/akifkara217/fruit-segmentation-dataset-with-mask

## Segmentation methods used in the project:
1. Threshold  
2. Kmeans  
3. Watershed  
4. Sobel  
5. Canny  
6. Prewitt  
7. Laplacian  
8. Laplacian of Gaussian  
9. Prewitt and Laplacian Combination  
10. Sobel and Laplacian Combination  
11. Laplacian of Gaussian and Sobel Combination  
12. Prewitt and Laplacian of Gaussian Combination  
13. Prewitt and Sobel Combination

## Success metrics used in the project:
1. Dice Coefficient
2. Precision
3. Recall
4. IoU (Intersection over Union)
5. F1-Score


## Success rates results by metrics:
### Threshold:
- **Dice Coefficient:** 0.0007  
- **Precision:** 0.1807  
- **Recall:** 0.2036  
- **IoU (Intersection over Union):** 0.1195  
- **F1-Score:** 0.1792  

### KMeans:
- **Dice Coefficient:** 0.0008  
- **Precision:** 0.1896  
- **Recall:** 0.2451  
- **IoU (Intersection over Union):** 0.1250  
- **F1-Score:** 0.1900  

### Watershed:
- **Dice Coefficient:** 0.0003  
- **Precision:** 0.1089  
- **Recall:** 0.0608  
- **IoU (Intersection over Union):** 0.0435  
- **F1-Score:** 0.0666  

### Sobel:
- **Dice Coefficient:** 0.0073  
- **Precision:** 0.4203  
- **Recall:** 0.9768  
- **IoU (Intersection over Union):** 0.4159  
- **F1-Score:** 0.5659  

### Canny:
- **Dice Coefficient:** 0.0008  
- **Precision:** 0.8305  
- **Recall:** 0.1174  
- **IoU (Intersection over Union):** 0.1150  
- **F1-Score:** 0.1943  

### Prewitt:
- **Dice Coefficient:** 0.0054  
- **Precision:** 0.4451  
- **Recall:** 0.7038  
- **IoU (Intersection over Union):** 0.3663  
- **F1-Score:** 0.5224  

### Laplacian:
- **Dice Coefficient:** 0.0066  
- **Precision:** 0.4771  
- **Recall:** 0.8398  
- **IoU (Intersection over Union):** 0.4275  
- **F1-Score:** 0.5780  

### Laplacian of Gaussian:
- **Dice Coefficient:** 0.0065  
- **Precision:** 0.4252  
- **Recall:** 0.8600  
- **IoU (Intersection over Union):** 0.3946  
- **F1-Score:** 0.5472  

### Sobel & Laplacian Combination:
- **Dice Coefficient:** 0.0073  
- **Precision:** 0.4180  
- **Recall:** 0.9834  
- **IoU (Intersection over Union):** 0.4152  
- **F1-Score:** 0.5649  

### Prewitt & Laplacian Combination:
- **Dice Coefficient:** 0.0069  
- **Precision:** 0.4507  
- **Recall:** 0.9093  
- **IoU (Intersection over Union):** 0.4292  
- **F1-Score:** 0.5794  

### Laplacian of Gaussian & Sobel Combination:
- **Dice Coefficient:** 0.0066  
- **Precision:** 0.3711  
- **Recall:** 1.0000  
- **IoU (Intersection over Union):** 0.3711  
- **F1-Score:** 0.5197  

### Prewitt & Laplacian of Gaussian:
- **Dice Coefficient:** 0.0066  
- **Precision:** 0.4451  
- **Recall:** 0.8805  
- **IoU (Intersection over Union):** 0.4165  
- **F1-Score:** 0.5687  

### Prewitt & Sobel:
- **Dice Coefficient:** 0.0073  
- **Precision:** 0.4268  
- **Recall:** 0.9741  
- **IoU (Intersection over Union):** 0.4216  
- **F1-Score:** 0.5711  

## Example Image: 
![Image](https://github.com/user-attachments/assets/243a9398-a4cb-43ed-8059-9311f56d3fb8)


