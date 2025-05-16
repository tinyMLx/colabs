# TinyMLx edX  (development)

## Changes
- [3-3-7], [3-3-10] Fixed version of numpy, tensorflow, and tensorflow-datasets, tensorflow-hub, and protobuf.
- [3-3-4] Install Tensorflow 2.14.0
- [2-3-3], datasets.ascent() --> datasets.ascent().astype(np.int32)

# TinyMLx edX  (2024-11-20)

## Changes
- [2-3-3], datasets.ascent() --> datasets.ascent().astype(np.int32)
- [3-8-13], [3-8-16], [3-10-7] Install Tensorflow 2.10.0.
- [3-5-18], [3-7-11]Install Tensorflow 2.10.0.
- [3-4-3] Fixed the module import error for `Model.py`
- [3-4-3] Fixed the path of the `schema_v3.fbs` file in the tensorflow/lite schema.
- [3-4-3] Fixed the compiler flag to stop treating warnings as errors.
- [3-3-12] Install Tensorflow-model-optimization 0.7.3
- [3-3-7], [3-3-10], [3-3-12], [3-3-14] Install Tensorflow 2.10.0, tensorflow-hub 0.12.0, tensorflow-datasets 4.6.0
- [3-3-4] Install Tensorflow 2.10.
- [3-3-4] Tensorflow expects a numpy array as input for the model.predict() method.
- [2-1-9], [2-2-5]  Tensorflow expects a numpy array as input for the model.predict() method.
- [2-3-7] model.input --> model.inputs
- [2-4-3] lr --> learning_rate, model.input --> model.inputs
- [2-4-6] lr --> learning_rate, model.input --> model.inputs



# TinyMLx edX (unreleased)

## Changes
- [4-4-8] Fixed download link for flatbuffers
- [4-4-8] Fixed tflite Model import


## Changes
- [3-5-13] TF v2.4.1 --> TF v2.14.0

## Changes
- [3-10-7] Static image links are replaced.
- [4-6-8] import tensorflow as tf --> import tensorflow.compat.v1 as tf and deactivate re-installing tensorflow
- [4-4-8] %tensorflow_version 1.x --> %tensorflow_version 2.x
- [4-4-8] flatbuffers==1.12 --> flatbuffers==23.5.6



# TinyMLx edX 0.1.2 (2023-08-15)

## Changes
- [3-8-16] `lr` --> `learning_rate`
- [3-7-11] Fixed data link.
- [3-5-18] Fixed tf1 -> tf2 compatibility issues (see [#16](https://github.com/tinyMLx/colabs/pull/16))
- [3-3-7] Fixed a typo in metadata. 


# TinyMLx edX 0.1.1 (2023-07-21)

## Changes
- [2-3-3] 
  - `from scipy import misc` --> `from scipy import datasets`
  - `misc.ascent()` --> `datasets.ascent()`
  - DeprecationWarning: scipy.misc.ascent has been deprecated in SciPy v1.10.0; 
    and will be completely removed in SciPy v1.12.0. Dataset methods have moved 
    into the scipy.datasets module. Use scipy.datasets.ascent instead.
- Fixed broken links in 2-x-x colabs. 
- In data links: `laurencemoroney-blog.appspot.com` --> `learning-datasets`
- [2-1-6] Only supports tf 2 and python 3.
- [2-1-4] Comments on the code maximum length is 80 characters.
- `fstring` is used for string formatting.
