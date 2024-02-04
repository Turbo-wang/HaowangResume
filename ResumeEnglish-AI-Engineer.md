<center>

<h1>Hao Wang</h1>

<div>

<span><img src="assets/iconmonstr-linkedin-3.svg" width="18px">[**LinkedIn**](https://www.linkedin.com/in/hao-wang-4821ba100/)</span>&ensp;  . &ensp; <span><img src="assets/envelope-solid.svg" width="18px">wanghao.ftd@foxmail.com</span>
</div>
</center>

## <img src="assets/tools-solid.svg" width="30px"> Skill
- Language：Python, C++,  Java
- Framework：TensorFlow, PyTorch, Bert, Spark
- Additional: Spring Boot, Flask

## <img src="assets/briefcase-solid.svg" width="30px"> Work Experience
- Tencent Technology (Shenzhen) Co., Ltd.
  - **Worked as a Developer** from April 2018 to November 2021
  - Designed and implemented a short video labeling system based on **BERT** and **Vision Transformer**

    for Tencent-Search engine.
  - Designed and implemented certificate's Optical Character Recognition system.
- Charworkshop Technology (Shenzhen) Co., Ltd.
  - **Work as a Developer** from November 2021 to now
  - Use **Stable-Diffusion** Models to generate pet images.
  - Built English-to-Chinese translator based on **BERT** for translating pet's articles.
  - Constructed a crawler system which is based on Scrapy to collect pet releted data.
## <img src="assets/project-diagram-solid.svg" width="30px"> Project
- **Video Labeling System**
  - **Background**
    Designed and implemented the system of Labeling short videos for Tencent-Search engine and these labels be applied in several results pages.

  - **Extracted labels from title**
    Trained sequence labeling models based on **Prompt tuning + Bert** to generate videos' labels and achieved a 83.24% AVG-F1 Score. Then deployed it as a Http Service. 

  - **Classified videos by frames**

    Trained multiple classification model to label video's type. First step is to extract and collect video's frames. Then trained a **large vision transformer** to extract vision feature learnt from millions videos data. Finally using a **MLP** layor to tell different type.

  - **Implemented the Program**
    Built the video data process system in **spark** platform and the videos' labels be finally written into the key-value databases for downstream applications. This system processed ten thousand levels of video data every hour. The video labels increased the click rate by 15.3% (from 21.84% to 25.19%) in the video results page. The video labels supoorted the phrase-filtering and video-collecting functions.
- **OCR Services**
  - **Background** 
    Built several identity documents OCR http api for Fusion Bank. And built HTTPs APIs that served AI capacity to the clients.

  - **OCR Implement**
    Built a pipeline to recognize different documents' texts. Trained models to tell types, find text regions (using **SSD**) and recognize words intelligently (based on **RCNN+CTC loss**) and integrated these models into the pipeline. 

- **Pet Community Website**
    - **Background**
      Dsigned and implemented a production system to generate images and articles in the pet website.

    - **Pet Article Generator**
      ​

    - Pet Image Generator

      ​

    - **Crawle System**
      Using Scrapy, I built out a crawle system for downloading pet related articles from several websites. And the system checks new articles from these websites everyday.

## <img src="assets/graduation-cap-solid.svg" width="30px"> Education
- **Master of  Engineer (Professional Degree) : Computer Technology ** 
  - Shanghai Jiaotong University, in China, from September 2015 to April 2018
- **Bachelor of Engineer : Software Engineering ** 
  - Xi'an Jiao Tong University, in China, from September 2011 to July 2015

## <img src="assets/tools-solid.svg" width="30px"> Paper
- **Hao Wang**, Hai Zhao. A Transition-based System for Universal Dependency Parsing. In Proceedings of the CoNLL 2017 Shared Task: Multilingual Parsing from Raw Text to Universal Dependencies Vancouver, Canada, August 3-4, 2017. **(CoNLL 2017)**
