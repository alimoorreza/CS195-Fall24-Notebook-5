# CS195-Fall24-Notebook-5
## Underwater Animal Segmentation:
<b>Due</b>: Wednesday, December 5th, 2024

For this assignment, you'll use the final part of Underwater Animal Detection Dataset (UWS_sem_seg_v1), which can be downloaded from [here](https://drive.google.com/uc?id=155Vg3iOTK3aed11LXC2lFQBxhdimfuZB). This is a multiclass semantic segmentation task where you predict pixel labels from predefined categories of underwater animals (starfish, shark, whale) and background elements (rock, water, etc.). You'll evaluate pre-trained models like FCN and DeepLab from PyTorch, then train and test using the state-of-the-art HRNet (High Resolution Network).
![Underwater Animal Categories](https://github.com/alimoorreza/CS195-Fall24-Notebook-3/blob/main/etc/uws_v1_samples.png)


## Notebook:
It's an assignment divided into three parts. You should use these three notebooks for the corresponding experiments:
   - [_Part 1: Notebook_5_starter for FCN inference_](https://github.com/alimoorreza/CS195-Fall24-Notebook-5/blob/main/cs195_part1_inference_using_pretrained_FCN_model.ipynb).
   - [_Part 2: Notebook_5_starter for HRNet trainining using UWSv1 dataset_](https://github.com/alimoorreza/CS195-Fall24-Notebook-5/blob/main/cs195_part2_training_HRNet_model.ipynb).
   - [_Part 3: Notebook_5_starter for HRNet inference using UWSv1 dataset_](https://github.com/alimoorreza/CS195-Fall24-Notebook-5/blob/main/cs195_part3_inference_using_trained_HRNet.ipynb).

## Expectations: ☑️
You need to create a Colab notebook starting from here - [_Part 1: Notebook_5_starter for FCN inference_](https://github.com/alimoorreza/CS195-Fall24-Notebook-5/blob/main/cs195_part1_inference_using_pretrained_FCN_model.ipynb). After completing the FCN inference experiment, proceed to training HRNet model using the following [_Part 2: Notebook_5_starter for HRNet trainining using UWSv1 dataset_](https://github.com/alimoorreza/CS195-Fall24-Notebook-5/blob/main/cs195_part2_training_HRNet_model.ipynb). Finally, after training an HRNet model using UWSv1 dataset, you need to evaluate the trained model using 3 sample images (randomly selected) using the third notebook [_Part 3: Notebook_5_starter for HRNet inference using UWSv1 dataset_](https://github.com/alimoorreza/CS195-Fall24-Notebook-5/blob/main/cs195_part3_inference_using_trained_HRNet.ipynb)
Add your code and results to document your experiment.



### Rubric:
> *This assignment is worth 14 points. It will be graded using the following rubric. I strongly suggest evaluating your project using this rubric before turning it in. It consists of two criteria: 1) *writing, and 2) *code. The details of the rubrics are as follows:

| Exercise #  | Points Awarded (out of 14)  | Notes |
| --------- | ------------------- | --------- |
| 1: FCN inference on random samples using the UWSv1 dataset       |    -/7.0    |            |
| 2: HRNet training using UWSv1 dataset (train split)              |    -/3.0    |            |
| 3: HRNet inference using UWSv1 dataset (validation split)        |    -/4.0    |            |
| <b>Total                                                         |    -/14.0   |     </b>   |

