# Pre-trained TensorFlow.js models

This repository hosts a set of pre-trained models that have been ported to
TensorFlow.js.

The models are hosted on NPM and unpkg so they can be used in any project out of the box. They can be used directly or used in a transfer learning
setting with TensorFlow.js.

To find out about APIs for models, look at the README in each of the respective
directories. In general, we try to hide tensors so the API can be used by
non-machine learning experts.

For those intested in contributing a model, please file a GitHub issue to gauge
interest. We are trying to add models that complement the existing set of models
and can be used as building blocks in other apps.

## Models

### Image classification
- [MobileNet](https://github.com/tensorflow/tfjs-models/tree/master/mobilenet) - Classify images with labels from the [ImageNet database](http://www.image-net.org/).
  - `npm install @tensorflow-models/mobilenet`
- [PoseNet](https://github.com/tensorflow/tfjs-models/tree/master/posenet) - Realtime pose detection. Blog post [here](https://medium.com/tensorflow/real-time-human-pose-estimation-in-the-browser-with-tensorflow-js-7dd0bc881cd5).
  - `npm install @tensorflow-models/posenet`
