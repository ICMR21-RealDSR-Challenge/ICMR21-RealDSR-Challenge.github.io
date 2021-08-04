## Challenge Title

Real DepthSR2021 Challenge: Real World Depth Map Super-Resolution on the RGB-D-D Dataset

## Challenge Description:

As a supplement of the RGB modality, the depth map can provide useful depth information, which has been applied in bokeh rendering, AR modeling, face recognition, gesture recognition, etc. However, the resolution of depth maps cannot match the resolution of RGB images, thereby limiting the practical applications to some extent. Although numerous deep learning methods have been proposed for depth map SR and presented impressive performance, there are still some unsatisfactory points in detail preserving, computation complexity, and real-world application. 

In order to be applied on the platforms of the mobile devices and embedded systems, the depth map SR algorithms should take into account both the efficiency and accuracy. Furthermore, down-sampling as a straight-forward strategy has been widely used in the existing depth map SR algorithms to construct paired HR and LR depth maps training samples, which fails to simulate the real correspondences between HR and LR depth maps. 
In this competition, we encourage the participants to design depth map SR models that can suit the real-world depth map SR task. Giving depth maps captured by low-power depth sensor, they are supposed to be up-sampled not only fit for embedded systems but also achieve high accuracy at the same time.

## Dataset Download:
We randomly split 1586 portraits, 380 plants, 249 models from RGB-D-D dataset as the training set for this challenge. Meanwhile, we randomly select 50 samples from the test set in RGB-D-D dataset to evaluate your models by two phases.
The dataset can only be used for academic purposes. By using this dataset and related codes, you should agree to cite our dataset and baseline paper. You can apply the training set and get more detailed content according to the home page of our group: [http://mepro.bjtu.edu.cn/resource.html](http://mepro.bjtu.edu.cn/resource.html)

## Baseline Method (FDSR):
Our previous work will be used as the baseline method for this challenge, which is accepted by CVPR 2021 with high performance. This paper is also used to provide the dataset in this challenge.

The source code for the baseline method (FDSR) can be found: [https://github.com/lingzhi96/RGB-D-D-Dataset](https://github.com/lingzhi96/RGB-D-D-Dataset). Please cite our baseline paper if it is helpful for your research:

```markdown
@inproceedings{he2021towards,
  title={Towards Fast and Accurate Real-World Depth Super-Resolution: Benchmark Dataset and Baseline},
  author={He, Lingzhi and Zhu, Hongguang and Li, Feng and Bai, Huihui and Cong, Runmin and Zhang, Chunjie and Lin, Chunyu and Liu, Meiqin and Zhao, Yao},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={9229--9238},
  year={2021}
}
```
## Important Dates
Registration Start Date: 		**August 10, 2021**
Training Dataset Available Date: 	**August 10, 2021**
Test Dataset Available Data:		**October 10, 2021**
First-phase Submission Start Date:	**October 10, 2021**
First-phase Submission Deadline: 	**October 17, 2021**
Second-phase Submission Start Date: **October 20, 2021**
Second-phase Submission Deadline: 	**October 27, 2021**
Winner Announcement Date Around: 	**October 30, 2021**

## Challenge Procedures
The Training set (a subset of RGB-D-D dataset) for this challenge will be available to the participants once the challenge starts. The participates are required to use the provided training set with annotations to develop a depth map super-resolution method using the low-resolution depth maps as the input or use RGB image to guide it. We will release our testing samples according to schedule. 
There will be two phases for this challenge: 
- First phase: randomly select 25 samples from the 50 testing set for evaluation. 
- Second phase: the remaining 25 of the testing set. The final ranking is based on the smaller RMSE of the two phases. If the RMSE results are the same, we choose the one with a smaller model size. 

Some detailed rules are listed as follows:
The participates can form their own teams from different organizations and the number of participants is not limited. But only one team is allowed from an individual organization.
The participates are NOT allowed to use external data for either training or validation.
The teams need to provide their opensource code through GitHub after the challenge results announcement. 
The participates are not allowed to use extra information from human labeling on the training dataset or testing dataset for the challenge’s target labels.
During each of the two phases in the competition, each team can only submit their results for evaluation less than 5 attempts in total. 
The provided dataset can only be used for academic purposes. By using this dataset and related software, you agree to cite our dataset and baseline paper. 
The first three participants in each phase will be issued certificates.

## Host Organization:
MePro, Institute of Information Science, Beijing Jiaotong University

## Organizers:
Yao Zhao (yzhao@bjtu.edu.cn): Professor, Beijing Jiaotong University
Runmin Cong (rmcong@bjtu.edu.cn): Associate Professor, Beijing Jiaotong University
Huihui Bai (hhbai@bjtu.edu.cn): Professor, Beijing Jiaotong University
Chunjie Zhang (cjzhang@bjtu.edu.cn): Professor, Beijing Jiaotong University
Chunyu Lin (cylin@bjtu.edu.cn): Professor, Beijing Jiaotong University
Meiqin Liu (mqliu@bjtu.edu.cn): Associate Professor, Beijing Jiaotong University
Sam Kwong (cssamk@cityu.edu.hk): Chair Professor, City University of Hong Kong
```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ICMR21-RealDSR-Challenge/ICMR21-RealDSR-Challenge.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
