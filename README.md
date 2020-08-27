# SIDGAN:Low Light Video Enhancement using Synthetic Data Produced with an Intermediate Domain Mapping (Paper accepted to ECCV 2020)

Danai Triantafyllidou, [Sean Moran](http://www.seanjmoran.com), Steven McDonagh, Sarah Parisot, [Greg Slabaugh](http://gregslabaugh.net/)

Huawei Noah's Ark Lab

### [[Paper]](https://arxiv.org/abs/2007.09187) 
### [[Video]](http://www.seanjmoran.com/img/1809-10min.wmv) 
### [[Supplementary]](http://www.seanjmoran.com/pdfs/low_light_video_enhancement_using_synthetic_data_produced_with_an_intermediate_domain_mapping-Supplementary%20Material.zip) 

<p align="center">
<img src="./images/teaser.png" width="80%"/>
</p>
Repository for the paper SIDGAN: Low Light Video Enhancement using Synthetic Data Produced with an Intermediate Domain Mapping. Here you will find a link to the code and information on the datasets. Please raise a Github issue if you need assistance of have any questions on the research. 
<p></p>

### Code

**Code is currently undergoing legal screening **

### Bibtex

```
@misc{triantafyllidou2020low,
    title={Low Light Video Enhancement using Synthetic Data Produced with an Intermediate Domain Mapping},
    author={Danai Triantafyllidou and Sean Moran and Steven McDonagh and Sarah Parisot and Gregory Slabaugh},
    year={2020},
    eprint={2007.09187},
    archivePrefix={arXiv},
    primaryClass={eess.IV}
}
```

### Datasets

* __Adobe-DPE__ (5000 images, RGB, RGB pairs): this dataset can be downloaded [here](https://data.csail.mit.edu/graphics/fivek/). After downloading this dataset you will need to use Lightroom to pre-process the images according to the procedure outlined in the DeepPhotoEnhancer (DPE) [paper](https://github.com/nothinglo/Deep-Photo-Enhancer). Please see the issue [here](https://github.com/nothinglo/Deep-Photo-Enhancer/issues/38#issuecomment-449786636) for instructions. Artist C retouching is used as the groundtruth/target. Feel free to raise a Gitlab issue if you need assistance with this (or indeed the Adobe-UPE dataset below). You can also find the training, validation and testing dataset splits for Adobe-DPE in the following [file](https://www.cmlab.csie.ntu.edu.tw/project/Deep-Photo-Enhancer/%5BExperimental_Code_Data%5D_Deep-Photo-Enhancer.zip). 
