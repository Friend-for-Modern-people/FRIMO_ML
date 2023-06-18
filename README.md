# FRIMO_ML

FRIMO_ML is a repository for the parts of the FRIMO project that use machine learning.

<br> <br>

## <b> Repository Structure </b>

<br>

* <b> Model / Emotion Recognition </b>
    > Emotion Recognition models is located here.
    * File
        * <b> train.py </b> : Python file for training
        * <b>  predict.py </b> : Python file for recognition
        * <b> 감성대화말뭉치(최종데이터)_Training.json </b> : JSON files used for training
        * <b> 감성대화말뭉치(최종데이터)_Validation.json </b> : JSON files used for validation
        * <b> final_train.csv </b> : CSV file we plan to use for data augmentation
        * <b> final_test.csv </b> : CSV file we plan to use for data augmentation
    * Implement the ability to understand the emotion behind a conversation.
    * Implemented Model : [KoBERT]()
* <b> README </b>
    > A markdown file containing a description of FRIMO_ML.
  
<br> <br>

## <b> Model Implementation </b>

<br>

* Model Structure

![image](https://github.com/Friend-for-Modern-people/FRIMO_ML/assets/31691750/1142cc55-8912-456e-a8c6-aa46a7cbd461)

<br>

* How to use
    * Training :
    > python train.py --train_data [file_path] --test_data [file_path] --num_epoch [number]
  
    * Predict :
    > python predict.py --pt_path [file_path]

<br>

* Emotion Recognition
    * [X] <b> Implement Prototype </b>
    * [X] <b> Handle Requirements </b>
    * [X] <b> Apply the Corpus[^1] </b>
    * [X] <b> Optimize the model </b>
    * [X] <b> Train repeatedly for enough reps </b>

<br> <br>

[^1]: https://aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=realm&dataSetSn=86

<br> <br>

## <b> Contributors </b>

<br>

| Name | Student Number | University | Contributed Parts | Github Link |
| :---: | :---: | :---: | :---: | :---: |
|Kim Donghyeon | 201935217 | Gachon Univ. | Emotion Recognition | [Github](https://github.com/eastlighting1) |

