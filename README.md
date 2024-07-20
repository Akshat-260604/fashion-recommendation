
---

## Fashion Recommender System

Welcome to the Fashion Recommender System project! This project leverages precomputed image embeddings to recommend similar fashion items based on a target image. 

### Key Features
- **Image Embeddings**: Utilizes VGG16 model embeddings to represent images as feature vectors.
- **Similarity Calculation**: Computes cosine similarity between image embeddings to find the most similar items.
- **Efficient Recommendation**: Quickly identifies and displays the top 5 similar images to a given target image.
- **User-Friendly Visualization**: Provides a clear visual representation of the target image alongside its recommended similar items.

### Technical Details
- **Embeddings Storage**: Image embeddings are stored in a CSV file for efficient access and manipulation. The embedding file might take up several hours and days in few cases if you're just reliable on your CPU. I have done that so I am providing you guys with the embedded file directly - https://drive.google.com/file/d/1_UVUZwprI35G7Wyo5wi2rnquP_ujfjgX/view?usp=sharing
- **Preprocessing**: Preprocessing steps are already done, and embeddings are directly used for similarity computation.
- **Model Training**: The VGG16 model was used to generate embeddings for a dataset of fashion images.
- **Dependencies**: Utilizes libraries such as TensorFlow/Keras, NumPy, Pandas, and Matplotlib for various tasks.

### How It Works
1. **Load Embeddings**: Reads the precomputed embeddings from `image_embeddings.csv` which is uploaded on the above provide gdrive link.
2. **Select Target Image**: Chooses a target image from the dataset.
3. **Calculate Similarity**: Computes the cosine similarity between the target image embedding and all other embeddings.
4. **Recommend Images**: Identifies and displays the top 5 most similar images to the target image.

### Getting Started
To run the recommender system, follow these steps:
1. Clone the repository.
2. Ensure you have the necessary dependencies installed.
3. Place your target image in the specified directory.
4. Run the recommendation script to see the results.

### Future Improvements
- **Expand Dataset**: Incorporate a larger and more diverse set of fashion images. I am linking the dataset that I used for this project. Here you go - https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-small. I am also sharing 'styles_cleaned.csv' above so that it reduces your workload.
- **Advanced Models**: Experiment with more advanced deep learning models for improved accuracy.
- **User Interface**: Develop a web or mobile interface for easier user interaction.

### Conclusion
This project showcases the power of image embeddings and similarity calculations in creating an efficient fashion recommender system. Whether you're a developer or a fashion enthusiast, this system provides a practical example of combining machine learning and fashion.

---

