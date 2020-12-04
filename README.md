# CSCE 614 Term Project

### Team Members: 
Aaryan Kothapalli, Michell Brito

### Paper: 
Hardware for Machine Learning: Challenges and Opportunities - https://arxiv.org/pdf/1612.07625.pdf

### Abstract: 
Machine learning has grown extremely popular in the recent years and provided many opportunities for scientists, but also brought many challenges in the computer architecture field. When it comes to training a system through experience, it often requires very large datasets to be processed quickly, and high energy consumption to enable this processing. To account for these obstacles, specialized architectures like a Graphical Processing Unit can be used that are especially potent in large data processing and repeated instruction processing. Based on the paper "Hardware for Machine Learning: Challenges and Opportunities", we explore different hardware architectures and their limitations in processing a neural network. We compare MNIST dataset neural network performance with and without optimized hyperparameters using different hardware architectures like a mainstream CPU, mainstream GPU, cloud GPU, cloud CPU, and cloud TPU. The MNIST dataset based Convolutional Neural Network performed the best with the fastest execution time on cloud with TPU hardware acceleration.

### Instructions: 

1. Clone the CSCE_614_Term_Project repo (https://github.com/michellbrito/CSCE_614_Term_Project.git) 
2. Open the notebook file (CSCE_614_CNN_for_MNIST.ipynb) in Google Colab (recommended) or any Jupyter notebook.
3. If you are trying to run on Google Colab (cloud), go to Edit -> Notebook Settings -> Select the prefered Hardware Accelerator to test on Colab, for example: GPU. If you are trying to run on Google Colab (local), select the drop down on "Connect" to the right on the main screen and select "connect to local runtime". Follow the instructions to pair Jupyter to Colab. Otherwise, feel free to run this on Jupyter.
4. Install the required packages as needed.
5. Setting up "Measuring Metrics":
    a. Run the code below 
    b. Click on the link 
    c. Sign up (if needed)
    d. Copy the code it gives you 
    e. Paste it back in Colab
    f. Go back to the website, go to metrics. 
    g. You will be able to see the metrics from the website app.
6. Check the hardware spec of your current configuration if you prefer.
7. Load the MNIST dataset
8. Go through "Preprocessing and reshaping" section
9. Run the neural network with unoptimized hyperparameters
10. Running the hyperOpt section is not requried! It was already run and is ready for preview. Note that should you choose to run it, it will take a long time, even on a GPU.
11. The best hyperparameters provided by HyperOpt are now plugged into the same neural network. Run the "CNN Neural Network with optimized hyperparameters".
12. End metrics grabbing by wandb by running the last 

NOTE: There are two similar files in this repo. One is exclusively meant to be run on Google's TPU while the other file can run on GPU or CPU.
