This is an online signature verification model that enhances security in banking, legal, and business transactions. It leverages Multilayer Perceptron (MLP) and 
Convolutional Neural Networks (CNNs) to distinguish between genuine and forged signatures with high accuracy. Using the CEDAR dataset which is a public dataset, of 
1,320 real and 1,320 forged signatures, the system applies preprocessing techniques like binarization, noise removal, and slant normalization to enhance clarity.

The model extracts key features such as stroke curvature, direction, and pressure, with MLP handling feature extraction and CNN refining pattern recognition. During verification, 
a theta value is computed from the signature’s curve and compared with stored data to authenticate signatures. The system achieved 95% accuracy, validated using Receiver 
Operating Characteristic (ROC) curves and Area Under Curve (AUC) analysis, ensuring a low false positive rate and reliable fraud detection.

Future improvements include deeper MLP structures, data augmentation techniques, and adaptive learning rate methods like ADAM. Additionally, ensemble learning using classifiers 
like Support Vector Machines (SVMs) could further enhance accuracy. In conclusion, this signature verification system offers a robust, AI-driven approach to preventing forgery,
making it highly valuable for secure authentication in finance, legal, and identity verification applications.

The public Dataset used - https://www.kaggle.com/datasets/shreelakshmigp/cedardataset
