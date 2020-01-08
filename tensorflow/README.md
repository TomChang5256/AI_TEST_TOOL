git clone https://github.com/tensorflow/benchmarks.git
cd benchmarks
git checkout cnn_tf_v1.13_compatible
cd scripts/tf_cnn_benchmarks
python tf_cnn_benchmarks.py --num_gpus=1 --batch_size=32 --model=resnet50 --variable_update=parameter_server
