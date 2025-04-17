# **CNN AI Detection COVID-19 Chest X-Ray Classification**
-------------------
The COVID-19 pandemic, which began in December 2019, quickly escalated into one of the deadliest and most disruptive global health crises in modern history. While many individuals infected with the virus experience mild to moderate symptoms—such as fever, cough, headache, and loss of smell or taste—a substantial number suffer from severe or even critical conditions. Beyond the staggering loss of life, the pandemic has profoundly impacted public health systems, economies, and day-to-day life around the world.
To support the medical community in diagnosing and managing the disease, deep learning techniques have been increasingly applied in medical imaging. In particular, Convolutional Neural Networks (CNNs) have shown promise in classifying chest X-ray images to detect signs of COVID-19. These models help radiologists by distinguishing between healthy lungs, viral pneumonia, and COVID-19-related lung infections.
Objective
The goal of this project is to develop a Convolutional Neural Network (CNN) that can accurately classify chest X-ray images into three categories:
    COVID-19 positive
    Viral Pneumonia
    Normal (healthy)
This model can be used as a diagnostic aid to help identify patients affected by COVID-19 or related respiratory illnesses.
Data Description
    The dataset contains preprocessed training images for three categories, stored as NumPy arrays.
    The three image classes are:
        COVID-19: X-rays of patients who tested positive for COVID-19
        Viral Pneumonia: X-rays showing pneumonia with viral origins, which may mimic COVID-19 symptoms
        Normal: X-rays of healthy individuals with no signs of infection
    The dataset files are named:
        CovidImages.npy: Contains image data
        CovidLabels.csv: Contains corresponding labels
❗ Note: It is recommended to use a GPU runtime to ensure efficient execution of the training process.
