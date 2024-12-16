# TinyML - EfficientML Notebooks

Welcome to the TinyML Repository! This collection of notebooks provides insights and hands-on experience in deploying machine learning models on small, low-power devices, such as microcontrollers, sensors, and embedded systems. TinyML focuses on optimizing machine learning models to run efficiently on devices with limited computational resources.

## Overview of TinyML

TinyML refers to the deployment of machine learning models on small, energy-efficient devices. It enables real-time, on-device processing with minimal power consumption, making it ideal for battery-powered and edge computing applications. Models need to be optimized for devices with constraints in memory, processing power, and energy.

### Key Characteristics of TinyML:
- **Low Power Consumption**: Optimized to run with minimal power, extending battery life.
- **Limited Computational Resources**: Simplified models fit within device constraints.
- **Real-Time Inference**: Models process data and make decisions in real-time.
- **On-Device Processing**: Models run directly on the device, reducing latency and improving privacy.

## Contents of the Repository

This repository contains a series of notebooks that explore various aspects of TinyML and modern machine learning techniques:

### Notebooks:

1. **Introduction_to_PyTorch.ipynb**  
   Introduction to PyTorch, covering basics like tensors, automatic differentiation, and model training.

2. **Model_Training.ipynb**  
   Training machine learning models, setting up datasets, and optimizing model performance.

3. **Transformer.ipynb**  
   Overview of the Transformer architecture and its use in NLP tasks with self-attention mechanisms.

4. **Network_Pruning.ipynb**  
   Techniques for reducing neural network size while maintaining performance for TinyML.

5. **Quantization.ipynb**  
   Model quantization to reduce weight precision, making models more efficient for low-power devices.

6. **Dataset_Distillation.ipynb**  
   Creating smaller, efficient datasets that maintain performance for TinyML applications.

7. **Scaling_Laws.ipynb**  
   How model size, data size, and compute resources impact performance, and trade-offs for TinyML.

8. **Reinforcement_Learning_with_Human_Feedback_RLHF.ipynb**  
   Using human feedback in reinforcement learning to improve TinyML applications.

9. **Diffusion_Models.ipynb**  
   Introduction to diffusion models and their potential in generative tasks like image synthesis.

10. **Diffusion_Advanced.ipynb**  
    Advanced concepts in diffusion models, including optimization and real-world applications.

11. **Mixture_of_Experts_MoE.ipynb**  
    Exploring the Mixture of Experts (MoE) model, which uses multiple "expert" sub-models for scalability.

12. **LoRA.ipynb**  
    Low-Rank Adaptation (LoRA) technique for fine-tuning pre-trained models with fewer parameters.

---

### Additional Notebooks:

1. **Evolutionary Algorithm**  
   A deep dive into evolutionary algorithms, used for optimizing machine learning models by mimicking natural selection.

2. **Binary_Convolution.ipynb**  
   Exploring binary convolutional networks, which reduce model size by using binary weights.

3. **Logical_XNOR_Network.ipynb**  
   A notebook discussing XNOR networks, which use logical operations for efficient neural network design.

4. **Symmetric_&_Assymetric_Quantization.ipynb**  
   An exploration of symmetric and asymmetric quantization techniques for optimizing model performance in TinyML.

## Installation

To use the notebooks in this repository, you will need to install the following dependencies:

```bash
pip install torch torchvision torchaudio
pip install numpy pandas matplotlib
pip install sklearn
pip install tqdm
```

Check individual notebooks for any additional dependencies.

## Usage

Clone this repository to your local machine:

```bash
git clone https://github.com/Razaimam45/TinyML-Notebooks-by-Raza.git
```

Navigate to the directory and open the notebooks using Jupyter or any compatible viewer:

```bash
cd TinyML-Notebooks-by-Raza
jupyter notebook
```

## Contributions

Feel free to contribute by opening issues, submitting pull requests, or suggesting improvements. All contributions are welcome!

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Acknowledgments

We would like to acknowledge the **TinyML and LLMs (ML819) course** for its valuable collection by **Zhiqian Shen** at [**MBZUAI**](https://mbzuai.ac.ae/) which led to the creation of this repository.

---

Enjoy exploring TinyML and happy learning!
