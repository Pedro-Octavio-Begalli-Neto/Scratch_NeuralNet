# Scratch_NeuralNet
This notebook builds a NumPy-based neural network to classify MNIST handwritten digits. It utilizes ReLU and Softmax activations to reach 85.1% training accuracy over 1,000 iterations. The final model achieves an 84.6% validation accuracy and includes visual prediction samples.

# Prerequisites
Ensure you have Python installed along with numpy, pandas, and matplotlib. You will also need the train.csv dataset from the MNIST digit recognition challenge.

# Setup and Execution
Data Placement: Place the train.csv file in your Downloads folder or the same directory as the notebook.

Run Cells: Execute the notebook cells sequentially to load the data, which includes 42,000 samples with 785 columns (1 label and 784 pixels).

Training: The gradient_descent function will run for 1,000 iterations, normalizing pixels and updating weights to minimize error.

Inference: Use the forward_propagation function on the X_val array to predict digits for new images and visualize them using plt.imshow.


Dowload this archive and paste it in the folder: https://drive.google.com/file/d/1kobc4-1jZlOBOZBf52NNDPgosnuJD84S/view
