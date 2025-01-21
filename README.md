# **COMOT: Cell Counting and Motility Observation Tool**

**COMOT** is a tool designed for cell counting and motility observation in a video. Currently, it supports `.mp4` and `.mov` file formats.

---

## **Installation**

### **Windows Binary**

A pre-compiled Windows version is available in the [releases](#) section. Follow these steps to use it:
1. Download the `.zip` file from the release page.
2. Extract the contents of the `.zip` file.
3. Navigate to the `app` folder.
4. Run `app.exe` to launch the tool.

### **Running from Python**

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

---

## **Usage**

1. **Load Video:**
   - Open the application and load the video file you want to analyze.

2. **Mask Glass Area:**
   - Use the masking tool to define the glass area.

3. **Main Window:**
   - After masking, the main window will appear. Refer to the annotated image below for details about each component:
     ![Main Window Annotation](#)

4. **Proceed to Analysis:**
   - Click the **Proceed** button.

5. **Set Time Range:**
   - Specify the start and end times for analysis.

6. **Confirm and Process:**
   - Click **OK** to process the video.

7. **Save Results:**
   - Once the analysis is complete, save the results as either `.csv` or `.png`.

