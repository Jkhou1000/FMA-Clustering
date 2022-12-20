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
KMeans was used to test how well it can group and identify seeds and grouping them together. A data visualization over several features using scatterplots was conducted involving using the class as a hue, seperating/highlighting the 3 groups to make observations on the seeds and compare the results KMeans would make without the use of Kernel Class.![Sneeds](https://user-images.githubusercontent.com/105755535/208737425-e2e8497a-2359-474b-b187-0618a2667829.png)
