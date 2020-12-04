# CSCE 614 Term Project

### Team Members: 
Aaryan Kothapalli, Michell Brito

### Paper: 
Hardware for Machine Learning: Challenges and Opportunities - https://arxiv.org/pdf/1612.07625.pdf

### Abstract: 
Machine learning has boomed in recent years and has introduced new challenges that have arrived from having to analyze a lot of big data. Some of these challenges are power consumption, cost, and also bandwidth. These challenges can be addressed at various levels of hardware design ranging from architecture, hardware-friendly algorithms, mixed-signal circuits, and advanced technologies.

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
