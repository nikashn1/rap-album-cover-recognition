# Rap Album Cover Recognition Using Machine Learning

## Project Overview

Rap Album Cover Recognition is an image classification project developed using **Google Teachable Machine**. The project uses machine learning and computer vision to recognize and classify rap album covers from a collection of 32 albums.

Combining my interests in artificial intelligence, programming, and rap music, I developed and trained a model to identify album artwork from artists including Ken Carson, Playboi Carti, Travis Scott, Destroy Lonely, Don Toliver, and others.

The project explores how machine learning can recognize visual patterns, distinguish between different album designs, and associate images with their corresponding classifications.

## Project Statistics

- **32 album classes**
- **26,678 training images**
- **115 training epochs**
- **Batch size:** 16
- **Learning rate:** 0.00117
- **Platform:** Google Teachable Machine
- **Model format:** Keras (.h5)
- **Machine learning task:** Multiclass image classification

## Recognized Albums

The model was trained to recognize the following 32 rap albums, organized by artist.

### Ken Carson
1. A Great Chaos
2. More Chaos
3. Project X
4. X

### Playboi Carti
5. I AM MUSIC
6. Whole Lotta Red

### Destroy Lonely
7. </3² (Broken Hearts)
8. NO STYLIST
9. If Looks Could Kill
10. LOVE LASTS FOREVER

### Travis Scott
11. Rodeo
12. ASTROWORLD
13. JACKBOYS
14. UTOPIA
15. JACKBOYS 2

### Don Toliver
16. Heaven or Hell
17. Life of a DON
18. Love Sick
19. HARDSTONE PSYCHO

### Homixide Gang
20. Lifestyle
21. i5u5we5

### OsamaSon
22. Flex Musix
23. Jump Out

### SoFaygo
24. Pink Heartz
25. GO+

### Lil Baby
26. Street Gossip
27. My Turn

### Lil Baby & Gunna
28. Drip Harder

### Lil Baby & Lil Durk
29. The Voice of the Heroes

### Other Artists
30. Bad A** F****** Kid — Nettspend
31. Set It Off — Offset
32. So Much Fun — Young Thug

## How the Model Works

The project uses supervised machine learning to classify album cover images.

**1. Image Collection and Organization**

Images were organized into 32 categories, each representing a different rap album. The Teachable Machine project contains 26,678 training images across these categories.

**2. Model Training**

Using Google Teachable Machine, I trained an image classification model to recognize patterns in the collected images.

The model was trained over 115 epochs, using a batch size of 16 and a learning rate of 0.00117.

**3. Image Recognition**

When an image is supplied to the trained model, it produces classification scores corresponding to the 32 album categories.

**4. Classification Output**

The model can identify its highest-scoring album classification and provide scores for the other possible categories.

These scores help illustrate the model's relative confidence in its predictions.

## Technologies Used

- **Google Teachable Machine** — Training and exporting the image recognition model
- **TensorFlow / Keras** — Model framework and saved model format
- **Computer Vision** — Recognition and classification of album artwork
- **Supervised Learning** — Training with labeled album images
- **Image Classification** — Predicting album categories from image inputs
- **Git and GitHub** — Project documentation and version control
- **Git Large File Storage (LFS)** — Managing the original Teachable Machine project file

## Repository Files

| File | Description |
|---|---|
| `keras_rap_model.h5` | Exported trained image classification model |
| `labels.txt` | Names and class indices of the 32 albums |
| `projectRAP.tm` | Original Teachable Machine training project, including training images |
| `.gitattributes` | Git LFS configuration for large project files |
| `README.md` | Project documentation |

## How to Explore the Project

### Option 1: Teachable Machine

1. Visit [Google Teachable Machine](https://teachablemachine.withgoogle.com/).
2. Open an image project.
3. Import the `projectRAP.tm` project file.
4. Explore the album categories and training images.
5. Use Teachable Machine's preview and testing tools to evaluate the model.

**Note:** The `.tm` file is stored using Git LFS. Download the complete LFS file rather than its small Git pointer file.

### Option 2: Exported Keras Model

The repository also includes the exported `keras_rap_model.h5` file and its corresponding `labels.txt` file.

These files can be used to integrate the trained image classifier into a compatible Python machine learning application.

The repository currently provides the trained model and project data rather than a complete standalone application.

## Challenges and Learning Outcomes

This project allowed me to explore the practical application of machine learning to a subject I enjoy outside of academics.

Working with 32 different album categories introduced the challenge of distinguishing between a large number of visual classifications rather than making a simple binary prediction.

Through the project, I gained experience with:

- Organizing labeled image datasets
- Developing multiclass image classification models
- Training and exporting machine learning models
- Understanding model predictions and confidence scores
- Working with Keras model files
- Managing large machine learning project files
- Applying artificial intelligence to a personal interest

## Future Improvements

Potential future developments include:

- Creating an interactive web application where users can upload album covers
- Displaying the top three predicted albums and their classification scores
- Evaluating model accuracy using a separate testing dataset
- Building a confusion matrix to identify frequently misclassified albums
- Expanding recognition to additional artists and album releases
- Improving recognition under different lighting, cropping, and image-quality conditions

## Project Motivation

Music has always been one of my interests, particularly the production styles and visual identities associated with different rap artists.

I wanted to explore how artificial intelligence could recognize something that music listeners often identify immediately: an album simply by looking at its cover.

This project gave me an opportunity to connect my interest in music with machine learning, turning a personal curiosity into a practical computer vision project.

## Author

**Nikash Nemmara**

Machine learning enthusiast interested in artificial intelligence, computer vision, programming, and the intersection of technology with creative interests.

---

*This is an independent educational machine learning project developed using Google Teachable Machine. Album artwork and artist names belong to their respective rights holders.*
