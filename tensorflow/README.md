# Tensorflow Test
Here you can reference the Tensorflow benchmark to test your environment

## Getting Started
1. Git Tensorflow benchmark project
```
git clone https://github.com/tensorflow/benchmarks.git
```
2. Check out with cnn_tf_v1.13_compatible
```
cd benchmarks
git checkout cnn_tf_v1.13_compatible
```
3. Test environment with tf_cnn_benchmarks.py
```
cd scripts/tf_cnn_benchmarks
python tf_cnn_benchmarks.py --num_gpus=1 --batch_size=32 --model=resnet50 --variable_update=parameter_server
```
