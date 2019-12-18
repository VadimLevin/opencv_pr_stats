# Problematic pull requests
## Stable reproducers
 - [PR#15860](https://github.com/opencv/opencv/pull/15860): core(test): Test control characters in yml

   __Description__:<br/>
```
Reproducer for #6897

 Please use this line to close one or multiple issues when this pullrequest gets merged
You can add another line right under the first one:
resolves #1234
resolves #1235


This pullrequest changes

 Please describe what your pullrequest is changing 

```
 - [PR#15311](https://github.com/opencv/opencv/pull/15311): `solvePnP`and 'projectPoints' for calib3d and face module

   __Description__:<br/>
```
reproducer for #15299


opencv_contrib=master
force_builders_only=Custom
buildworker:Custom=linux-1,linux-2,linux-4
docker_image:Custom=javascript

```
## WIP
 - [PR#16164](https://github.com/opencv/opencv/pull/16164): [WIP] cuda4dnn(conv): fuse eltwise with convolutions

 - [PR#16134](https://github.com/opencv/opencv/pull/16134): [WIP] Python bindings improvements.

 - [PR#16118](https://github.com/opencv/opencv/pull/16118): WIP: G-API: GOpaque implementation

 - [PR#16010](https://github.com/opencv/opencv/pull/16010): [WIP] fix and enable tests for `DNN_TARGET_CUDA_FP16`

 - [PR#15463](https://github.com/opencv/opencv/pull/15463): DNN: multiple outputs for asynchronous inference

 - [PR#15214](https://github.com/opencv/opencv/pull/15214): WIP: imgproc: templmatch: Add support for mask for all methods 

 - [PR#15087](https://github.com/opencv/opencv/pull/15087): [WIP] Support ROI + UMat in own::Mat

 - [PR#14666](https://github.com/opencv/opencv/pull/14666): Python code examples for file IO in xml and yml format

 - [PR#14135](https://github.com/opencv/opencv/pull/14135): Heterogeneous plugin of Intel's Inference Engine

 - [PR#14107](https://github.com/opencv/opencv/pull/14107): Adding python codes to samples/python

 - [PR#12481](https://github.com/opencv/opencv/pull/12481): build: OpenCV includes

 - [PR#12290](https://github.com/opencv/opencv/pull/12290): 16-bit Grayscale and 48 bit RGB with FFV1 lossless as part of #12284 with tests

 - [PR#12186](https://github.com/opencv/opencv/pull/12186): samples: refactor DNN model downloading

 - [PR#10318](https://github.com/opencv/opencv/pull/10318): For various PR tests

 - [PR#10131](https://github.com/opencv/opencv/pull/10131): JUST TEST

## Problem: pr: needs rebase
 - [PR#16169](https://github.com/opencv/opencv/pull/16169): fix parameter description of angle of cv.ellipse()

   __Description__:<br/>
```
 Please use this line to close one or multiple issues when this pullrequest gets merged
You can add another line right under the first one:
resolves #1234
resolves #1235


This pullrequest changes parameter description of angle of cv.ellipse()

 Please describe what your pullrequest is changing 

```
 - [PR#15993](https://github.com/opencv/opencv/pull/15993):  This is a correction of the previously missleading documentation and a warning related to a common calibration failure described in issue #15992

   __Description__:<br/>
```
This pullrequest changes

 Please describe what your pullrequest is changing 
#15992
```
 - [PR#14107](https://github.com/opencv/opencv/pull/14107): Adding python codes to samples/python

   __Description__:<br/>
```
There are some files in samples/cpp whose python samples are not available. So, this PR is just adding "laplace.py" python code for laplace.cpp .
Added drawing.py to samples/python as it's code is not present 


**WIP**
force_builders=Docs
test_modules=none

```
## Problem: incomplete
 - [PR#16160](https://github.com/opencv/opencv/pull/16160): optimize cvCeil and cvFloor in fase_math.hpp

   __Description__:<br/>
```
This pullrequest changes

 This pull request will optimize the cvCeil and cvFloor with the GNUC function ceil() and floor() if GNUC is defined. cvRound already implemented this optimization but cvCeil and cvFloor have not 

```
## Problem: pr: needs test
 - [PR#16011](https://github.com/opencv/opencv/pull/16011): Fix #16007 - colinearity computed using all 3 coordinates

   __Description__:<br/>
```
resolves #16007 

This pullrequest changes

Colinearity test is now correctly performed on all 3 coordinates rather than just on x and y
```
 - [PR#15889](https://github.com/opencv/opencv/pull/15889): Made buildImagePyramid free function

   __Description__:<br/>
```
resolves https://github.com/opencv/opencv_contrib/issues/2324

This pullrequest changes

This PR makes changes the way, optical flow is computed on CUDA supporting devices. Refer, https://github.com/opencv/opencv_contrib/pull/2330#issuecomment-550396447
 Please describe what your pullrequest is changing 


opencv_contrib=

force_builders_only=Custom
buildworker:Custom=linux-4
build_image:Custom=ubuntu-cuda:18.04


```
 - [PR#15765](https://github.com/opencv/opencv/pull/15765): Use argument value for 'mat' in call to format for vector_mat and vector_mat_template

   __Description__:<br/>
```
The hard-coded string value "Mat" was used in the two format strings for vector_mat and vector_mat_template, preventing UMat arguments to functions that have these types from working correctly. as noted in #12231.

resolves #12231


```
 - [PR#13869](https://github.com/opencv/opencv/pull/13869): LineVirtualIterator

   __Description__:<br/>
```
Proposal of LineVirtualIterator, an alternative to "LineIterator not attached to any mat".
This is basically the same implementation, replacing the address difference by a single "offset" variable. elemsize becomes irrelevant and considered to be 1. "step" is thus equal to size.width since no stride is expected.

related to #13843
```
