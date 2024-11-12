<div align="center">

![AI Fashion Recommender](https://github.com/user-attachments/assets/48c283eb-b162-4cfe-ae09-6861cee7733d)

</div>

## Table of Contents

1. [Objective](#objective)
2. [Outputs](#outputs)
3. [Advantages](#advantages)
4. [Technical Aspects](#technical-aspects)
5. [Dataset](#dataset)
6. [Installation](#installation)
7. [Usage](#usage)
8. [Applications](#applications)
9. [Contributing](#contributing)

## Objective

The **AI Fashion Recommender** project aims to provide personalized fashion recommendations based on the visual similarity of clothing items. Leveraging deep learning techniques, this recommender system analyzes fashion images and computes embeddings to find similar products, enhancing the shopping experience for users.

## Outputs
 
![Screenshot 2024-10-19 170302](https://github.com/user-attachments/assets/a9a3fb73-aa6b-4f06-8a34-3f8eaf3849e7)

![Screenshot 2024-10-19 171131](https://github.com/user-attachments/assets/afd5131c-7aef-4bef-8c86-1635732618dc)

![Screenshot 2024-10-19 170428](https://github.com/user-attachments/assets/e0723563-e629-4445-a4d9-7ad67cb7afad)

![Screenshot 2024-10-19 171332](https://github.com/user-attachments/assets/f67ab780-2872-4471-997e-fca82a6657ca)


## Advantages

- **Personalized Recommendations**: The system suggests items based on visual similarity, making it easier for users to discover new products they may like.
- **User Engagement**: By showcasing similar products, it encourages users to explore more items, increasing overall engagement.
- **Data-Driven Insights**: The model learns from a large dataset, ensuring that recommendations are grounded in real-world fashion trends.
- **Scalability**: This recommender system can easily scale with additional data, improving accuracy and user satisfaction over time.

## Technical Aspects

- **Deep Learning Framework**: Built using PyTorch and torchvision for efficient deep learning model training and image processing.
- **Pre-trained Model**: Utilizes a pre-trained ResNet-18 model for feature extraction from fashion images.
- **Cosine Similarity**: Implements cosine similarity to measure the similarity between item embeddings, facilitating effective recommendations.
- **Image Processing**: Employs OpenCV for image loading and preprocessing, ensuring high-quality input for the model.
- **Data Handling**: Utilizes Pandas for data manipulation, making it easy to work with the dataset.

## Dataset

The dataset used for this project is the [Fashion Product Images Dataset](https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-dataset/data) available on Kaggle. It contains a rich collection of fashion images, which are essential for training and evaluating the recommendation model.

### Dataset Structure

- The dataset includes images and corresponding metadata such as product categories, attributes, and IDs.
- Images are stored in a structured directory format, which facilitates easy loading and processing.

## Installation

To set up the project environment, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/prajwalk-1/AI-Fashion-Recommender.git
   cd AI-Fashion-Recommender
   ```

2. Install the required packages using pip:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

To run the recommendation system:

1. Ensure you have downloaded the dataset from Kaggle and placed it in the appropriate directory as indicated in the code.
2. Open the Jupyter Notebook named **ai-fashion-recommender.ipynb**.
3. Execute the notebook cells sequentially to process images, extract embeddings, and generate recommendations.

## Applications

- **E-commerce**: Enhance online shopping platforms by providing users with tailored product recommendations based on their preferences and browsing history.
- **Fashion Retail**: Assist retailers in promoting similar items to customers, improving sales and customer satisfaction.
- **Personal Stylist**: Develop applications that serve as personal stylists, suggesting outfits based on user preferences and existing wardrobe items.

## Contributing

Contributions are welcome! If you'd like to contribute to the project, please fork the repository and submit a pull request. You can also open issues for suggestions or bug reports.

