Title of Project:
Automated Detection of Rice Leaf Diseases

Overview of the Project
The annual yield of rice significantly influences India's political, economic, and social stability. According to a study by the International Rice Research Institute (IRRI), diseases are responsible for approximately 37% of rice crop losses. Consequently, farmers face significant challenges in promptly identifying and treating crop diseases. Implementing an automated method for detecting and identifying diseases in large fields can alleviate some of the farmers' workload, saving time and money by reducing the need for manual inspection and analysis of disease symptoms. This research aims to develop a multiclass Support Vector Machine (SVM)-based technique for accurately identifying and detecting rice leaf diseases. Utilizing image processing methods, diseases can be swiftly categorized, enabling quick diagnosis and treatment. This approach can potentially enhance agricultural output through early disease intervention. The process includes steps such as preprocessing, segmentation, feature extraction, and image capture.

Our method employs a knowledge base with sample images, divided into 80% for training and 20% for testing, to train a classifier. Classification techniques are then applied to identify and diagnose specific plant diseases.

Installation
bash
Copy code
  clone the project
Requirements
numpy
Pillow
scikit-learn
scikit-image
Deployment
Open the command prompt in the working directory and run:

bash
Copy code
   pip install -r requirements.txt
To run the project, execute:

bash
Copy code
   python Rice_Leaves_Disease_Detection_GUI.py
and test it.

