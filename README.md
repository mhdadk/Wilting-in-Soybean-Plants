## Measuring wilting in soybean plant leaves using Convolutional Neural Networks

<p align="center">
  <img width="auto" height="75%" src="https://github.com/mhdadk/Wilting-in-Soybean-Plants/blob/master/alexnet_architecture.png">
</p>

This project involves fine-tuning AlexNet (shown above) to predict the different stages of wilting in soybean plants using images of these plants. This approach is also compared to using images with numerical weather data, such as temperature and humidity, with AlexNet and using numerical weather data alone with a support vector machine. The dataset used is available [here](https://drive.google.com/file/d/1YiSujqsSankP8cIOpiwbB9Ipz1k2KCIk/view?usp=sharing). The first approach using only images with AlexNet is implemented in `alexnet.py`. The second approach using images together with numerical weather data with AlexNet is implemented in `alexnet_numerical.py`. The final approach using only numerical weather data with a support vector machine is implemented in `svm_numerical.py`. Full implementation details and results can be found in `report.pdf`. 

