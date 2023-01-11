# **Clustering for Wheat Seeds**


## Data 

The [data](https://link.springer.com/chapter/10.1007/978-3-642-13105-9_2) which is used is comprised of 3 different wheat seeds (Kama, Rosa, and Canadian), using high quality visualizations via soft X-ray technoques. 

It is inexpensive and cheaper than more sophisticated imaging techniques, and were recorded on 12X18 KODAK plates. This data has use as a means to identify differing variants of wheat for multiple purposes, namely pest and disease identifcation, genetic research, and food allergens & regulations. 

Using Clustering mechanics allows the wheat seeds to be grouped and have its features examined and measured as well as distinguishing which seeds belong is which group or classification. It is a *Multivariate* dataset that consists of 7  major features and 210 instances not including the class, which is used to determine which type or group of seed it is already in and is dropped when used the purpose of clustering or training for classfication;

1. area A,
2. perimeter P,
3. compactness C = 4*pi*A/P^2,
4. length of kernel,
5. width of kernel,
6. asymmetry coefficient
7. length of kernel groove.


## Metrics and Info
KMeans was used to test how well it can group and identify seeds and grouping them together. A data visualization over several features using scatterplots was conducted involving using the class as a hue, seperating/highlighting the 3 groups to make observations on the seeds and compare the results KMeans would make without the use of Kernel Class;![Sneeds](https://user-images.githubusercontent.com/105755535/208737425-e2e8497a-2359-474b-b187-0618a2667829.png)

Afterwards Metrics were taken for KMeans to ascertain the optimal number of clusters, using Inertias and Silhouette Score with 2 different results;

![Sil_Score](https://user-images.githubusercontent.com/105755535/208739501-51bf478e-7b60-4b7e-91d2-c61950a86c25.png)
![image](https://user-images.githubusercontent.com/105755535/208739633-b9b0754e-ac59-4d78-a988-333c8c8e031d.png)

Silhouette Score said 2 clusters was optimal, while Inertias said 3 was. Both were tested out, and unsuprisingly KMeans with 3 clusters was the best amount for this particular set of data, although KMeans 2's predictions were similar to 3's in some ways such as the prediction sequence and recognition of the latter halves differences in features, but again lacking the ability to group them into 3 clusters meant KMeans 2 defaulted them into cluster 0. Broad analyses were made in order to compare to the previous scatterplot and data using the averages in each cluster. Below are the Clusters scatterplots and the Cluster's Feature average/mean plots.

![K2scatter](https://user-images.githubusercontent.com/105755535/208749307-e63dedc6-02f2-45f6-969f-a225acc01972.png)
![K3Scatter](https://user-images.githubusercontent.com/105755535/208749318-14384372-88f2-491f-a67b-8717b200a955.png)

![5029d7e9-003e-4336-a401-7d88ebb09abb](https://user-images.githubusercontent.com/105755535/211912497-9ccb0865-eb36-42f7-97f8-fc8726e20035.png)
![63cf7b79-f1e7-40dd-a325-d75f9524e51d](https://user-images.githubusercontent.com/105755535/211912537-2dd98355-5ed3-43f2-a59c-ac6d73d1ab7f.png)




## Next Steps:
Use on bigger datasets may be required to see if 3 clusters is optimal for the same seeds in largers sizes. Test out different types of clutsering methods to see if other models are more accurate. Create more exploratory Data Viz.


## Data Sources
Institute of Agrophysics of the Polish Academy of Sciences in Lublin

Piotr Kulczycki, Piotr A. Kowalski, Szymon Lukasik, Slawomir Zak Department of Automatic Control and Information Technology,
Cracow University of Technology, Warszawska 24, PL 31-155 Cracow, Poland and Systems Research Institute, Polish Academy of Sciences, Newelska 6,
PL 01-447 Warsaw, Poland.

MaÅ‚gorzata Charytanowicz, Jerzy Niewczas Institute of Mathematics and Computer Science, The John Paul II Catholic University of Lublin, KonstantynÃ³w 1 H,
PL 20-708 Lublin, Poland.

## Contact and Questions
If you have any questions please contact Jkhoury10000@gmail.com
