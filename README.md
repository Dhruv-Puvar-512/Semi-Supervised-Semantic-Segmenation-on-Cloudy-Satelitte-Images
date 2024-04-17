# README

## Semi-Supervised Semantic Segmentation on Cloudy Satellite Images

This repository contains the implementation of a semi-supervised semantic segmentation model tailored for cloudy satellite images. The model is designed to address the challenges of limited labeled data by leveraging neural networks augmented with a clustering layer.

### Abstract

Semantic segmentation is a crucial task in computer vision, with applications ranging from object recognition to image classification. This paper focuses on semi-supervised semantic segmentation, aiming to enhance accuracy and robustness by leveraging limited labeled data. The proposed model utilizes neural networks with a clustering layer for adaptivity and joint algorithm optimization.

### Implementation Details

The study is conducted on the 38-cloud dataset, which comprises cloudy satellite images. Three models are implemented: UNet, Attention UNet, and ASPP-UNet. These models serve as the baseline for the semi-supervised methods.

### Results

The results of the experiments are provided below:

- **UNet with Clustering output:**

  ![UNet with Clustering output](https://github.com/Dhruv-Puvar-512/Semi-Supervised-Semantic-Segmenation-on-Cloudy-Satelitte-Images/blob/main/results/Unet%20with%20Clustering%20output.png)

- **UNet-ASPP with Clustering output**: 

  ![UNet with Clustering output](https://github.com/Dhruv-Puvar-512/Semi-Supervised-Semantic-Segmenation-on-Cloudy-Satelitte-Images/blob/main/results/Unet-ASPP%20with%20Clustering%20output.png)

-  **UNet-ASPP with Clustering output**: 

  ![UNet with Clustering output](https://github.com/Dhruv-Puvar-512/Semi-Supervised-Semantic-Segmenation-on-Cloudy-Satelitte-Images/blob/main/results/Unet-Attention%20with%20Clustering%20output.png)

### How to Use

To use the code and replicate the experiments:

1. Clone the repository:

   ```
   git clone https://github.com/your-username/your-repository.git](https://github.com/Dhruv-Puvar-512/Semi-Supervised-Semantic-Segmenation-on-Cloudy-Satelitte-Images
   ```

2. Navigate to the cloned directory:

   ```
   cd Semi-Supervised-Semantic-Segmenation-on-Cloudy-Satelitte-Images
   ```

3. Run the provided scripts to train and evaluate the models.

### Citation

If you find this work useful in your research, please consider citing:

```
@article{your-article-citation,
  title={Semi-Supervised Semantic Segmentation on Cloudy Satellite Images},
  author={Author(s)},
  journal={Journal/Conference},
  year={Year},
}
```

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Contact

For any inquiries or issues regarding the code, feel free to contact:

- Your Name: [your.email@example.com](mailto:dhruvpuvar512@gmail.com)
- Co-author Name: [coauthor.email@example.com](mailto:dhruvpuvar512@gmail.com)

---
