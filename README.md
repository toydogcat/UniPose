# UniPose

  <a href="https://openaccess.thecvf.com/content_CVPR_2020/html/Artacho_UniPose_Unified_Human_Pose_Estimation_in_Single_Images_and_Videos_CVPR_2020_paper.html">**UniPose: Unified Human Pose Estimation in Single Images and Videos**</a>.
</p><br />

<p align="center">
  <img src="https://drive.google.com/uc?id=1_R6slinx-q7YyHwL4M9FScpZOXb5nLXX" title="WASPnet architecture for Semantic Segmentation">
  Figure 1: WASPnet architecture for Semantic Segmentation.
</p><br />

<p align="justify">
We propose UniPose, a unified framework for human pose estimation, based on our "Waterfall" Atrous Spatial Pooling architecture, that achieves state-of-art-results on several pose estimation metrics. UniPose incorporates contextual segmentation and joint localization to estimate the human pose in a single stage, with high accuracy, without relying on statistical postprocessing methods. The Waterfall module in UniPose leverages the efficiency of progressive filtering in the cascade architecture, while maintaining multi-scale fields-of-view comparable to spatial pyramid configurations. Additionally, our method is extended to UniPose-LSTM for multi-frame processing and achieves state-of-the-art results for temporal pose estimation in Video. Our results on multiple datasets demonstrate that UniPose, with a ResNet backbone and Waterfall module, is a robust and efficient architecture for pose estimation obtaining state-of-the-art results in single person pose detection for both single images and videos.
  
We propose the “Waterfall Atrous Spatial Pyramid” module, shown in Figure 2. WASP is a novel architecture with Atrous Convolutions that is able to leverage both the larger Field-of-View of the Atrous Spatial Pyramid Pooling configuration and the reduced size of the cascade approach.<br />

<p align="center">
  <img src="https://www.mdpi.com/sensors/sensors-19-05361/article_deploy/html/images/sensors-19-05361-g006.png" width=500 title="WASP module"><br />
  Figure 2: WASP Module.
</p><br />

Examples of the WASPnet architecture for segmentation are shown in Figures 3 and 4 for the PASCAL VOC and Cityscapes datasets, respectively.<br />

<p align="center">
  <img src="https://www.mdpi.com/sensors/sensors-19-05361/article_deploy/html/images/sensors-19-05361-g009.png" width=500 title="WASP module"><br />
  Figure 3: Segmentation samples for the Pascal VOC dataset.
  <br /><br />
  <img src="https://www.mdpi.com/sensors/sensors-19-05361/article_deploy/html/images/sensors-19-05361-g010.png" width=500 title="WASP module"><br />
  Figure 4: Segmentation samples for the CItyscapes dataset.
</p><br /><br />
  
Link to the published article at CVPR 2020: https://openaccess.thecvf.com/content_CVPR_2020/html/Artacho_UniPose_Unified_Human_Pose_Estimation_in_Single_Images_and_Videos_CVPR_2020_paper.html
</p><br />

**Datasets:**
<p align="justify">
Datasets used in this paper and required for training, validation, and testing can be downloaded directly from the dataset websites below:<br />
  LSP Dataset: https://sam.johnson.io/research/lsp.html<br />
  MPII Dataset: http://human-pose.mpi-inf.mpg.de/<br />
  PennAction Dataset: http://dreamdragon.github.io/PennAction/<br />
  BBC Pose Dataset: https://www.robots.ox.ac.uk/~vgg/data/pose/<br />
</p><br />

**Pre-trained Models:**
<p align="justify">
The pre-trained weights can be downloaded at
  <a href="">here</a>.
</p><br />


**Contact:**

<p align="justify">
Bruno Artacho:<br />
  E-mail: bmartacho@mail.rit.edu<br />
  Website: https://people.rit.edu/bm3768<br />
  
Andreas Savakis:<br />
  E-mail: andreas.savakis@rit.edu<br />
  Website: https://www.rit.edu/directory/axseec-andreas-savakis<br /><br />
</p>

**Citation:**

<p align="justify">
Artacho, B.; Savakis, A. UniPose: Unified Human Pose Estimation in Single Images and Videos. in Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2020. <br />

Latex:<br />
@InProceedings{Artacho_2020_CVPR,<br />
  title = {UniPose: Unified Human Pose Estimation in Single Images and Videos},<br />
  author = {Artacho, Bruno and Savakis, Andreas},<br />
  booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},<br />
  month = {June},<br />
  year = {2020},<br />
}<br />
</p>
