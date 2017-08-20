##Thoughts on project:

the basic convolution network does okay with the current params, with network structure
- conv2d (filter size 20, ksize=5, stride = 1)
- Maxpool (pool ksize=2, stride=2)
- conv2d (filter size 20, ksize=5, stride = 1)
- Maxpool (pool ksize=2, stride=2)
- flatten
- fully_connected (360 output)
- dropout
- fully_connected (100 output)
- output

but on testing it's only around 70% or so.
Would be interesting to see how it behaves by duplicating e.g. alexnet architecture...
