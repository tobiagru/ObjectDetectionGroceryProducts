<img src="https://github.com/tobiagru/HoloselectaDataset/blob/master/logo-hr.png?raw=true" alt="Auto-ID Labs" height="70"/>

# Object Detection Datasets in the Grocery Product Domain
This is a collection of datasets which are useful for object detection in the domain of grocery product detection. The credits for the respective datasets belong to the authors, which are credited with each dataset individually. These datasets were accumulated by the [Auto-ID Labs](https://www.autoidlabs.ch/) at the [ETH Zürich](www.ethz.ch) within an ongoing effort to accelerate computer vision research in the grocery domain. The datasets were accumulated by Klaus Fuchs & Tobias Grundmann.

## Datasets
| Name   | # Classes    | # Instances   | # Images   | 
| ------ | ------------ | ------------- | ---------- |
| Holoselecta | 109     | 10035         | 295        | 
| Grozi-3.2K |  3235    |               | 3235 + 680 |
| Grozi120 | 120        |               | 720 + 4973 |
| SKU110K | 110,712     | ~1.74 * 10^6  | 11,762     |


... if you know further datasets let us know by issuing a request ...    

### Holoselecta 
Please cite the paper as follows:  
*Klaus Fuchs, Tobias Grundmann, Elgar Fleisch. "Towards Identification of Packaged Products via Computer Vision." Proceedings of the IoT 2019. 2019*  

License: [Creative Commons CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

A dataset of labeled bounding boxes on realistic images of products in vending machines of the Zurich area.  

[**Download**](https://drive.google.com/open?id=1OofnsREqF1QNfUqZPZgcXu2VkWr2JUMA) (will forward to Google Drive)

### GroZi120
Please cite the paper as follows:  
*Michele Merler, Carolina Galleguillos, and Serge Belongie. "Recognizing groceries in situ using in vitro training data". Computer Vision and Pattern Recognition, 2007.*  

A dataset of labeled products in Swiss supermarket shelves. This dataset is a task-adaption one-shot learning dataset. For every product there is one labeled studio quality image of the product (in vitro) in the training dataset and the validation dataset consists of labeled frames in 29 videos with labeled bounding boxes in shelves in a shop realistic environment (in situ). low-quality images.

[**Website**](http://grozi.calit2.net/)

### Grozi-3.2K
Please cite the paper as follows:  
*Marian George and Christian Floerkemeier. "Recognizing Products: A Per-exemplar Multi-label Image Classification Approach." European Conference on Computer Vision. Springer, Cham, 2014*

Version of GroZi120 with more products and higher quality images. A dataset of labeled products in Swiss supermarket shelves. This dataset is a task-adaption one-shot learning dataset. For every product there is one labeled studio quality image of the product (in vitro) in the training dataset and the validation dataset consists of images taken from a camcorder video with labeled bounding boxes on in shelves in a shop realistic environment (in situ).

[**Download**](https://sites.google.com/view/mariangeorge/datasets?authuser=0) (will forward to Google Pages Website)

### SKU110K
Please cite the paper as follows:  
*Eran Goldman, Roei Herzig, Aviv Eisenschtat, Jacob Goldberger, Tal Hassner. "Precise Detection in Densely Packed Scenes." Computer Vision and Pattern Recognition. 2019*  

A dataset of labeled bounding boxes on realistic images of products shelves in supermarkets.  

[**Github**](https://github.com/eg4000/SKU110K_CVPR19)
