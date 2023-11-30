# House-Boundary-Detection
## Deep Learning project to detect house boundaries in Paksitan, using Solaris and Spacenet7 models

### For images captured at higher altitudes, displaying clustering akin to the Spacenet7 dataset, the image reconstruction is remarkably accurate, as evidenced by the samples below.


<p align="center">
  <img src="data/img_resized_7.png" width="350">
</p>



#### output

<p align="center">
  <img src="data/img_resized_7_infer.jpg" width="350">
</p>

#### Sample 2
<p align="center">
  <img src="data/img_resized_18.png" width="350" >
</p>

#### output

<p align="center">
  <img src="data/img_resized_18_infer.jpg" width="350">
</p>



### However, when dealing with images captured at lower altitudes featuring lower resolution and expansive boundaries, the model struggles to generate accurate boundary masks. Given that a significant portion of data in Pakistan aligns with these characteristics, the model's accuracy is compromised.

<p align="center">
  <img src="data/block_30.png" width="350">
</p>

#### output

<p align="center">
  <img src="data/block_30_infer.jpg" width="350">
</p>

#### Sample 2

<p align="center">
  <img src="data/block_32.png" width="350" >
</p>

#### output

<p align="center">
  <img src="data/block_32_infer.jpg" width="350">
</p>