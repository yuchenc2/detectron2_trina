# Detectron2 with RGBD 3D Segmentation for TRINA

## Description

This implementation uses the Detectron2 2D image recognition library to perform 3D segmentation on RGBD photos taken from the the TRINA robot. The goal is to create a segmented object from the cluttered scene for the next element in the robot manipulationg and grasping pipeline: grasping point generation on a single object.

Example: An RGBD Image of a banana

* Input RGBD Image:

  ![item1-color-25](https://user-images.githubusercontent.com/46701122/119622834-1e42b180-be3a-11eb-8b1e-68ac62e9e05e.png)

* Output from the colab program

  https://user-images.githubusercontent.com/46701122/119623001-5518c780-be3a-11eb-98e5-856dcdcb8856.mp4

## Getting Started
Go to the [colab file](https://colab.research.google.com/drive/1AEYJhjYqWEeBEIcugshmYnLH9ME4Kgy2) and run the code. You can select any RGBD photo by linking your Google drive containing the photo. To train the model, create your dataset in the COCO dataset format or follow the tutorial [here](https://detectron2.readthedocs.io/en/latest/tutorials/datasets.html)

## Acknowledgments

Inspiration, code snippets, etc.
* [Detectron2 Getting Started](https://detectron2.readthedocs.io/en/latest/tutorials/getting_started.html)
* [Detectron2 Tutorial](https://www.youtube.com/watch?v=eUSgtfK4ivk)
* [Detectron2 Training](https://detectron2.readthedocs.io/en/latest/tutorials/datasets.html)
