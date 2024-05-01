# Face Recognition Project with Flask

This project utilizes Flask and OpenCV for face recognition. It allows users to upload images, which are then processed to recognize faces and provide relevant information. The project uses a K-Nearest Neighbors classifier for face recognition.

## Installation

To run this project, follow these steps:

1. Clone this repository:

    ```
    git clone https://github.com/ToxicPanda-l3d/Face-Recognition-Flask.git
    ```

2. Navigate to the project directory:

    ```
    cd face-recognition
    ```

3. Install the required dependencies using pip:

    ```
    pip install -r requirements.txt
    ```

## Usage

1. Run the Flask application:

    ```
    python app.py
    ```

2. Open your web browser and go to [http://localhost:5000](http://localhost:5000).

3. You will see the home page where you can upload an image.

4. Upload an image containing faces.

5. Wait for the processing to complete. The page will display information about the recognized faces, if any.

## Libraries Used

- Flask: A web framework for Python.
- OpenCV (cv2): Library for computer vision and image processing.
- NumPy: Library for numerical computing.
- scikit-learn: Library for machine learning in Python.
- Pandas: Library for data manipulation and analysis.
- joblib: Library for saving and loading machine learning models.

## Files and Directory Structure

- `app.py`: Flask application file containing routes and logic for face recognition.
- `templates/`: Directory containing HTML templates for the web application.
- `static/`: Directory containing static files (e.g., CSS, JavaScript).
- `model/`: Directory containing trained machine learning models.

## Additional Notes

- Ensure that your system has a webcam connected if you plan to use real-time face recognition features.
- You may need to adjust the model parameters or fine-tune the pre-trained model based on your specific requirements and dataset.
- Experiment with different machine learning algorithms and hyperparameters for better face recognition accuracy.

## References

- [Flask Documentation](https://flask.palletsprojects.com/)
- [OpenCV Documentation](https://opencv.org/)
- [scikit-learn Documentation](https://scikit-learn.org/)
- [Pandas Documentation](https://pandas.pydata.org/)
- [joblib Documentation](https://joblib.readthedocs.io/)

## Contributors

- Feel free to contribute by submitting bug reports, feature requests, or pull requests. Thank you for using this project!