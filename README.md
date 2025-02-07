# Computer-Vision

# AI-Enhanced Image Stitching and Edge Detection


This project showcases several image processing techniques and an AI-based object detection model. It includes functionalities for:

*   **Canny Edge Detection:** Identifying edges in images using the Canny algorithm.
*   **Difference of Gaussians (DoG):**  A technique used for blob detection and enhancing image features.
*   **AI-based Human Figure Detection:** Leveraging the SSD MobileNet V3 model for detecting human figures in images.
*   **Image Stitching:** Creating panoramic images by stitching multiple overlapping images together.
*   **Morphological Operations:** Applying morphological transformations to refine image results.

This README provides instructions on how to set up and run the Flask application that implements these features.

## Setup Instructions

1.  **Download and Extract the .rar File:**
    Download the compressed .rar file containing the Flask application. Use a file archiver like WinRAR, 7-Zip, or similar to extract the contents to a location of your choice.

2.  **Navigate to the Project Directory:**
    Open your terminal or command prompt and navigate to the directory where you extracted the contents of the .rar file using the `cd` command.

    ```bash
    cd path/to/extracted/folder
    ```

3.  **Set Up a Virtual Environment (Optional but Recommended):**
    It is highly recommended to use a virtual environment to manage dependencies for the Flask application. If you don't have `virtualenv` installed, you can install it using pip:

    ```bash
    pip install virtualenv
    ```

    Create a new virtual environment inside your project directory:

    ```bash
    virtualenv venv
    ```

    Activate the virtual environment:

    *   On Windows:
        ```bash
        venv\Scripts\activate
        ```

    *   On macOS/Linux:
        ```bash
        source venv/bin/activate
        ```

4.  **Install Dependencies:**
    Once the virtual environment is activated, install the necessary dependencies for the Flask application. The dependencies are listed in the `requirements.txt` file.

    ```bash
    pip install -r requirements.txt
    ```

5.  **Run the Flask Application:**
    After installing the dependencies, you can run the Flask application.

    ```bash
    python app.py
    ```

6.  **Access Your Flask Application:**
    The Flask application will be running locally. Open a web browser and navigate to `http://localhost:5000/` or the URL specified by your Flask application to access it.

7.  **Navigate Through the Application:**
    Use the navigation links provided on the home page to access different functionalities:

    *   **Home:** Overview of the project.
    *   **Image Stitching:** Upload and stitch images into a panoramic view.
    *   **Edge Detection:** Apply edge detection algorithms.
    *   **AI-based Object Detection:** Detect human figures in stitched images.

8.  **Explore Features:**

    *   Upload images for stitching and edge detection.
    *   Adjust parameters such as kernel size for edge detection.
    *   View processed images and results on respective pages.

9.  **Interact with the Application:**

    *   Use the buttons and forms provided on each page to interact with the application.
    *   Follow on-screen instructions and prompts for image uploads, parameter adjustments, and result viewing.

10. **Stop Flask Server:**
    To stop the Flask development server, press `Ctrl + C` in the terminal/command prompt where the server is running.
