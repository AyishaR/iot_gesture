# Gesture recognition using TinyML devices — home automation applications

This notebook uses the accelerometer and gyroscope sensors for gesture recognition.

Gestures are mapped to the corresponding sensor values recorded during motion. Here, we have accelerometer and gyroscope values along x, y, z axes recorded 100 times for one gesture, i.e, 600 data points for one gesture.

### Dataset collection

Check out the app used to record the gestures [here](https://github.com/AyishaR/Sensor_data_app)

This app returns a text file containing n lines, each with 601 values (sensors + gesture name). These values were then consolidated using the csv library.

