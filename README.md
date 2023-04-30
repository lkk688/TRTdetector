# TRTdetector
Build TRTdetector3D
```bash
$ mkdir build && cd build
lkk@Alienware-LKKi7G8:~/Developer/TRTdetector/TRTdetector3D/build$ cmake -DCMAKE_PREFIX_PATH=/home/lkk/Developer/libtorch  ..
$ make -j4
lkk@Alienware-LKKi7G8:~/Developer/TRTdetector/TRTdetector3D/build$ ./demo
```

Build TRTsamples
```bash
(base) lkk@Alienware-LKKi7G8:~/Developer/TRTdetector/TRTsamples/build$ cmake -DCMAKE_PREFIX_PATH=/home/lkk/Developer/libtorch  ..
(base) lkk@Alienware-LKKi7G8:~/Developer/TRTdetector/TRTsamples/build$ make -j4
(base) lkk@Alienware-LKKi7G8:~/Developer/TRTdetector/TRTsamples/build$ ./sampleOnnxMNIST/out/sample_onnx_mnist -d /home/lkk/Developer/TensorRT/build/mymodels
(base) lkk@Alienware-LKKi7G8:~/Developer/TRTdetector/TRTsamples/build$ ./sampleOnnxMNIST/out/sample_onnx_mnist -d /home/lkk/Developer/TensorRT-8.6.0.12/data/mnist/
```
