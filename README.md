# Safety Helmet Detection using YOLOv8 and Faster R-CNN

## Introduction

In the field of construction and heavy industry, safety is of paramount importance. One of the key safety measures is the use of safety helmets. However, monitoring whether every worker is wearing a safety helmet can be a challenging task.

This project aims to automate the process of safety helmet detection by leveraging the power of deep learning. We use two state-of-the-art object detection models, YOLOv8 (You Only Look Once version 8) and Faster R-CNN (Region Convolutional Neural Networks). These models have been trained to detect and classify whether a person in an image or video stream is wearing a safety helmet or not.

The use of these models allows for real-time detection and classification, making it a viable solution for integration into existing surveillance systems. This could greatly enhance safety measures in the workplace, potentially preventing accidents and saving lives.
## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

* You have installed the latest version of Python (Python 3.7 or higher is recommended).
* You have a Windows/Linux/Mac machine with a decent GPU. This is because both YOLOv8 and Faster R-CNN are computationally intensive models.
* You have installed the necessary Python libraries and frameworks, including but not limited to PyTorch, torchvision, OpenCV, NumPy, and Matplotlib. You can install these using pip:

### Installation

## Setting Up the Development Environment

1. **Install Python:** The project is implemented using Python. If you don't have Python installed, you can download it from the official website: https://www.python.org/downloads/. We recommend using Python 3.7 or higher.

2. **Install PyTorch:** This project uses PyTorch as the deep learning framework. You can install it by following the instructions on the official PyTorch website: https://pytorch.org/get-started/locally/.

3. **Clone the Project Repository:** Use git to clone the project repository to your local machine. Open your terminal and run:


4. **Navigate to the Project Directory:** Change your current directory to the project directory:

```bash cd Safety-Helmet-Detection-using-YOLOv8-and-Faster-R-CNN``

5. **Install Required Libraries:** Install the necessary Python libraries and frameworks using pip:

```bashpip install torchvision opencv-python numpy matplotlib``

6. **Download Pre-trained Models:** Download the pre-trained YOLOv8 and Faster R-CNN models and place them in the `models/` directory.

7. **Run the Project:** Finally, you can run the project.

## Usage

The Safety Helmet Detection system using YOLOv8 and Faster R-CNN can be used in a variety of scenarios, primarily in industries where safety helmets are mandatory. Here are a few examples:

1. **Construction Sites:** The system can be integrated with existing CCTV cameras to monitor whether all workers on site are wearing safety helmets.

2. **Factories and Industrial Areas:** Similar to construction sites, the system can ensure that all factory workers are adhering to safety protocols.

3. **Mining and Excavation Sites:** In these high-risk areas, the system can provide an additional layer of safety by continuously monitoring workers.

4. **Safety Training and Compliance:** The system can be used in training scenarios to automatically evaluate whether trainees are following safety protocols.

5. **Research and Development:** The project can also be used as a base for further research in the field of object detection and industrial safety.

Remember, the goal of this project is to enhance workplace safety by ensuring the use of safety helmets, potentially preventing accidents and saving lives.

## Results
![output](https://github.com/iSparshP/Safety-Helmet-Detection-using-YOLOv8-and-Faster-R-CNN/assets/77487266/86a0fce5-bdc5-43e5-8d4d-ca2dd23d2f74)

## License

This project is open for use by anyone. You are free to clone, modify, and distribute this project as you see fit. Please note that this project comes with no warranty.

For more details, please refer to the [LICENSE](LICENSE) file in the project repository.

## Acknowledgments


I would like to express my gratitude to the following individuals and institutions:

* **Priyam Dalmia** - for their invaluable guidance and support throughout the project.

I would also like to acknowledge the creators and the community of the open-source libraries and frameworks used in this project, including PyTorch, OpenCV, and the YOLOv8 and Faster R-CNN models. Their work has made this project possible.
