
### Articles

##### Google Blog
[On-device, Real-time Body Pose Tracking with MediaPipe BlazePose](https://ai.googleblog.com/2020/08/on-device-real-time-body-pose-tracking.html)

##### Other Blogs
[Javascript Lib ML5.js: Machine learning for everyone: How to implement pose estimation in a browser using your webcam](https://thenextweb.com/syndication/2020/02/01/machine-learning-for-everyone-how-to-implement-pose-estimation-in-a-browser-using-your-webcam/)

### Libraries

##### Google
- [MediaPipe: BlazePose](https://google.github.io/mediapipe/solutions/pose)  
    <i>The solution utilizes a two-step detector-tracker ML pipeline, proven to be effective in our MediaPipe Hands and MediaPipe Face Mesh solutions. Using a detector, the pipeline first locates the pose region-of-interest (ROI) within the frame. The tracker subsequently predicts the pose landmarks within the ROI using the ROI-cropped frame as input. Note that for video use cases the detector is invoked only as needed, i.e., for the very first frame and when the tracker could no longer identify body pose presence in the previous frame. For other frames the pipeline simply derives the ROI from the previous frame’s pose landmarks.

    The pipeline is implemented as a MediaPipe graph that uses a pose landmark subgraph from the pose landmark module and renders using a dedicated upper-body pose renderer subgraph. The pose landmark subgraph internally uses a pose detection subgraph from the pose detection module.
    
    Note: To visualize a graph, copy the graph and paste it into MediaPipe Visualizer. For more information on how to visualize its associated subgraphs, please see visualizer documentation.
    </i>
  
##### Gits
- [Human Pose Estimation using ShelfNet with PyTorch](https://github.com/fmahoudeau/ShelfNet-Human-Pose-Estimation)
- [PyTorch-Pose](https://github.com/bearpaw/pytorch-pose)
- [Microsoft: Simple Baselines for Human Pose Estimation and Tracking](https://github.com/microsoft/human-pose-estimation.pytorch)
- [Pytorch-Human-Pose-Estimation](https://github.com/Naman-ntc/Pytorch-Human-Pose-Estimation)
- [PyTorch Realtime Multi-Person Pose Estimation](https://github.com/DavexPro/pytorch-pose-estimation)
- [Realtime Multi-Person Pose Estimation (Original)](https://github.com/ZheC/Realtime_Multi-Person_Pose_Estimation)
- [轻轻松松使用StyleGAN2](https://blog.csdn.net/weixin_41943311/article/details/103818239?utm_medium=distribute.pc_relevant.none-task-blog-baidulandingword-7&spm=1001.2101.3001.4242)
- []


##### Facebook

###### Pytorch
https://github.com/albumentations-team/albumentations
https://github.com/facebookresearch/detectron2
https://github.com/pytorch/ignite