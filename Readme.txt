# Object Detection

This project is a real-time object detection web app built with React and TensorFlow.js using the COCO-SSD model. It uses your webcam to detect and highlight objects live in the browser.

## Features

- Real-time object detection using [COCO-SSD](https://github.com/tensorflow/tfjs-models/tree/master/coco-ssd)
- Live webcam video stream
- Bounding boxes and labels drawn on detected objects
- Built with [Create React App](https://github.com/facebook/create-react-app)

## Getting Started

### Prerequisites

- Node.js (>=12)
- Yarn or npm

## Project Structure

```
src/
  App.js           # Main React component
  App.css          # Styles
  index.js         # Entry point
  index.css        # Global styles
  utilities.js     # Drawing utilities for bounding boxes
public/
  index.html       # HTML template
  ...
```

## How It Works

- Loads the COCO-SSD model with TensorFlow.js.
- Captures video from your webcam using `react-webcam`.
- Runs object detection on each frame.
- Draws bounding boxes and labels for detected objects on a canvas overlay.

## Dependencies

- [React](https://reactjs.org/)
- [TensorFlow.js](https://www.tensorflow.org/js)
- [COCO-SSD Model](https://github.com/tensorflow/tfjs-models/tree/master/coco-ssd)
- [react-webcam](https://github.com/mozmorris/react-webcam)

## Scripts

- `yarn start` – Run the app in development mode
- `yarn build` – Build for production
- `yarn test` – Run tests
