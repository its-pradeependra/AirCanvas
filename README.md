# Air Canvas - Draw Your Imagination

### Project Overview

This project leverages the OpenCV and Mediapipe libraries to enable real-time drawing using a webcam. The primary objectives of the project are as follows:

- **Hand Detection**: Utilize the Mediapipe library to detect hands in the webcam feed.
- **Finger State Detection**: Identify whether the index and middle fingers are raised.
- **Finger Tip Location Detection**: Determine the exact location of the tips of the fingers.
- **Drawing and Selection Mechanism**: 
  - Draw a line on the canvas when only the index finger is raised.
  - Implement a selection mode when both the index and middle fingers are raised.
- **Canvas Management**: Draw on a black canvas and subsequently mask the drawing onto the actual frame for display.

By integrating these functionalities, the project aims to create an interactive and intuitive drawing application that responds to finger movements detected via a webcam.


### Prerequisites and Setup Instructions

To successfully run this project, several prerequisites must be fulfilled. The following steps outline the process for setting up the required environment and installing necessary libraries:

Open your terminal within the specific Integrated Development Environment (IDE) for this project.

1. **Create a Virtual Environment**:
   - Create a virtual environment for the workspace by executing the command:
     'python3 -m venv env'

   - Note: To identify the available versions of Python, type `python` and press the Tab key. This example uses python3.

2. **Activate the Virtual Environment**:
   - Activate the Python 3 virtual environment by running the command:
     'source env/bin/activate'

   - Note: To determine the available versions of pip, type `pip` and press the Tab key. This example uses pip3.

3. **Install OpenCV Library**:
   - Install the OpenCV library by executing the command:
     'pip3 install opencv-python'

4. **Install MediaPipe Library**:
   - Install the MediaPipe library by executing the command:
     'pip3 install mediapipe'

Note-'pip install -r requirements.txt' by using this Command installed all necessary dependencies for the Project. If you don't want to follow 3,4 step.

By following these steps, you will set up the necessary environment and dependencies to run the project successfully.


### Execution of the Project

To successfully run this project. The following steps outline the process for execution are:

1. **Run the Project**:
   - Execute your Python file to run the code by using the command:
     'python3 main.py'

     or

   - Execute Main Python file in Dedicated Terminal.

By following these steps, you will execute the project successfully.