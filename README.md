# NeuroEmo: An fMRI Dataset for Emotion Recognition
https://openneuro.org/datasets/ds005700

#Description: The purpose of the study is to enable emotion recognition analysis using culturally relevant stimuli, such as Indian Bollywood movie clips, in fMRI data collected from Indian participants. This dataset explores the neural basis of emotions in a contextually meaningful way, focusing on functional and dynamic connectivity.

# Summary
This dataset contains fMRI data collected from 40 healthy participants who watched emotional Indian movie videos clips. Tasks included resting-state and emotion-elicitation tasks. Data was organized following the BIDS standard. Dataset size: 7.21 GB (BIDS-compliant format), 36 GB (raw DICOM files).
The data was collected at fMRI center of Central Institute of Psychiatry (CIP), Kanke, Ranchi.The research proposal and experimental protocol received ethical clearance from the Institute Ethics Committee, CIP (No. IEC/CIP/2022-23/1709).

# Data Collection details:
# Acquisition details:
Scanner: Philips Ingenia 3T MRI scanner with following parameter- -T1w data was collected for matrix size 192x192x256, voxel size 1x1x1 mm, slice thickness 1, space between slices 1, echo time 0.002943, repetition time 0.0065, flip angle 9^°. -Task-rest_bold was collected for matrix size 96x96x38, voxel size -2.29x2.29x4 mm, slice thickness 4, space between slices 4, echo time 0.035001, repetition time 2.02697, flip angle 90^°, slice 38. -Task-fe_bold was collected for matrix size 128x128x36, voxel size =-1.8x1.8x4 mm, slice thickness 4, space between slices 4, echo time 0.035, repetition time 3, flip angle 90^°, slice 36.

# Stimuli 
Videos used as stimuli were selected from [Mishra, S., Srinivasan, N., Asif, M., and Tiwary, U.S., 2023. Affective film dataset from India (AFDI): Creation and validation with an Indian sample. Journal of Cultural Cognitive Science, 7(3), pp. 255–267] based on their potential to evoke emotions. The videos were downloaded in high quality and cropped to 30-second clips to elicit specific emotions corresponding to five emotion classes: Calm, Afraid, Delighted, Depressed, and Excited.

# Task
Participants viewed movie clips designed to evoke different emotions task details: onset duration emotion

0 30 calm 30 30 white noise 60 30 afraid 90 30 white noise 120 30 delighted 150 30 white noise 180 30 depressed 210 30 white noise 240 30 excited 270 30 white noise 300 30 delighted 330 30 white noise 360 30 depressed 390 30 white noise 420 30 calm 450 30 white noise 480 30 excited 510 30 white noise 540 30 afraid 570 30 white noise

# File Structure
-/sub-01/
-/anat/
-sub-01_T1w.nii: Anatomical data of sub-01
-sub-01_T1w.json
-/func/
    -sub-01_task-fe_bold.nii: Functional data for the emotion task.
-sub-01_task-fe_bold.json
    -sub-01_task-rest_bold.nii: Resting-state functional data.
-sub-01_task-rest_bold.json

# Contact
For questions, email: [abgeenakhan786@gmail.com]


