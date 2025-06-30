# UDA-IIT-Mandi Organization

## Overview

This GitHub organization showcases research projects on **Unsupervised Domain Adaptation (UDA)** conducted during a research internship at the **Indian Institute of Technology (IIT) Mandi** under the **School of Computing and Electrical Engineering**. Our work focuses on advancing domain adaptation techniques for audio scene classification, with applications of gradient reversal layers and cycle self-training methodologies.

## Research Focus

Our team worked under the guidance of **Dr. Padmanabhan Rajan** and **Abhishek Dileep** (Research Scholar), exploring approaches to domain adaptation challenges in acoustic scene classification. The primary research areas include:

- **Unsupervised Domain Adaptation** techniques for cross-device audio classification
- **Audio scene classification** using transformer models
- **Transfer learning** across different recording devices and environments
- **Feature extraction methods** using pre-trained audio transformers (PaSST)
- **Cross-device domain adaptation** for real-world acoustic applications

## Repositories

### [UDA-Gradient-Reversal-Layer](https://github.com/UDA-IIT-Mandi/UDA-Gradient-Reversal-Layer)

**First Project**: Implementation of unsupervised domain adaptation using Gradient Reversal Layer (GRL) with PaSST feature extractors for cross-device acoustic scene classification.

**Key Features:**
- **Domain-Adversarial Neural Networks (DANN)** with gradient reversal layers
- **PaSST Integration**: Pre-trained audio transformers as feature extractors
- **Cross-Device Evaluation**: Device A → Devices B,C,S1-S6 adaptation
- **Computer Vision Validation**: SVHN→MNIST implementation for method verification

**Technical Highlights:**
- **Architecture**: PaSST (768-dim) → 768→512→256 adaptation layers → 10-class classifier
- **Dataset**: DCASE TAU 2020 Mobile (64 hours, 10 acoustic scenes)
- **Results**: 70.37% overall accuracy, 22.76% improvement over source-only training
- **Innovation**: Novel combination of audio transformers with adversarial domain adaptation

**Technologies:**
- Python, PyTorch, Jupyter Notebooks
- PaSST (Patchout Audio Spectrogram Transformer)
- DCASE TAU 2020 dataset
- Gradient Reversal Layer implementation

### [UDA-Cycle-Self-Training](https://github.com/UDA-IIT-Mandi/UDA-Cycle-Self-Training)

**Second Project**: Implementation of Unsupervised Domain Adaptation using Cycle Self-Training (CST) with enhanced loss functions and consistency regularization.

**Key Features:**
- **Cycle Self-Training (CST)** with source-target-source consistency
- **Enhanced Loss Function**: Combined Tsallis entropy, CST loss, and FixMatch
- **FixMatch Integration**: Consistency regularization with strong/weak augmentations
- **SAM Optimizer**: Sharpness-Aware Minimization for improved generalization

**Technical Highlights:**
- **Architecture**: PaSST + CST framework with multi-component loss
- **Loss Components**: CE + Tsallis (λ₁=0.1) + CST (λ₂=0.3) + FixMatch (λ₃=0.4)
- **Results**: 66.57% overall accuracy with improved target domain performance
- **Innovation**: First application of cycle self-training to audio domain adaptation

**Technologies:**
- Python, PyTorch, Jupyter Notebooks
- Cycle Self-Training methodology
- FixMatch consistency regularization
- SAM (Sharpness-Aware Minimization) optimizer
- Audio-specific augmentations and transformations

## Team Members

Our research team consists of two groups working collaboratively under expert supervision:

### Group 1
- **Ronn Mathew Sino** 
- **Noah Thomas**

### Group 2
- **K J Theophene Xavier Lynn**
- **Advaith S Menon** 

### Mentors and Guides
- **Dr. Padmanabhan Rajan** - Associate Professor, School of Computing and Electrical Engineering, IIT Mandi
- **Abhishek Dileep** - Research Scholar, IIT Mandi
- **Dr. Divya James** - Associate Professor, Rajagiri School of Engineering & Technology (Advisor)

## Technical Stack

### Core Technologies
- **Python** - Primary programming language
- **PyTorch** - Deep learning framework
- **Jupyter Notebooks** - Interactive development environment
- **NumPy, Pandas** - Data processing and analysis
- **Librosa** - Audio processing and feature extraction

### Domain Adaptation Libraries
- **PaSST** - Pre-trained audio transformers
- **DALib** - Domain adaptation algorithms
- **Custom Implementations** - GRL, CST, and supporting utilities

### Audio Processing
- **DCASE TAU 2020** - Primary evaluation dataset
- **Audio Transformations** - Augmentation and preprocessing pipelines
- **Cross-Device Evaluation** - Multi-device testing framework

## Contact Information

For inquiries about our research, collaboration opportunities, or technical questions:

### Research Team
- **Ronn Mathew Sino**: [GitHub Profile](https://github.com/RonnMath03)
- **Noah Thomas**: [GitHub Profile](https://github.com/noahthomas6111)
- **K J Theophene Xavier Lynn**: [GitHub Profile](https://github.com/lynntheophene)

### Faculty Supervision
- **Dr. Padmanabhan Rajan** - Associate Professor, IIT Mandi
- **School of Computing and Electrical Engineering, IIT Mandi**

### Organization
- **Institution**: Indian Institute of Technology (IIT) Mandi
- **Department**: School of Computing and Electrical Engineering
- **Research Focus**: Machine Learning, Domain Adaptation, Audio Signal Processing

## Acknowledgments

We express our sincere gratitude to:

- **IIT Mandi** and the **School of Computing and Electrical Engineering** for providing research opportunities and computational resources
- **Dr. Padmanabhan Rajan** for expert guidance and supervision throughout the internship
- **Abhishek Dileep** for mentorship and technical insights
- **DCASE Community** for providing high-quality datasets and evaluation frameworks
- **Open Source Community** for foundational implementations (DANN-pytorch, PaSST, CST)

## License and Usage

These projects are developed for academic and research purposes. Please refer to individual repository licenses:
- Research use: Freely available for academic research
- Commercial use: Requires permission and proper attribution
- Dataset usage: Subject to DCASE TAU 2020 license terms

---

**Last Updated**: June 2025 | **Projects**: 3 Completed
