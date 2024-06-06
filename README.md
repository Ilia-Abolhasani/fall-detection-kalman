# Fall Detection System using Deep Learning and Kalman Filters

This project implements a fall detection system using deep learning techniques and Kalman filters to process signals from the Sysfall dataset. The system aims to accurately detect falls, enhancing safety and improving response times.

## Repository Structure

- `/`: Jupyter notebooks containing the implementation.
- `figs/`: Directory containing the figures generated during the project.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Ilia-Abolhasani/fall-detection-kalman.git
    cd fall-detection-kalman
    ```
2. Install the required packages:
    ```bash
        pip install python-bidi
        pip install arabic-reshaper
        pip install scipy
    ```

## Project Overview

### Signal Processing

#### Accelerometer Signals:
<div style="display: flex; justify-content: space-around;">
  <div style="text-align: center;">
    <p>Before Kalman Filter:</p>
    <img src="./figs/accelerator-sensor-before-kalman.png" alt="Accelerator Sensor Before Kalman" width="600">
  </div>
  <div style="text-align: center;">
    <p>After Kalman Filter:</p>
    <img src="./figs/accelerator-sensor-after-kalman.png" alt="Accelerator Sensor After Kalman" width="600">
  </div>
</div>

#### Gyroscope Signals
<div style="display: flex; justify-content: space-around;">
  <div style="text-align: center;">
    <p>Before Kalman Filter:</p>
    <img src="./figs/gyroscope-sensor-before-kalman.png" alt="Gyroscope Sensor Before Kalman" width="600">
  </div>
  <div style="text-align: center;">
    <p>After Kalman Filter:</p>
    <img src="./figs/gyroscope-sensor-after-kalman.png" alt="Gyroscope Sensor After Kalman" width="600">
  </div>
</div>

#### Signal Magnitude Area (SMA) Comparison
<div style="display: flex; justify-content: space-around;">
  <div style="text-align: center;">
    <p>Accelerometer:</p>
    <img src="./figs/accelerator-sma-compare.png" alt="Accelerator SMA Compare" width="600">
  </div>
  <div style="text-align: center;">
    <p>Gyroscope:</p>
    <img src="./figs/gyroscope-sma-compare.png" alt="Gyroscope SMA Compare" width="600">
  </div>
</div>

### Data Analysis

#### Activity Frequency
<img src="./figs/activity-freq.png" alt="Activity Frequency" width="500">

#### State Frequency
<img src="./figs/state-freq.png" alt="State Frequency" width="500">

#### Distribution Standardization
<img src="./figs/dis-standardization.png" alt="Distribution Standardization" width="500">

#### State Label Example
<img src="./figs/state-label-example.png" alt="State Label Example" width="500">

### Model and Performance

#### Deep Learning Model Architecture
<img src="./figs/dl-model.png" alt="Deep Learning Model" width="500">

#### State Confusion Matrix
<img src="./figs/state-confusion-matrix.png" alt="State Confusion Matrix" width="500">

## Usage

Run the Jupyter notebooks to reproduce the results and visualizations shown above.

## Contributing

Feel free to submit issues or pull requests if you have suggestions for improvements or find any bugs.

## License

This project is licensed under the MIT License.
