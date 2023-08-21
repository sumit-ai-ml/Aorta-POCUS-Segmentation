

Welcome to the official repository for the research paper titled "Deep Learning Models for Abdominal Aorta Segmentation in Point-of-Care Ultrasound Images." This repository houses the code and resources associated with the investigation and comparison of six state-of-the-art deep learning models designed for segmenting the short axis of the abdominal aorta in point-of-care ultrasound (POCUS) images.

**Here an Web-app:**

<iframe
	src="https://sumit-ai-ml-aorta-segmentation.hf.space"
	frameborder="0"
	width="850"
	height="450"
></iframe>

- **Introduction:**
In the realm of medical imaging, accurate and efficient segmentation of anatomical structures is crucial for diagnostic precision and patient care. This paper presents a comprehensive study that delves into the performance of six cutting-edge deep learning models when applied to the task of segmenting the abdominal aorta in POCUS images. The project was undertaken with the aim of improving health screening processes, particularly in remote areas, where access to specialized medical services may be limited.

- **Dataset:**
A diverse collection of 724 ultrasound images obtained from 175 adult patients was meticulously curated, encompassing a variety of perspectives. This dataset was thoughtfully partitioned into three subsets for training, validation, and testing. Specifically, 510 images from 146 patients were allocated for training, 74 images from 17 patients were used for validation, and 140 images from 18 patients were earmarked for testing.

- **Models Explored:**
The study delved into six distinct deep learning architectures, each tailored for the task of abdominal aorta segmentation. These models include UNet, Attention UNet, Res-UNet, Res-Attention UNet, YOLOv8, and a hybrid model integrating YOLOv8 with the Segment Anything model (SAM).

- **Methodology:**
Each model underwent rigorous training until it reached optimal performance levels. Following this training phase, a separate dataset containing 375 patients was employed to evaluate the efficacy of the models in real-world scenarios.

- **Key Findings:**
The results showcased the superior and efficient performance of YOLOv8 in segmenting the abdominal aorta in ultrasound images. Notably, YOLOv8 achieved a mean dice score of 0.759, outperforming the other models. When combined with the Segment Anything model (SAM), YOLOv8 further enhanced its segmentation capabilities, yielding a mean dice score of 0.763.

- **Implications:**
These findings bear significant implications for healthcare diagnostics, especially in remote and underserved regions. The ability of YOLOv8 and its combination with SAM to accurately analyze the anatomical location and morphology of the abdominal aorta showcases their potential to revolutionize health screening practices. Such advancements can potentially lead to improved patient care, enhanced diagnostics, and more effective medical interventions.

In this repository, you will find the code, documentation, and resources necessary to replicate and extend this research. We invite researchers, developers, and medical professionals to explore, contribute, and utilize these findings to drive innovation in the field of medical image analysis.


