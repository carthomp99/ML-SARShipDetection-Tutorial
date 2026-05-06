# ML SAR Ship Detection Tutorial
The goal of this tutorial is to show how to train, utilize, and compare the efficacy of two machine learning models for SAR Ship Detection. YOLO models have become mainstays in the digital image processing boom through the mid-2010s to the present; they are quick and easy to implement, but have sometimes lacked in accuracy (though newer models continue to improve on this). DETR transformer models are very robust and precise, but have lacked the speeds YOLO models could achieve - until now, with the development of RT-DETR models that operate in real time.

This tutorial will show you how to prepare, train, optimize, and test both of these models separately, and provide you tools to compare their performance metrics against one another if that interests you.

## References

[1] T. Zhang, X. Zhang, J. Li, X. Xu, B. Wang, X. Zhan, Y. Xu, X. Ke, T. Zeng, H. Su et al., “SAR ship detection dataset (SSDD): Official release and comprehensive data analysis,” Remote Sensing, vol. 13, no. 18, p. 3690, 2021, doi: 10.3390/rs13183690.

[2] G. Jocher and J. Qiu, Ultralytics YOLO26. 2026. [Online]. Available: https://github.com/ultralytics/ultralytics

[3] W. Lv et al., “DETRs Beat YOLOs on Real-time Object Detection.” 2023.