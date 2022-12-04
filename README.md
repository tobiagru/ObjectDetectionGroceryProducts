<img src="https://github.com/tobiagru/HoloselectaDataset/blob/master/logo-hr.png?raw=true" alt="Auto-ID Labs" height="70"/>

# Object Detection Datasets in the Grocery Product Domain
This is a collection of datasets which are useful for object detection in the domain of grocery product detection. The credits for the respective datasets belong to the authors, which are credited with each dataset individually. These datasets were accumulated by the [Auto-ID Labs](https://www.autoidlabs.ch/) at the [ETH Zürich](www.ethz.ch) within an ongoing effort to accelerate computer vision research in the grocery domain. The datasets were accumulated by Klaus Fuchs & Tobias Grundmann.

## Datasets
| Name                           | # Classes    | # Instances   | # Images    | GTIN annotated   | 
| ------------------------------ | ------------ | ------------- | ----------- | ---------------- |
| Holoselecta                    | 109          | 10'035        | 295         | Yes              |
| Grozi-3.2K                     | 3'235        |               | 3'235 + 680 | No               |
| Grozi120                       | 120          |               | 720 + 4'973 | No               |
| The Freiburg Groceries Dataset | 25           | 5'000         | 5'000       | No               |
| SKU110K                        | 110'712      | ~1.74 * 10^6  | 11,762      | No               |
| Locount                        | 140          | ~1.9 * 10^6   | 50'394      | ?               |



... if you know further datasets let us know by issuing a request or sending us an email to team@autoidlabs.ch ...    

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

[**Download**](https://drive.google.com/file/d/1vvB1hvKhr4pE8zUpPImlogA6kof-kLVN/view)


### The Freiburg Groceries Dataset
Please cite the paper as follows:  
*Philipp Jund, Nichola Abdo, Andreas Eitel, Wolfram Burgard. "The Freiburg Groceries Dataset." arXiv, 2016*

The Freiburg Groceries Dataset consists of 5000 256x256 RGB images of 25 food classes. Examples for each class can be found below. The paper can be found here and the dataset here.

[**Download**](https://github.com/PhilJd/freiburg_groceries_dataset/blob/master/README.md)

### SKU110K
Please cite the paper as follows:  
*Eran Goldman, Roei Herzig, Aviv Eisenschtat, Jacob Goldberger, Tal Hassner. "Precise Detection in Densely Packed Scenes." Computer Vision and Pattern Recognition. 2019*  

A dataset of labeled bounding boxes on realistic images of products shelves in supermarkets.  

[**Github**](https://github.com/eg4000/SKU110K_CVPR19)

### The Locoust Dataset
Please cite the paper as follows:  
*Yuanqiang Cai and Longyin Wen and Libo Zhang and Dawei Du and Weiqiang Wang. "Rethinking Object Detection in Retail Stores" AAAI 2021*

They collect a large-scale object localization and counting dataset at 28 different stores and apartments, which consists of 50,394 images with the JPEG image resolution of 1920x1080 pixels. More than 1.9 million object instances in 140 categories

[**Link**](https://isrc.iscas.ac.cn/gitlab/research/locount-dataset) 
