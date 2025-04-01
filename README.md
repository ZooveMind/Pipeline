# Pipeline
software architecture

### Stage-1:  Data acqusition model

    * can use opencv based video capture library to capture video from camera/ cctv.
    * will make it configurable in order to capture with different aspects.
    * pushes frames to queue / buffer : so that one part can go for next stage.

### Stage-2 : v2e wrapper

    * have to make a library project out of it.
    * input will be video and output will be event data, i want to store them as .npy for faster calcualtion.
    * we can plan to give configurable params along with input like thresold, time, resolution etc.

### Stage-3: Event data pre-processing

    * datalaoder 
    * normalization of timestamps  
    * denoising  
    * removing isolated noise  
    * ROI extraction and background suppression if required.


### Stage-4: event data visualisation:

    * histogram represenation  
    * scatter plot representation  
    * 2D and 3D visualization  
    * time-surface encoding  
    * spiking represenation  
    * Temporal represenation  
    * spatial represenation  
    * fusing spatio-temporal represenation  
    * optical flow represenation 

### stage-5: some level of analytics report from the visualisation module.

    * some level of anlytics report from the visualisation module.
    * 


