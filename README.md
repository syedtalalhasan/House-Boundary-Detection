# House-Boundary-Detection
Deep Learning project to detect house boundaries in Paksitan, using Solaris and Spacenet7 models

### For Images that are taken from higher altitutde and resemble clustering simmilar to the Spacenet7 dataset, image reconstruction is highly accurate, as is evident from samples below
<p align="center">
  <img src="data/img_resized_17.png" width="350">
</p>


<p align="center">
  <img src="data/img_resized_17_infer.png" width="350">
</p>

### Sample 2
<p align="center">
  <img src="data/img_resized_18.png" width="350" >
</p>


<p align="center">
  <img src="data/img_resized_18_infer.png" >
</p>



### However for images that are taken from lower altitutdes and have lower resolution with large boundaries, the model fails to recognize house boundaries. Most data in Pakistan is simmilar to these examples, where results are not accurate.

<p align="center">
  <img src="data/block_30.png" width="350">
</p>

<p align="center">
  <img src="data/block_30_infer.png" width="350">
</p>

### Sample 2

<p align="center">
  <img src="data/block_32.png" width="350" >
</p>

<p align="center">
  <img src="data/block_32_infer.png" width="350">
</p>
