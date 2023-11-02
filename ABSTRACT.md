The **Panoramic Dental X-rays With Segmented Mandibles** dataset provides segmentation of mandibles in panoramic X-rays capturing their anatomical structures. It is composed of almost 2000 digital panoramic X-rays in BMP format of ∼2900×1250 pixels taken by the Soredex CranexD digital panoramic X-ray unit. All the images were taken for diagnostic purposes and treatment planning and no radiography record was taken for the purpose of this study. Two subsets were selected from the original set, but prior to selection, some exclusion criteria were applied to narrow down the sample size. Records with implants were excluded. Also, to ensure that no deciduous tooth was present in the images and that the growth of the jaw had almost completed, patients below 20 years of age were excluded from the dataset. Low-quality X-rays, which were blurred or malposed due to a technician’s error or patient’s lack of cooperation, were also excluded from the dataset.

For the first subset, a maxillofacial radiologist sorted out the panoramic x-rays based on several qualitative features such as the width of ramuses, the vertical distance between the alveolar process and inferior border of the mandible, the acuteness of gonial angle (n), overall convexity of inferior border (g), whether there was a concavity around the gonial angle, shape of coronoid process (m), shape of condyles (p), and depth of sigmoid notch (e). She then purposefully selected 116 images to cover all varieties of mandible shapes seen on panoramic X-rays regarding these criteria. These images were considered templates of the atlas.

![Fig. 2](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4652330/bin/JMI-002-044003-g002.jpg)

For the second subset, 30 images were chosen randomly from the same large dataset and grouped as the statistical set through which the parameters of the system were assigned.

The mandibles of all 146 images were manually segmented by three expert dentists working at Shahid Beheshti University of Medical Sciences, Tehran. In order to generate a reliable unified ground truth for each x-ray, a voting policy was used. According to this voting policy, a pixel belonged to the object (mandible) if at least two of the three manual segmentations defined that pixel as an object:

![Fig. 1](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4652330/bin/JMI-002-044003-g001.jpg)

The figure below depicts the outputs of the automatic and manual mandible segmentations in some panoramic X-rays.

![Fig. 3](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4652330/bin/JMI-002-044003-g007.jpg)

The results of the current study seem promising and can lead to further investigations in the field of automatic segmentation of structures in different head and neck radiography techniques. The output of this study can be used in various scenarios, such as improving registrations of panoramic X-rays through the information gained from a segmented mandible. It can affect dental biometrics, which has become a popular field of research. It is also a promising method for human identification.

Intraosseous lesions of the mandible can be detected by performing pattern recognition on the mandible body, which is extracted through the proposed method. Because panoramic radiography is by far the most utilized form of paraclinical record in today’s dentistry (and not all dentists are experienced enough to detect intraosseous lesions), designing a system for autonomous detection of these damaged tissues seems like a good practice that could also result in early detection of lesions. The proposed method can be further extended to detect anatomic landmarks. As such, detecting locations of dental work in panoramic X-rays can be of great use, mostly in cases of dental forensics and detection of periapical lesions.

<i>Please note that on images with index 22 and 110, part of the segmentation is lost and the data was carefully restored by DatasetNinja</i>
