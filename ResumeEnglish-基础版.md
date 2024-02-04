<center>

<h1>Hao Wang</h1>

<div>

<span><img src="assets/iconmonstr-linkedin-3.svg" width="18px">https://www.linkedin.com/in/hao-wang-4821ba100/</span>&ensp;  . &ensp; <span><img src="assets/envelope-solid.svg" width="18px">wanghao.ftd@foxmail.com</span>
</div>
</center>

## <img src="assets/graduation-cap-solid.svg" width="30px"> Education

- **Master of  Engineer (Professional Degree) : Computer Technology ** 
  - Shanghai Jiaotong University (46th in QS Ranking), in China, from September 2015 to April 2018
- **Bachelor of Engineer : Software Engineering ** 
  - Xi'an Jiao Tong University (291rd in QS Ranking), in China, from September 2011 to July 2015

## <img src="assets/briefcase-solid.svg" width="30px"> Work Experience
- **Tencent** Technology (Shenzhen) Co., Ltd.
  - **Worked as a software engineer** from April 2018 to November 2021
  - Designed and implemented a short video labeling system based on title and vision for Tencent-Search engine.
  - Built HTTP APIs involving my colleagues' AI models and served it to clients.
  - Designed and implemented certificate's Optical Character Recognition system.
- **Charworkshop** Technology (Shenzhen) Co., Ltd.
  - **Work as a software engineer** from November 2021 to now
  - Built RESTful APIs based on Java SpringBoot and Python Flask that served data to the JavaScript front-end Page.
  - Constructed a crawler system which is based on **Scrapy** to collect pet related data.
## <img src="assets/project-diagram-solid.svg" width="30px"> Project
- **Video Labeling System**
  - **Background**
    Designed and implemented the system of Labeling short videos for Tencent-Search engine and these labels be applied in several results pages.
  - **Extracted labels from title**
    Trained sequence labeling models based on **Prompt tuning + Bert** to generate videos' labels and achieved 83.24% AVG-F1 Score. Then deployed it as a Http Service. 
  - **Implemented the Program**
    Built the video data process system in **spark** platform and the videos' labels be finally written into the key-value databases for downstream applications. This system processed ten thousand levels of video data every hour. The video labels increased the click rate by 15.3% (from 21.84% to 25.19%) in the video results page. The video labels supoorted the phrase-filtering and video-collecting functions.
- **AI Services in Finance and Insurance**
  - **Background** 
    Built several identity documents OCR http api for Fusion Bank. And built HTTPs APIs that served AI capacity to the clients.
  - **OCR Implement**
    Built a pipeline to recognize different documents' texts. Trained models to tell types, find text regions and recognize words intelligently and integrated these models into the pipeline.
  - **AI HTTPs Services**
    Built HTTPs services of several AI models (trained in Keras, TensorFlow and PyTorch) in finance and insurance fields. Based on Python Flask to develop the HTTPs API and used Gunicorn to serve interfaces in multiprocessing way.
- **Pet Articles Online**
  - **Background**
    Built the back-end HTTPs interfaces which served data from database to front-end. 
  - **Pet Article RestFul API**
    Built the Pet article HTTPs services and the user payments HTTPs services based on SprintBoot. Used MySQL as the data stores. Used Redis as the key-value database. 
  - **Crawle System**
    Using Scrapy, I built out a crawling system for downloading pet related articles from several websites. And the system checks new articles from these websites every day.


##<img src="assets/tools-solid.svg" width="30px"> Skill
- Language： Java, C++, Python
- Framework：Spark, PyTorch, Scrapy, Stable-diffusion
## <img src="assets/tools-solid.svg" width="30px"> Paper
- **Hao Wang**, Hai Zhao. A Transition-based System for Universal Dependency Parsing. In Proceedings of the CoNLL 2017 Shared Task: Multilingual Parsing from Raw Text to Universal Dependencies Vancouver, Canada, August 3-4, 2017. **(CoNLL 2017)**