# SAR Ship Detection - YOLO and RT-DETR Comparison Tutorial
##### __by Carter Thompson__
##### updated: 14 May 2026

### The goal of this tutorial is to show how to train, utilize, and compare the efficacy of two machine learning models for SAR Ship Detection.

YOLO models have become mainstays in the digital image processing boom through the mid-2010s to the present; they are quick and easy to implement, but have sometimes lacked in accuracy (though newer models continue to improve on this). DETR transformer models are very robust, but have lacked the speeds YOLO models could achieve - until now, with the development of RT-DETR models that test at real-time speeds.

This tutorial will show you how to prepare, train, optimize, and test both of these models separately, and provide you tools to compare their performance metrics against one another if that interests you.

## References

[1] T. Zhang, X. Zhang, J. Li, X. Xu, B. Wang, X. Zhan, Y. Xu, X. Ke, T. Zeng, H. Su et al., “SAR ship detection dataset (SSDD): Official release and comprehensive data analysis,” Remote Sensing, vol. 13, no. 18, p. 3690, 2021, doi: 10.3390/rs13183690.

[2] G. Jocher and J. Qiu, Ultralytics YOLO26. 2026. [Online]. Available: https://github.com/ultralytics/ultralytics

[3] R. Sapkota and M. Karkee, “Ultralytics YOLO Evolution: An Overview of YOLO26, YOLO11, YOLOv8 and YOLOv5 Object Detectors for Computer Vision and Pattern Recognition,” arXiv:2510.09653, 2025. doi: 10.48550/arXiv.2510.09653.

[4] Ultralytics, “Baidu’s RT-DETR: A Vision Transformer-Based Real-Time Object Detector,” Ultralytics Docs. [Online]. Available: . [Accessed: May 13, 2026].

[5] W. Lv et al., “DETRs Beat YOLOs on Real-time Object Detection,” arXiv:2304.08069v3, 2024. doi: 10.48550/arXiv.2304.08069

## Tutorial
The tutorial can be found in the Colab Notebook [ML-SARShipDetection-Tutorial.ipynb](https://colab.research.google.com/github/carthomp99/ML-SARShipDetection-Tutorial/blob/main/ML-SARShipDetection-Tutorial.ipynb#scrollTo=QkkI4Ga1j6uf). All sections can be run in Google Colab using free GPU runtimes.
