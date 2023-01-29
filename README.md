# facemask tracking using yolov7 + deepsort

This is the model for detecting the person and also it shows the how the person who wear mask or not

## Getting Started

This project needs GPU so I had done this project on colab.
This is an example of how you may give instructions on setting up your project locally.

### Prerequisites

Download and install [Python 3.10.0](https://www.python.org/ftp/python/3.10.0/python-3.10.0-amd64.exe)
Download yolov7 [YOLOV7](https://github.com/WongKinYiu/yolov7.git)
### Installation

1. First check python version in terminal, if it's 3.10.0 then go ahead.
   ```sh
   python --version 
   ```

2. Go to folder where you want to clone this repository and use below command to clone this repo to your local machine.
   ```sh
   git clone https://github.com/Dmeet6401/Facemask_Tracking_yolov7
   ```
3. Create virtual Environment 
   ```sh
   python -m venv venvForFacemask --system-site-packages
   ```

   To Activate our virtual environment we use 
   ```sh
   venvForFacemask/Script/Activate.bat
   ```
4. Install packages using requirements.txt
   ```sh
   pip install -r requirements.txt
   ```
4. Now check if streamlit is installed properly or not.
   ```sh
   streamlit version
   ```

## Usage

1. Run below command in terminal to run streamlit application. 
   ```sh
   streamlit run app.py
   ```
Now we are all set to go. just upload the image of any given class and it will classify drone is in the image or not.

[Download dataset for facemask](https://www.kaggle.com/datasets/andrewmvd/face-mask-detection?resource=download)
[Download datset for person detection](https://drive.google.com/file/d/1L7oxFqRi63APVi-ffeK3L7dF_qTkZmbW/view?usp=sharing) 

## Contact

Linkedin - [Meet Desai](https://www.linkedin.com/in/meet-desai-235655208)  
Gmail - [desai.meet06gmail.com](desai.meet06@gmail.com)  
Project Link -  [github.com/Dmeet6401/Facemask_Tracking_yolov7](https://github.com/Dmeet6401/Facemask_Tracking_yolov7)
