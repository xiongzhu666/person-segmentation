# person-segmentation

I traind a small person segmentation model by u2netp. the size of the fp16 model is only about 2Mb and it is friendly deployment for Android or ARM platform. the repo is just for demo and the precision is not very good. 

**u2net has higher precision compared with u2netp but its size is too large. it is not suitable for ARM or Android.**

I write a simple code interenced by ncnn or onnxruntime

c++ dependency： opencv ncnn

python dependcy：onnxruntime

![result](https://github.com/xiongzhu666/person-segmentation/blob/main/result.png)

