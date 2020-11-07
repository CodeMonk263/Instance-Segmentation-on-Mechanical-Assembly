# Instance-Segmentation-on-Mechanical-Assembly
Using Detectron2 algorithm to segment various parts of mechanical assembly


The following github repos have been helpful and made this project successfull - 
1. Detectron2 (FAIR) - https://github.com/facebookresearch/detectron2
2. Cocosynth (Generating Custom COCO Dataset) - https://github.com/akTwelve/cocosynth

## Scope of Improvement - 
1. Better Occlusion Detection using Custom COCO Dataset with annotations which have occlusion masks also (ORCNN can be used - https://github.com/waiyulam/ORCNN)
2. Reducing False Detections of holes on certain parts.

Detailed Description of the Working of the Colab Files - Midsem Report File

Research Papers Referred have been attached.

## Input Directory Substructure - 
* backgrounds

* foregrounds

  * parts

    * piece1

    * piece2

    * rod

    * tyre

  * screws

    * bolts

    * nuts
    

## Author - 

Shaurya Vijayvargiya

BITS Pilani Hyderabad Campus
