# Facial Keypoints Detection

Each predicted keypoint is specified by an (x,y) real-valued pair in the space of pixel indices.
15 facial keypoints are:
- left_eye_center
- right_eye_center
- left_eye_inner_corner
- left_eye_outer_corner
- right_eye_inner_corner
- right_eye_outer_corner
- left_eyebrow_inner_end
- left_eyebrow_outer_end
- right_eyebrow_inner_end
- right_eyebrow_outer_end
- nose_tip
- mouth_left_corner
- mouth_right_corner
- mouth_center_top_lip
- mouth_center_bottom_lip

> Left and right here refers to the point of view of the subject.

Dataset contains separate x and y rows for each keypoints(15x2 rows) and 96x96 grayscale face image data as row-ordered list of pixels(1 row).

#### Plot of a sample
|![sample_data](https://github.com/op1009/facial_keypoints_detection/assets/149959895/a38e4f47-9608-4f25-8c9d-3a0901ffc83a)|
|:-:|
|plot of a sample data|

#### A quick summary of project:
- Model Architecture : CNN
- Dataset : Facial Keypoints Detection (Kaggle Competition Dataset) 
- Platform : GPU
