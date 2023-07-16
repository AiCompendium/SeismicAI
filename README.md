# SeismicAI
SeismicAI: Earthquake Detection and Monitoring App
Notice: This project is under devlopment. Not fully functional yet. 
SeismicAI is an advanced application that utilizes artificial intelligence and machine learning techniques to detect and monitor earthquakes based on seismic and structural data. The app provides a comprehensive solution for earthquake detection, evaluation, and continuous monitoring.

## Features

- **Data Collection:** Collect seismic and structural data from reliable sources.
- **Data Preprocessing:** Clean and organize the data by handling missing values and performing necessary preprocessing steps.
- **Feature Extraction:** Extract relevant features from the seismic and structural data to enhance earthquake detection.
- **Algorithm Selection:** Choose an appropriate machine learning algorithm (e.g., Random Forest) for earthquake prediction.
- **Data Splitting:** Split the data into training and testing sets for model evaluation.
- **Feature Scaling:** Scale the features to improve model performance using the StandardScaler.
- **Model Training:** Train the selected machine learning algorithm using the training data.
- **Model Evaluation:** Evaluate the model's performance using accuracy, precision, recall, and F1 score.
- **Deployment and Integration:** Integrate the model into the desired application and implement a user-friendly interface for earthquake detection functionality.
- **Continuous Monitoring and Improvement:** Periodically evaluate the model's performance, collect new data, and update the model to enhance accuracy and adaptability.

## Installation

1. Clone this repository: `git clone https://github.com/AiCompendium/SeismicAI.git `
2. Install the required dependencies: `pip install -r requirements.txt`
3. Download the seismic and structural data and place them in the appropriate directories.
4. Run the app: `seismicai.py`

## Usage

1. Launch the SeismicAI app.
2. Enter the required input, such as location coordinates, to detect earthquakes.
3. The app will process the input, perform feature extraction, scale the features, and predict the occurrence of earthquakes.
4. View the prediction results and relevant metrics such as accuracy, precision, recall, and F1 score.

## License

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
