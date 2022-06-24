# Respiratory Motion Compensation for image-guided percutanous procedures using surrogate signals

The aim of this project is to develop a respiratory motion estimation model using different surrogate signals.

Organ motion affects the accuracy of image-guided percutanous procedures taking place in the abdominal/thoracic area.

![image1](https://user-images.githubusercontent.com/72251458/175567988-a2a5f49f-d652-49e4-9acb-5a2e157531b6.png)


Current imaging modalities are unable to accurately locate tumour sites with simultaneous high temporal and spatial resolution.
These innaccuracies affect the outcome and process of diagnostic and therapeutic procedures such as liver biopsy and ablation.

![Screenshot from 2022-06-24 13-35-43](https://user-images.githubusercontent.com/72251458/175526860-42ba1428-38fb-4f79-8c2a-852bd7063e91.png)


The objective of this project consists in creating a motion model that provides realtime accurate localisation of the site of interest. 
The motion model is created using an external surrogate signal and ground truth data provided by CT or MRI images.

![image2](https://user-images.githubusercontent.com/72251458/175568036-54ba733f-340f-4b20-b41f-97cbb278863e.png)


The current surrogate signals that are explored in this project are:
- RGB-D camera


![Screenshot from 2022-06-24 13-32-21](https://user-images.githubusercontent.com/72251458/175526440-e65db083-79a3-4fca-907e-9702aaaedf61.png)


- Ultrasound transducer


