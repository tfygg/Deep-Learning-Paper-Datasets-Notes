 # Instruction
 
 ### CASIA-Webface
 
 -  CASIA-WebFace数据集包含了10575 个人的494414 张图像。
 
 -  CASIA-Webface 跟LFW有3个身份的重合。
 
 
 ### MS1M
- ms1m-v1 = ms1m-ibug, include 85164 IDS/3804846 images

- ms1m-v2 = ms1m-arc = emore include 85742 IDS/5822653 images
 
 
 ### VGG-Face2
- The dataset contains 3.31 million images of 9131 subjects (identities), with an average of 362.6 images for each subject.
 
 
 ### DeepGlint-Face/Trillion Pairs ([face_glint](!http://trillionpairs.deepglint.com/overview)) 
 
 #### Training set
DeepGlint-Face includes MS1M-DeepGlint and Asian-DeepGlint
 
 - MS-Celeb-1M-v1c with 86,876 ids/3,923,399 aligned images cleaned from MS-Celeb-1M dataset. 
   This dataset has been excluded from both LFW and Asian-Celeb.
 
 - Asian-Celeb 93,979 ids/2,830,146 aligned images. 
   This dataset has been excluded from both LFW and MS-Celeb-1M-v1c.
   
#### Testing set
Trillion Pairs is consisted of the following two parts.

- ELFW: Face images of celebrities in LFW name list. There are 274k images from 5.7k ids.

- DELFW: Distractors for ELFW. There are in total 1.58 million face images from Flickr.

### Megaface
#### Challenge 1
- Train on any dataset, test your method with 1 million distractors

#### Challenge 2
- Training on 672K identities (4.7 Million photos), test at Million scale

- Training Set:

    4.7 Million Photos

    672,057 Unique Identities
    
    7 Mean photos / person (3 min, 2469 max

- Test Sets

    FaceScrub Celebrities

    FGNet Age-invariant non-celebrities
    
### [FaceScrub](!http://vintage.winklerbros.net/facescrub.html )
- It comprises a total of 106,863 face images of male and female 530 celebrities, with about 200 images per person.

