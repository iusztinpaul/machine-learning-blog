# Master Data Integrity to Clean Your Computer Vision Datasets
##### `Handle Data Leakage. Reduce Labeling Costs. Decrease Computation Time and Expenses.`

Data integrity is one of the biggest concerns for companies and engineers in the latest period.

The amount of data we have to process and understand only gets more significant, and manually looking at millions of samples is not sustainable. Thus, we need tools that can help us navigate our datasets.

This tutorial will present how to clean, visualize and understand Computer Vision datasets, such as videos or images.

We will be working on a video of the most precious thing in my house, my cat. Our end goal is to extract essential frames from the video that, lately, can be sent to labeling and to train your model. Extracting only essential information from a video is not straightforward because the video properties change constantly. For example, in the beginning, the video is extremely static, and starting from the middle there is a lot of action. Thus we need an intelligent way to understand the properties of the video to eliminate duplicate images, find the outliers, and cluster similar photos.
Leveraging FastDup, a tool for understanding and cleaning CV datasets, we will show you how to solve the above-mentioned problems. 

### The End Goal
We will present a tutorial on decoding a video of my sassy cat and extracting all the frames from it as images. We will use FastDup to visualize different statistics over the pictures dataset. 
The main goal is to remove similar/duplicate images from the dataset. In the next section, we will detail why cleaning your dataset from duplicates is crucial. Ultimately, we will look at the outliers before and after removing all the similar photos.