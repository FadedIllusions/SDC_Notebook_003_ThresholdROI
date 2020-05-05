# SDC_Notebook_003_ThresholdROI

This notebook is the third notebook corresponding to the "Computer Vision Fundamentals" of Udacity's Self-Driving Car Nanodegree, in which we begin exploring the concepts of image processing and computer vision.

In this notebook, we combine what we learned in the previous [Color Selection Notebook](https://github.com/FadedIllusions/SDC_Notebook_001_ColorSelection) and [Region Of Interest Notebook](https://github.com/FadedIllusions/SDC_Notebook_002_ROI) to not only select a color beyond a certain pixel intensity threshold (in this case, white); but, also, limit such thresholding to a specific field of view.

Essentially, we (logic) AND the area within our Color Selection and ROI, negating everything else. Then we can overlay our threshold/ROI selection with the original image...

![Threshold ROI](/images/threshold_roi.png)
