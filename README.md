# PINNs
Physics-Informed Neural Networks

Scientific machine learning (SciML) represents a significant advancement by integrating machine learning (ML) with scientific methodologies. At the forefront of this progress are Physics-Informed Neural Networks (PINNs), which offer a promising solution. Unlike conventional neural networks, PINNs incorporate physical principles, reducing the reliance on extensive datasets. Automatic differentiation further streamlines the integration of physical models into the network, enhancing adaptability and effectiveness.

This project explores the capabilities and constraints of DeepXDE, a powerful framework leveraging PINNs, to address both forward and inverse problems in understanding dielectric properties.

# Forward Mode
Forward Mode: Predicting Dielectric Properties of HVDC Insulation Systems

This repository contains the implementation of forward-mode Physics-Informed Neural Networks (PINNs) using TensorFlow and DeepXDE. The model is designed to predict the dielectric properties of materials used in High Voltage Direct Current (HVDC) insulation systems. By inputting physical parameters, the network solves the governing differential equations to simulate the behavior of the system, providing insights into the material properties under various conditions.


# Inverse Mode
Inverse Mode: Inferring Material Parameters Using Synthetic Data(Analytical Solution)

This repository showcases the inverse-mode implementation of Physics-Informed Neural Networks (PINNs) using TensorFlow and DeepXDE. In this approach, the model is trained to infer unknown material parameters of HVDC insulation systems by fitting the network to synthetic data generated from analytical solutions. By solving the governing differential equations and adjusting the parameters to match the synthetic data, the model accurately extracts critical material properties, demonstrating its potential for applications in dielectric spectroscopy and beyond.

# Natural logarithm approach
Further analysis revealed that the natural logarithm approach significantly improved the model’s performance in both forward and inverse modes. By pre- dicting the natural logarithm of the current (ln(I)), sensitivity issues were mit- igated, and the model’s accuracy and robustness were enhanced across various scenarios.
