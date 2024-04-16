#DATASET:
Food-101

#SOURCE:
● The Food-101 dataset was introduced by Lukas Bossard, Matthieu Guillaumin,
Luc Van Gool, et al. in their paper "Food-101 – Mining Discriminative
Components with Random Forests" .
● It is designed for food recognition through image analysis.
● Link:https://paperswithcode.com/dataset/food-101

#DESCRIPTION:
● Introduced by Lukas Bossard and co-authors in their work on identifying key
components in foods using random forests.
● Comprises 101 distinct categories of food.
● Each category features 750 images for training and 250 for testing, totaling
101,000 images.
● Test image labels have been carefully verified, while the training set might
include some inaccuracies.
● Aimed at advancing food recognition technology through detailed image analysis.

#IMAGE SELECTION CRITERIA:
● Images must prominently feature food from the specified 101 categories.
● High-resolution and clear images are required for precise classification.
● Food items should be the main focus, with minimal distraction from the
background.

#CLASSIFICATION APPROACH:
Sorting images into 101 predefined food groups is the core of the classification process.
It involves the detection of distinctive visual cues tied to various food items.
Utilizes advanced deep learning techniques for pattern recognition.
Essential preprocessing techniques include image resizing, pixel value normalization, and applying various data augmentation strategies. These techniques enhance the predictive performance and generalization of the models across diverse food item presentations.

#DESCRIPTIVE STATISTICS:
● Introduces a dataset featuring 101 food categories with a total of 101,000
images.
● Provides 250 test images per category, each manually reviewed for accuracy.
● Includes 750 training images per category, intentionally left with some noise, such as intense colors and occasional incorrect labels, to introduce challenges.
● All images are resized to have a maximum side length of 512 pixels, ensuring consistency in image scale.

#PREPROCESSING:
● Resizing: Adjusting images to a uniform size for model input.
● Normalization: Scaling pixel values to a range between 0 and 1.
● Data Augmentation: Applying techniques like rotation, flipping, and zooming to
increase the diversity of the training set and improve model robustness.
● Color Space Adjustments: Experimenting with different color spaces (e.g., RGB
to HSV) for potentially better performance.
