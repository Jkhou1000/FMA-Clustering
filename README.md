# **Clustering for Wheat Seeds**


### Seed clusters data 

The [data](https://link.springer.com/chapter/10.1007/978-3-642-13105-9_2) which is used is comprised of 3 different wheat seeds (Kama, Rosa, and Canadian), using high quality visualizations via soft X-ray technoques. It is inexpensive and cheaper than more sophisticated imaging techniques, and were recorded on 12X18 KODAK plates. This data has use as a means to indetify differing variants of wheat for multiple purposes, namely pest and disease identifcation, genetic research, and food allergens & regulations. 

Using Clustering mechanics allows the wheat seeds to be grouped and have its features examined and measured as well as distinguishing which seeds belong is which group or classification. It is A *Multivariate* dataset that consists of 7  major features and 210 instances not including the class, which is used to determine which type or group of seed it is already in and is dropped when used the purpose of clustering or training for classfication;

1. area A,
2. perimeter P,
3. compactness C = 4*pi*A/P^2,
4. length of kernel,
5. width of kernel,
6. asymmetry coefficient
7. length of kernel groove.


### Metrics and Info
KMeans was used to test how well it can group and identify seeds and grouping them together. A data visualization over several features using scatterplots was conducted involving using the class as a hue, seperating/highlighting the 3 groups to make observations on the seeds and compare the results KMeans would make without the use of Kernel Class;![Sneeds](https://user-images.githubusercontent.com/105755535/208737425-e2e8497a-2359-474b-b187-0618a2667829.png)

Afterwards Metrics were taken for KMeans to ascertain the optimal number of clusters, using Inertias and Silhouette Score with 2 different results;

![Sil_Score](https://user-images.githubusercontent.com/105755535/208739501-51bf478e-7b60-4b7e-91d2-c61950a86c25.png)
![image](https://user-images.githubusercontent.com/105755535/208739633-b9b0754e-ac59-4d78-a988-333c8c8e031d.png)

Silhouette Score said 2 clusters was optimal, while Inertias said 3 was. Both were tested out, unsuprisingly, KMeans with 3 clusters was the best amount for this particular set of data, although KMeans 2's predictions were similar to 3's in some ways such as the prediction sequence and recognition of the latter halves differences in features, but again lacking the ability to group them into 3 clusters meant KMeans 2 defaulted them into cluster 0.





