## Setting a fronzen layer in transfer Learning in fastai
To freeze some layers in a model we can set .requeires_grad=False.
We can see if the layer is not trainable using model.summary().

https://github.com/ultralytics/yolov5/issues/1314
