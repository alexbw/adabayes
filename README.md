# adabayes

### To do:
* [x] Find candidate last layer features (DeCAF, Overfeat)
* [x] Find AlexNet code (5 convolutional layers with max-pooling, then three fully connected layers)
* [ ] Extract last-layer ImageNet features
* [ ] Extract last-layer ImageNet features
* [ ] Host last-layer ImageNet features
* [ ] Build download script for last-layer ImageNet features
* [ ] Build download script for MNIST dataset
* [ ] Build download script for CIFAR10 dataset
* [ ] Build download script for STL10 dataset
* [ ] Grok boosting criterion
* [ ] Fork torch-dist repo
* [ ] Update torch-dist repo for OS X 10.10 install
* [ ] Add new required submodules to distro (nnx, iTorch, ccn2, cunnx, cudnn, sdl2, cutorch)
* [ ] Figure out model serialization and loading
* [ ] Train and Whetlab a net on MNIST (to get the whole workflow going)
* [ ] Train and Whetlab a net on CIFAR10
* [ ] Train and Whetlab a net on STL10
* [ ] Train and Whetlab a net on last-layer features on ImageNet
* [ ] Build dumb ensemble on CIFAR10
* [ ] Build dumb ensemble on STL10
* [ ] Build a dumb ensemble on ImageNet
* [ ] Whetlab a net with progressive ensembling on CIFAR10
* [ ] Whetlab a net with progressive ensembling on STL10
* [ ] Whetlab a net with progressive ensembling on the last-layer features of ImageNet
* [ ] Whetlab a net with progressive ensembling and tuned class weights on CIFAR10
* [ ] Whetlab a net with progressive ensembling and tuned class weights on STL10
* [ ] Whetlab a net with progressive ensembling and tuned class weights on the last-layer features of ImageNet


### Collecting some resources

AlexNet:
https://github.com/soumith/convnet-benchmarks/blob/master/torch7/imagenet_winners/alexnet.lua

I think this is NiN:
https://github.com/soumith/convnet-benchmarks/blob/master/torch7/imagenet_winners/googlenet.lua

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
