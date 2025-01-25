# **COMOT: Cell Counting and Motility Observation Tool**

**COMOT** is a tool designed for cell counting and motility observation in a video. Currently, it supports `.mp4` and `.mov` file formats.

---

## **Installation**

### **Windows Binary**

A pre-compiled Windows version is available in the [releases](https://github.com/d191761/comot/releases) section. Follow these steps to use it:
1. Download the `.zip` file from the release page.
2. Extract the contents of the `.zip` file.
3. Navigate to the `app` folder.
4. Run `app.exe` to launch the tool.

### **Running from Python (MacOS, Windows, Linux)**

To run the tool from Python, follow these steps:

1. **Set up a Python environment:**
   - Create and activate a Python environment using either `venv` or `conda`.

2. **Install COMOT:**
   - Navigate to the `comot` folder in the repository.
   - Run the following command:
     ```bash
     pip install -e .
     ```

3. **Run the application:**
   - Navigate to the `app` folder.
   - Start the application by running:
     ```bash
     python app.py
     ```

* Tested on `macOS Sequioa 15.1.1, Windows 10 10.0.19045, MX Linux 23`
---

## **Usage**

1. **Load Video:**
   - Open the application and load the video file you want to analyze using `Load Video` button.

2. **Mask Glass Area:**
   - Use the masking tool to define the glass area, by clicking on the image area then click `masking` button when done.

3. **Main Window:**
   - After masking, the main window will appear. Refer to the annotated image below for details about each component:

![Main Window Annotation](docs/comot_main_with_annotation.png)

4. **Proceed to Analysis:**
   - Click the `Results` button.

5. **Set Time Range:**
   - Specify the start and end times for analysis.

6. **Confirm and Process:**
   - Click **process** to process the video.

7. **Save Results:**
   - Once the analysis is complete, save the results as either `.csv` or `.png`.

---
## Dataset

The dataset used in the paper can be downloaded trough this [link](#)

