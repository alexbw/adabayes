# adabayes

### To do:
* [x] Find candidate last layer features (DeCAF, Overfeat)
* [x] Find AlexNet code (5 convolutional layers with max-pooling, then three fully connected layers)
* [X] [Find download script for MNIST dataset](https://github.com/torch/demos/blob/master/train-a-digit-classifier/dataset-mnist.lua#L4)
* [X] [Find download script for CIFAR10 dataset](https://github.com/torch/demos/blob/1bfcb778dd3e237e5716a2c7001e3535cb17064c/train-on-cifar/train-on-cifar.lua#L140-L220)
* [x] Fork torch-dist repo
* [x] Update torch-dist repo for OS X 10.10 install
* [x] Add new required submodules to distro (nnx, iTorch, ccn2, cunnx, cudnn, sdl2, cutorch)
* [x] Figure out model serialization and loading
    * Built-in model serialization. [Loading](https://github.com/facebook/fblualib/blob/master/fblualib/thrift/README.md) and [saving](https://github.com/torch/demos/blob/1bfcb778dd3e237e5716a2c7001e3535cb17064c/train-on-cifar/train-on-cifar.lua#L372).
    * There is also facebook's [Thrift library](https://github.com/facebook/fblualib/blob/master/fblualib/thrift/README.md), which I haven't seen many examples for.
* [ ] Get the data out of the `DataSource` models that we're using
* [ ] Train and Whetlab a net on MNIST (to get the whole workflow going)
* [ ] Train and Whetlab a net on CIFAR10
* [ ] Train and Whetlab a net on STL10
* [ ] Build dumb ensemble on CIFAR10
* [ ] Build dumb ensemble on STL10
* [ ] Grok boosting criterion
* [ ] Whetlab a net with progressive ensembling on CIFAR10
* [ ] Whetlab a net with progressive ensembling on STL10
* [ ] Whetlab a net with progressive ensembling on the last-layer features of ImageNet
* [ ] Whetlab a net with progressive ensembling and tuned class weights on CIFAR10
* [ ] Whetlab a net with progressive ensembling and tuned class weights on STL10
* [ ] Extract last-layer ImageNet features
* [ ] Host last-layer ImageNet features
* [ ] Build download script for last-layer ImageNet features
* [ ] Train and Whetlab a net on last-layer features on ImageNet
* [ ] Build a dumb ensemble on ImageNet
* [ ] Whetlab a net with progressive ensembling and tuned class weights on the last-layer features of ImageNet


### Collecting some resources

AlexNet:
https://github.com/soumith/convnet-benchmarks/blob/master/torch7/imagenet_winners/alexnet.lua

I think this is NiN:
https://github.com/soumith/convnet-benchmarks/blob/master/torch7/imagenet_winners/googlenet.lua

OverFeat:
https://github.com/facebook/fbcunn/blob/master/examples/imagenet/models/overfeat_cunn.lua

Multiclass criterion:
https://github.com/torch/nn/blob/master/doc/criterion.md#classnllcriterion

Some other interesting nets:
https://github.com/culurciello/profiling

Bunch of demos, not all nets:
https://github.com/torch/demos

Overfeat features:
http://cilvr.nyu.edu/doku.php?id=software:overfeat:start

Decaf ImageNet submission:
https://github.com/UCB-ICSI-Vision-Group/decaf-release/wiki/imagenet
