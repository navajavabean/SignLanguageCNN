# Sign Language Recognition with CNN

This project was part of a group assignment in my Machine Learning class. The goal was to learn how to use a CNN (Convolutional Neural Network) to recognize sign language from images. The model performed well, achieving an accuracy of **92.49%** on the test set. However, there are areas where it could be improved, especially for signs like **Class 17**, which were harder for the model to identify correctly.

---

## What I Learned

- **How CNNs Work:** I learned how convolutional layers help extract features from images, like edges and patterns, to identify different signs.
- **Handling Data:** I gained experience preparing datasets, normalizing pixel values, and reshaping data for machine learning.
- **Evaluating Models:** I learned how to measure performance using metrics like accuracy, classification reports, and confusion matrices.
- **Problem Solving:** I realized the importance of identifying issues like class imbalance and misclassification to improve the model.

---

## Key Takeaways from the Model

### Observations
- The model works well for most signs, but it struggles with some, especially **Class 17** and **Class 12**.
- These errors are likely because some signs look very similar, making them harder to distinguish.
- Some classes didn’t have enough examples in the dataset, which may have caused the model to perform poorly on those.

### Insights
- The model’s performance for most signs was strong, but certain challenging signs need more attention.
- For **Class 17**, the model might benefit from better-quality data or more training examples.

---

## How I Can Improve the Model

1. **Make More Training Data (Data Augmentation):**
   - Create new images by slightly rotating, flipping, or zooming in on the existing ones. This will help the model learn to recognize signs from different angles and conditions.

2. **Adjust the Model for Imbalance (Class Weighting):**
   - Give more weight to underrepresented classes so the model pays more attention to them during training.

3. **Make the Model Smarter (Model Enhancements):**
   - Add more layers to the CNN to help it detect finer details in the images.
   - Use dropout and batch normalization to make training more stable and prevent overfitting.

4. **Fix the Hard Signs (Focus on Misclassified Classes):**
   - Analyze why the model is confusing certain signs, like Class 17 and Class 12, and create more examples of those signs.

5. **Tweak the Settings (Hyperparameter Tuning):**
   - Experiment with different learning rates, batch sizes, and training methods to find what works best.

---

## Tools Used
- **Programming:** Python
- **Libraries:**
  - PyTorch: For building and training the CNN.
  - NumPy and Pandas: For handling data.
  - Matplotlib and Seaborn: For visualizing the data and results.
  - Scikit-learn: For splitting data and evaluating performance.

---

This project gave me hands-on experience with CNNs and a better understanding of how to improve machine learning models. I’m excited to keep learning and applying these techniques to future challenges.

