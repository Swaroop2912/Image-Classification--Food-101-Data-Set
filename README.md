## DATASET: Food-101

## SOURCE:
- The Food-101 dataset was introduced by Lukas Bossard, Matthieu Guillaumin, Luc Van Gool, et al. in their paper "Food-101 – Mining Discriminative Components with Random Forests". 
- It is designed for food recognition through image analysis.
- [Read the paper here](https://paperswithcode.com/dataset/food-101)

## DESCRIPTION:
Introduced by Lukas Bossard and co-authors, this dataset focuses on identifying key components in foods using random forests. It includes:
- **101 distinct categories** of food.
- **750 training images** and **250 testing images** per category, totaling **101,000 images**.
- Test image labels have been carefully verified, while the training set may include some inaccuracies.
- Aimed at advancing food recognition technology through detailed image analysis.

## IMAGE SELECTION CRITERIA:
- Images must prominently feature food from the specified 101 categories.
- High-resolution and clear images are required for precise classification.
- Food items should be the main focus, with minimal distraction from the background.

## CLASSIFICATION APPROACH:
Sorting images into 101 predefined food groups is the core of the classification process. This involves:
- Detection of distinctive visual cues tied to various food items.
- Utilization of advanced deep learning techniques for pattern recognition.
- Essential preprocessing techniques include image resizing, pixel value normalization, and applying various data augmentation strategies. These enhance the predictive performance and generalization of the models.

## DESCRIPTIVE STATISTICS:
Introduces a dataset featuring:
- **101 food categories**
- **101,000 images**
- **250 test images** per category, each manually reviewed for accuracy.
- **750 training images** per category, with some noise to introduce challenges.
- All images are resized to have a maximum side length of **512 pixels**.

## PREPROCESSING:
- **Resizing**: Adjusting images to a uniform size for model input.
- **Normalization**: Scaling pixel values to a range between 0 and 1.
- **Data Augmentation**: Applying techniques like rotation, flipping, and zooming to increase the diversity of the training set and improve model robustness.
- **Color Space Adjustments**: Experimenting with different color spaces (e.g., RGB to HSV) for potentially better performance.
