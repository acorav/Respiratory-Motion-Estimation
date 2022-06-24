# Respiratory-Motion-Estimation
Respiratory Motion Compensation for image-guided percutanous procedures using surrogate signals. 

The aim of this project is to develop a respiratory motion estimation model using different surrogate signals.

Organ motion affects the accuracy of image-guided percutanous procedures taking place in the abdominal/thoracic area.
![Screenshot from 2022-06-24 13-32-08](https://user-images.githubusercontent.com/72251458/175526375-625cd546-81ef-4bdd-8ce2-c91dd737c147.png)

Current imaging modalities are unable to accurately locate tumour sites with simultaneous high temporal and spatial resolution.
This innaccuracies effect the outcome and process of diagnostic and therapeutic treatments such as liver biopsy and ablation.
![Screenshot from 2022-06-24 13-35-43](https://user-images.githubusercontent.com/72251458/175526860-42ba1428-38fb-4f79-8c2a-852bd7063e91.png)


The objective of this project consists in creating a motion model that provides realtime accurate localisation of the site of interest. 
The motion model is created using an external surrogate signal and ground truth data provided by CT or MRI images. 
![Screenshot from 2022-06-24 13-31-46](https://user-images.githubusercontent.com/72251458/175526499-f4a1b1e9-d7c3-42af-9876-dd1c000528e2.png)

The current surrogate signals that are explored in this project are:
- RGB-D camera


![Screenshot from 2022-06-24 13-32-21](https://user-images.githubusercontent.com/72251458/175526440-e65db083-79a3-4fca-907e-9702aaaedf61.png)


- Ultrasound transducer


