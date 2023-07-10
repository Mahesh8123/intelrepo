# intelrepo
# To run the Social Distance Detection project using the Intelrepo code, follow these steps:

# Download the code and move it to the "yolo-coco" folder.
https://drive.google.com/file/d/1LtekYJd3X_Pe4GgzQ4GzwFLjX92vyLeg/view?usp=drive_link

# Open your terminal.

# Change the directory to where you have downloaded the code.

# If you haven't installed Python 3, install it. If you already have Python 3 installed, you can skip this step.

# Create a virtual environment named "venv" by running the following command:

# Copy code
python3 -m venv venv
# Activate the virtual environment by running the following command:
# bash
# Copy code
source venv/bin/activate
# Install the Python dependencies related to this project, such as OpenCV, NumPy, SciPy, by running the following command:
# Copy code
pip install -r requirements.txt
# Run the following command to start the social distance detection:
css
Copy code
time python distance.py --input output1.mp4 --output output.avi --display 1
         or
time python distance.py --input CCTV_demo.mp4 --output output.avi --display 1
This command will analyze the "output1.mp4" video, generate an "output.avi" file, and display the output in a separate window.

After executing the command, a window will pop up showing the social distance detection in progress. Once the execution is complete, the "output.avi" file will be available in your current directory, containing the results of the social distance detection.
