# Deep Learning Image Segmentation (Horizon Segmentation)

Welcome to the "Deep Learning Image Segmentation (Horizon Segmentation)" repository! This project represents an in-depth exploration of deep learning techniques for image segmentation, specifically focusing on the task of distinguishing between the sea and the sky in image data. The work was completed as part of the coursework at the University de Toulon under the guidance of Professor Arnaud Pietrosemoli.
### Google Colab
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1nlb0lmy1Vjp-j6qzvD82GZkLJK4pGjr8#scrollTo=vDJuDBXqPxsB)

## Introduction

### Problem Statement
Image segmentation is a fundamental computer vision task that involves partitioning an image into distinct regions based on certain characteristics or criteria. In this project, the goal is to develop a deep learning model, specifically a UNET model, capable of segmenting images and distinguishing between the sea and the sky in each image. This task is essential in various applications, such as autonomous navigation for drones or sailboats.

### Approach
We will implement and train a UNET model, a popular architecture for image segmentation tasks. UNET is known for its ability to capture fine-grained details while maintaining spatial context. By leveraging this architecture, we aim to achieve accurate and reliable horizon segmentation.

## Tasks

### Model Development
- Implement the UNET model architecture, including encoder and decoder components.
- Define the loss function suitable for image segmentation tasks.
- Prepare the dataset, ensuring proper labeling and splitting into training and validation sets.
- Train the UNET model on the dataset, monitoring key metrics such as loss and accuracy.
- Perform model evaluation on the validation set to assess its performance.

### Hyperparameter Tuning
- Experiment with various hyperparameters, such as learning rate, batch size, and network depth.
- Analyze the impact of hyperparameter changes on model performance and convergence speed.

### Inference and Visualization
- Deploy the trained UNET model for inference on new images.
- Visualize the segmentation results to assess the model's accuracy and identify any areas for improvement.

### Documentation
- Provide clear and detailed documentation on how to replicate the experiment, including dataset preparation, model training, and inference.
- Include visualizations and explanations to help users understand the segmentation results.

## Usage

To get started, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/eather0056/Deep-Learning-image-segmentation-horizon-segmentation.git
   cd Deep-Learning-image-segmentation-horizon-segmentation
   ```

2. Set up the required environment and dependencies (provide instructions or scripts if necessary).

3. Prepare your dataset and ensure it is properly labeled.

4. Train the UNET model using the provided code or your own customizations.

5. Evaluate the model's performance and fine-tune hyperparameters if needed.

6. Deploy the trained model for inference on new images.

7. Document your experiments and results for future reference.


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

We would like to express our gratitude to Professor Arnaud Pietrosemoli for the guidance and support provided throughout this class project.
