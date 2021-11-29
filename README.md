# Naive Bayes Implementation from Scratch on Recognising Yoga Poses
Seth Ng & Wong Li Sean

## Summary
This project serves to better understand how a Naive Bayes model works by deconstructing the processes, analysing how they work, and piecing them together to form the whole model. This project uses the Yoga Pose Classification dataset from https://www.amarchenkova.com/2018/12/04/data-set-convolutional-neural-network-yoga-pose/ where each instance has 23 variables, of which each representing a different body part, where they collectively represents a yoga pose. The training and test sets can also be found in the 'data' folder.

Four main questions were answered in our report which relate to i) multiclass classification, ii) Gaussian distribution assumptions, iii) kernel density estimates (KDE), and iv) model selection techniques. For more information on those questions, please refer to 'Project Spec.pdf' and our answers for them in 'Report.pdf'.

All functions should be run right from the notebook file in order from top to bottom. The functions can be extended to other training and testing sets.

## Notes
- For Q2, we plotted graphs of the specific 5 attributes: wristR, kneeL, elbowL, head, kneeR to show some of the cases.
- For Q3 we chose 10 as our arbitrary kernel value.
- For Q4, we used random partitions to split the training dataset, so you may not get exactly the same results as us but perhaps similar.
