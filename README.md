# Vehicle Detection and Counting App

This project is a **Vehicle Detection and Counting App** built with [Streamlit](https://streamlit.io/) and [OpenCV](https://opencv.org/) to detect and count vehicles in videos. It uses computer vision techniques to detect vehicles, track them, and compute metrics such as vehicle count, average speed, and vehicle density.

## Features
- **Video Source Options**: Select pre-uploaded videos or upload your own.
- **Customizable Settings**: Adjust video resolution, frame rate, and detection sensitivity.
- **Display Options**: Show bounding boxes, object IDs, and tracking paths.
- **Statistics**: Display vehicle count, average speed, and vehicle density in real time.
- **User Controls**: Play, pause, and stop video processing at any time.

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/vehicle-detection-app.git
    cd Vehicle-Detection
    ```
    
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```

## Usage

1. Select a video source from the sidebar (pre-uploaded videos or your own uploaded video).
2. Customize the video resolution, frame rate, and detection sensitivity.
3. Choose the display options (bounding boxes, object IDs, tracking paths).
4. Optionally, enable average speed and vehicle density statistics.
5. Use the controls (Play, Pause, Stop) to manage the video playback and processing.
6. View real-time video frames and vehicle counting results in the main app window.

## File Structure

- `app.py`: Main application file for the Streamlit app.
- `vehicle_counter.py`: Contains the core logic for vehicle detection, tracking, and counting.
- `videos/`: Directory containing sample videos.
- `temp/`: Temporary storage for uploaded videos.

## Future Enhancements

- Integrating additional vehicle attributes such as type and color detection.
- Exporting vehicle counting and tracking data to CSV format.
- Improving performance with GPU acceleration.

## App Demo 
![App_Demo](https://github.com/user-attachments/assets/5ab99400-b379-471e-9d14-8b33ccac76b0)

## License

This project is licensed under the MIT License.

---

**Developed by Mohamed Shamsudeen**
