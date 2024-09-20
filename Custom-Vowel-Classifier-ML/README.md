**Multilingual Vowel Classifier**

This project is a language-translation prototype aimed at classifying vowels from five languages: Chinese, Russian, Korean, Greek, and Japanese, and predicting their corresponding English characters.

Key features:
- Users can draw vowels on a provided canvas, and the system processes and classifies the drawn images using pre-trained models or trains new ones.
- You can choose from various machine learning models, including LinearSVC, KNeighbors, RandomForestClassifier, DecisionTreeClassifier, LogisticRegression, and GaussianNB, to train and predict the corresponding English characters with varying degrees of precision.
- The training dataset consists of over 800 images of vowels from the mentioned languages.
- **PIL (Python Imaging Library)** is used for opening, manipulating, and saving images, while **OpenCV** handles reading and processing images.
- **NumPy** is used for creating arrays to store images and classes for training the model.
- **scikit-learn** is used for importing machine learning algorithms and performing training and testing operations.
- **Tkinter** is used to create a user-friendly graphical interface for easy interaction.
- The **Pickle** module is used to save and load the trained models, enabling the use of pre-trained datasets for efficient predictions.

This project expands the use of drawing classification for language translation through machine learning and image processing, offering a user-interactive tool for multilingual vowel recognition.

![WhatsApp Image 2024-09-20 at 19 52 38_51e9a5da](https://github.com/user-attachments/assets/7e4991f5-24ef-443c-9076-c0aa14eb28d2)
