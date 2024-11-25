# **Yelp Dataset Generative Models and Sentiment Analysis Project**

## **Project Overview**
This project involves building and evaluating generative models to create images based on the Yelp dataset and implementing sentiment analysis using various deep learning techniques. The repository includes generative models such as DCGAN, WGAN, VAE, and cGAN for image generation, as well as CNN and Transformer-based models for sentiment classification.

The project is organized into three main branches: **Development**, **Testing**, and **Production**, to ensure a clear workflow from experimentation to deployment.


## **Dataset**
The dataset used in this project is the **Yelp Dataset**, which provides:
- Images categorized into labels such as `food`, `drink`, `inside`, and `outside`.
- Text reviews for sentiment analysis.

### **Source**
The dataset is available from the **Yelp Dataset Challenge**.  
You can access the dataset here: [Yelp Open Dataset](https://www.yelp.com/dataset/download).

### Demo Video

[Click here to view the demo videos](https://azureloyalistcollege-my.sharepoint.com/:f:/g/personal/dhanushchandarsiv_loyalistcollege_com/Es6bUZVuBF1NrULP-tQZzKcBD29mypBayyXjX4kB7GtB2w?e=LVYPUe)



## **Models Implemented**

### **Generative Models**
1. **DCGAN (Deep Convolutional GAN)**:
   - Generates realistic images using convolutional neural networks.

2. **WGAN (Wasserstein GAN)**:
   - Improves stability and addresses mode collapse in GANs.

3. **VAE (Variational Autoencoder)**:
   - Learns latent representations to generate images.

4. **cGAN (Conditional GAN)**:
   - Generates images conditioned on labels (`food`, `drink`, `inside`, `outside`).

### **Evaluation Metrics**
- **Inception Score (IS)**: Measures the quality and diversity of generated images.
- **Frechet Inception Distance (FID)**: Compares generated images to real ones for similarity.


### **Sentiment Analysis Models**
1. **CNN**: A Convolutional Neural Network for text-based sentiment classification.
2. **Transformer Models**:
   - Pretrained models such as Causal Transformer with Postional Encoding and Relative Postional Encoding .


## **How to Run the Project**

### **Step 1: Clone the Repository**
```bash
git clone https://github.com/your-org/yelp-project.git
cd yelp-project
```

### **Step 2: Set Up the Environment**
Install the required dependencies:
```bash
pip install -r requirements.txt
```

### **Step 3: Run Jupyter Notebooks**
- Open the Jupyter notebooks in `notebooks/` for each model.
- Follow the instructions in the notebooks to train or test models.

### **Step 4: Deployment**
- Deployment scripts are available in the `deployments/` folder.
- Use `Flask` or `FastAPI` to deploy your models locally or on a cloud server.



## **Generated Images**
Each generative model produces images, which are evaluated using IS and FID. Examples are available in the `results/` folder.



## **Contributors**
- Ayesha Mohammed Yunus Q
- Dhanush Chandar Sivakumar
- Hassaan Chishti
- Janvi Satishbhai Rai
- Oluwakanyinsola Ifeoluwa Adebanjo
- Rajeesh Jayaraman
- Rithwik Prem
- Sucheta Adhikary
- Sweatha Palani


## **License**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
