# Large Scale Data Processing: Project 2
## Group Members: Hengrui Xie, Yinzhe Ma

## Question 1
Local Results:**Exact F2. Time elapsed:63s. Estimate: 4272998834**    

GCP Results: **Exact F2. Time elapsed:41s. Estimate: 4272998834**

## Question 2
Local Results: **Tug-of-War F2 Approximation. Width :10. Depth: 3. Time elapsed:85s. Estimate: 47698098**

GCP Results:**Tug-of-War F2 Approximation. Width :10. Depth: 3. Time elapsed:133s. Estimate: 40041566**

## Question 3
Local Results:**BJKST Algorithm. Bucket Size:2000. Trials:50. Time elapsed:146s. Estimate: 1.09051904E8**

GCP Results: **BJKST Algorithm. Bucket Size:2000. Trials:50. Time elapsed:224s. Estimate: 1.00663296E8**

## Question 4
Exact F0: **Exact F0. Time elapsed:39s. Estimate: 7406649**

Tug-of-War estimation seems a lot smaller than that of exact F2 (2 digits), and the time used to calculate exact F2 is significantly shorter as well. In terms of estimating F0, BJKST algorithm' estimation is still 2 digits off from the exact value, but the difference isn't as big as that of between ToW and exactF2; however, BJKST's runtime is a lot slower than exactF0.


