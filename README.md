# Trash Classification and Disposal Application 
This application utilizes computer vision and natural language processing to classify different types of trash and provide disposal instructions. It aims to assist users in properly disposing of various waste materials by accurately identifying the type of trash and suggesting the appropriate disposal method.

## Motivation
The motivation behind this project is to address the growing environmental concerns associated with waste management. Improper disposal of trash can have adverse effects on the environment, including pollution, contamination, and depletion of natural resources. This application aims to promote responsible waste management practices and encourage users to adopt sustainable waste disposal methods.

## Features
Trash Classification: The application employs a deep learning model trained on a diverse dataset of waste materials. It can accurately classify items into different categories such as cardboard, glass, metal, paper, plastic, and trash.
Disposal Instructions: Based on the classified trash item, the application provides clear and concise disposal instructions. These instructions guide users on how to properly dispose of the item, whether it should be recycled, placed in specific recycling containers, or discarded in regular trash bins.

## Usage
1. Clone the repository to your Google Colab drive environment by running the following command: 
   !git clone https://github.com/NoemiRyf/ML2_Project.git
2. Open the Trash_Sorting_Images.ipynb notebook located in the code folder. Make sure to adjust the paths in the notebook if necessary to match the location of the dataset and any other required files.
3. Run the Trash_Sorting_Images.ipynb notebook step by step. This notebook utilizes computer vision techniques to classify trash items. Follow the instructions provided in the notebook to process the images and obtain classification results.
4. After completing the image classification, you can open the Trash_Sorting_NLP.ipynb notebook from the code folder. Again, make sure to adjust the paths in the notebook if necessary to match the location of any required files.
5. Run the Trash_Sorting_NLP.ipynb notebook step by step. This notebook utilizes natural language processing techniques to generate disposal instructions based on the classified trash items. 

## Technologies Used
Computer Vision: TensorFlow, Keras, Convolutional Neural Networks (CNN), ResNet
Natural Language Processing: Hugging Face Transformers, GPT-2 Language Model
Image Processing Libraries: OpenCV, PIL
Python Libraries: NumPy, Pandas

## Dataset
The trash classification model was trained on a diverse dataset of waste materials, including images of cardboard, glass, metal, paper, plastic, and trash items. The dataset is from this repository: https://github.com/garythung/trashnet.

## Future Enhancements
Model Performance Improvement: Continuously refine and fine-tune the trash classification model to enhance accuracy and robustness. For example with using more data for training.
Additional Waste Categories: Extend the application to classify and provide disposal instructions for additional waste categories, such as organic waste, hazardous materials, and electronic waste.
User-Friendly Interface: Enhance the user interface to make it more intuitive and user-friendly, allowing users to interact with the application seamlessly.
