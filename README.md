# Pulmonary-radiography-CNN
CNN neural network for classifier more of one class like 'COVID', 'Lung_Opacity', 'Normal', 'Viral Pneumonia'. For build this CNN I used transfer learning and fine tuning with the archictecture VGG 19 and keras turner for found the best hyperparameters.

* the notebook called radiografias_pulmones contains the model and the results, and the notebook called chestRay shows us the process to find the best hyperparameters using keras turner

The idea is to create a backend rest api deployed in AWS and a frontend to upload the radiological images to make the predictions, we will see this in future versions.
