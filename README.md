# Blood_Vessel_Segmentation Using Unet Architecture
Blood Vessel Segmentation of Diabetic Retinopathy Fundus Image. The dataset on the Unet model Tested is Messidor
In this project, we present a approach for segmenting blood vessels from retinal fundus images using the popular UNet architecture. The UNet model has been widely recognized for its outstanding performance in medical image segmentation tasks. Leveraging this powerful architecture, we aim to accurately identify and extract blood vessels from retinal fundus images, which is crucial for diagnosing various eye-related diseases and conditions.  

Retinal fundus images contain valuable information about the blood vessels in the eye's retina. Accurate segmentation of these vessels can aid in the early detection and monitoring of various retinal pathologies, including diabetic retinopathy and glaucoma.
Our project focuses on leveraging the UNet architecture to perform pixel-wise segmentation of blood vessels in retinal fundus images. By training the model on a large dataset of annotated fundus images, we enable the network to learn the intricate patterns and characteristics of blood vessels. Once trained, the UNet model can then be used to automatically segment blood vessels in unseen fundus images, assisting healthcare professionals in making faster and more precise diagnoses.
<h2>Here is the segmented image picture<h2>

<img src="https://user-images.githubusercontent.com/68460013/236637428-01478ca1-333d-4a13-8322-15e3e1c06dd0.png" alt="Segmented Image">

<h2>Project Highlights</h2>
<ul>
  <li>Utilized the UNet architecture for retinal fundus image blood vessel segmentation.</li>
  <li>Preprocessed and augmented the dataset to enhance model robustness.</li>
  <li>Implemented a pixel-wise cross-entropy loss function to train the model effectively.</li>
  <li>Leveraged transfer learning techniques for improved generalization and performance.</li>
  <li>Conducted extensive hyperparameter tuning to optimize model accuracy.</li>
  <li>Evaluated the model on a separate test set and quantified its performance using various metrics (e.g., Jaccard index).</li>
  <li>Deployed the trained model in a user-friendly interface for easy interaction and visualization.</li>
</ul>
UNet is a convolutional neural network (CNN) architecture. The architecture of UNet is characterized by its unique U-shaped design, which consists of an encoding path and a decoding path. The encoding path involves a series of convolutional and pooling layers that progressively reduce the spatial dimensions of the input image while capturing essential features. The decoding path, on the other hand, involves upsampling and concatenation operations to restore the spatial resolution and produce the final segmentation map. UNet is known for its ability to effectively capture both local and global context, making it well-suited for segmentation tasks where precise boundary delineation is required. Its skip connections between the encoding and decoding paths enable the propagation of feature information, allowing the model to maintain high-resolution details throughout the process.
Unet architecture:
<img src= "https://www.mdpi.com/machines/machines-10-00327/article_deploy/html/images/machines-10-00327-g001.png" alt= "Unet Arch">



