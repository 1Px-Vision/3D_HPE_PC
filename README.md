# 3D_HPE_PC

Capturing 3D human pose and body shape from a single monocular image is a significant challenge in computer vision. Traditional RGB-based methods often need help with varying lighting conditions and occlusions. 
However, advancements in imaging technologies have introduced single-pixel imaging (SPI), which can overcome these limitations. SPI is particularly effective in capturing 3D human pose in the near-infrared (NIR) 
spectrum. NIR wavelengths can penetrate clothing and are less affected by lighting variations than visible light, providing a reliable means to accurately capture body shape and pose data, even in challenging 
environments.

# Project Description
In this work, we explore using an SPI camera operating in the NIR range, with Time-of-Flight (TOF) technology at wavelengths of 850-1550 nm, to detect humans in nighttime environments. 
Our proposed system employs SPI for depth estimation and feature extraction in humans. These features then generate point clouds integrated into a 3D body model (SMPLX) via 3D body 
shape regression. This process utilizes deep learning techniques based on self-supervised 3D human mesh methodologies.

![](https://github.com/1Px-Vision/3D_HPE_PC/blob/main/3D_HPE_Model.jpg)

# Experimental Setup

We constructed a laboratory scenario simulating night-time conditions to evaluate the efficacy of NIR-SPI 3D image reconstruction. This setup allowed us to test the feasibility of using NIR-SPI as a vision 
sensor in outdoor environments.

![](https://github.com/1Px-Vision/3D_HPE_PC/blob/main/3D_result_HPE.jpg)

# Results and Future Work
By assessing the results obtained from this setup, we aim to demonstrate the potential of NIR-SPI as an effective tool for detecting humans in night-time scenarios and accurately capturing their 3D body pose 
and shape. This work has future applications in environmental rescue and other fields requiring reliable human detection and pose estimation in low-light conditions.

![](https://github.com/1Px-Vision/3D_HPE_PC/blob/main/3D_future_HPE.jpg)
