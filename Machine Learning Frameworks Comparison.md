# Machine Learning Frameworks Comparison

When taking the deep-dive into Machine Learning (ML), choosing a framework can be daunting. You've probably heard the many names/acronyms that make-up the constellation of frameworks, toolkits, libraries, data sets, applications etc. but may be curious about how they differ, where they fall short and which ones are worth investing in. Since the field and surrounding technologies are relatively new, the most common concern amongst new users is understanding which of these frameworks has the most momentum. This article summarizes their major differences and attempts to contextualize them within a broader landscape.

[![TensorFlow](https://blog.paperspace.com/content/images/2016/12/tensorflow.png)](https://www.tensorflow.org/)

TensorFlow was developed by the Google Brain Team for conducting research in machine learning and deep neural networks. Google recently moved away from Torch to TensorFlow which was a blow to other frameworks -- Torch and Theano in particular. Many describe TensorFlow as a more modern version of Theano after many important lessons about this new field/technology were learned over the years.

TensorFlow is relatively painless to setup and offers tutorials aimed at beginners that cover the theoretical underpinnings and practical application of neural networks. TensorFlow is slower than Theano and Torch but this is currently being addressed head on by Google and the open source community. TensorBoard is TensorFlow's visualization module which provides an intuitive view of your computation pipeline. Keras, a deep-learning library, was recently ported to run on TensorFlow which means any model written in Keras can now run on TensorFlow. Finally, it's worth mentioning that TensorFlow can run on a wide variety of hardware.

 * GPU acceleration: Yes 
 * Languages/interfaces: Python, Numpy, C++
 * Platform: Cross platform
 * Maintainer: [Google](https://www.tensorflow.org/)

![Theano](https://blog.paperspace.com/content/images/2016/12/theano-1.png)

Theano originated in 2007 at the University of Montreal at the widely renowned Institute for Learning Algorithms. Theano is powerful, extremely fast and flexible but is generally regarded as a low-level framework (eg error messages are known to be especially cryptic/unhelpful). As such, raw Theano is more of a research platform and ecosystem than a deep learning library. It is often used as an underlying platform for higher-level abstraction libraries that provide simple API wrappers into Theano. Some of the more popular libraries include Keras, Lasagne and Blocks. One of the downsides of Theano is that multi-GPU support still requires a workaround.

 * GPU acceleration: Yes
 * Languages/interfaces: Python, Numpy
 * Platform: Linux, Mac OS X and Windows
 * Maintainer: MILA lab at University of Montreal

![Torch](https://blog.paperspace.com/content/images/2016/12/torch-1.png)

Of all the common frameworks, Torch is probably the easiest to get up and running, especially if you are using Ubuntu. Originally developed at NYU in 2002, Torch is widely used by large tech companies like Facebook and Twitter and is also backed by NVIDIA. Torch is written in the scripting language called Lua which is easy to read but not nearly as common as languages like Python. Helpful error messages, a plethora of sample code/tutorials and the simplicity of Lua make Torch a great place to start.

 * GPU acceleration: Yes
 * Languages/interfaces: Lua
 * Platform: Linux, Android, Mac OS X, iOS and Windows
 * Maintainer: Ronan, Clément, Koray and Soumith

![Caffe](https://blog.paperspace.com/content/images/2016/12/caffe-1.png)

Caffe was developed for image classification/machine-vision leveraging Convolutional Neural Networks (CNNs). Caffe is perhaps best known for Model Zoo, a set of pre-trained models which you can use without writing any code.

Caffe is targeted towards those building applications while Torch and Theano are tailored for research. Caffe is not intended for non-computer vision deep-learning applications such as text, sound or time series data. Caffe can run on a variety of hardware and switching between CPU and GPU is set with a single flag. Caffe is slower than Theano and Torch.

 * GPU acceleration: Yes
 * Languages/interfaces: C, C++, Python, MATLAB, CLI
 * Platform: Ubuntu, Mac OS X, experimental Windows support
 * Maintainer: BVLC

![CNTK](https://blog.paperspace.com/content/images/2016/12/cntk.png)

Microsoft Cognitive Toolkit, also known as CNTK, is Microsoft’s open-source deep-learning framework. CNTK is better known in the speech community than in the general deep learning community though CNTK can be used for image and text training as well. CNTK supports a wide variety of algorithms like Feed Forward, CNN, RNN, LSTM, and Sequence-to-Sequence. It runs on many different hardware types including multiple GPUs.

 * GPU acceleration: Yes
 * Languages/interfaces: Python, C++, C# and CLI
 * Platform: Windows, Linux
 * Maintainer: Microsoft Research

Additional Frameworks

There are several other deep learning frameworks, including 
[MXnet](https://github.com/dmlc/mxnet), 
[Chainer](http://chainer.org/), 
[BidMach](https://github.com/BIDData/BIDMach), 
[Brainstorm](https://github.com/IDSIA/brainstorm), 
[Kaldi](https://github.com/kaldi-asr/kaldi), 
[MatConvNet](http://www.vlfeat.org/matconvnet/), 
[MaxDNN](https://github.com/eBay/maxDNN), 
[Deeplearning4j](http://deeplearning4j.org/), 
[Keras](http://keras.io/), 
[Lasagne](https://github.com/Lasagne/Lasagne), 
[Leaf](https://github.com/autumnai/leaf), 
and others.

A comparison of GitHub activity: 
![comparison](https://blog.paperspace.com/content/images/2016/12/1-VRihskMG4cTA8g60EuSWuw.png)
