# Attention

## GitHub Repositories

- [Element-Research/rnn/examples/recurrent-visual-attention.lua](https://github.com/Element-Research/rnn/blob/master/examples/recurrent-visual-attention.lua)

## Papers
#### To Read
- [Effective Approaches to Attention-based Neural Machine Translation](http://arxiv.org/abs/1508.04025)
- [Learning generative models with visual attention](http://arxiv.org/pdf/1502.03044v2.pdf)
- [Attention-Based Convolutional Neural Network for Machine Comprehension](http://arxiv.org/abs/1602.04341)
- [Multiple Object Recognition with Visual Attention](http://arxiv.org/abs/1412.7755)
- [Multi-Way, Multilingual Neural Machine Translation with a Shared Attention Mechanism](http://arxiv.org/abs/1601.01073)
- [Searching for objects driven by context](https://papers.nips.cc/paper/4717-searching-for-objects-driven-by-context.pdf)
- [Optimal Scanning for Faster Object Detection](http://www.cs.washington.edu/research/insects/CVPR2009/objdetrec/optimscan_objdetect.pdf)
- [A model of saliency-based visual attention for rapid scene analysis](http://www.lira.dist.unige.it/teaching/SINA_08-09/papers/itti98model.pdf)
- [Long Short-Term Memory](http://deeplearning.cs.cmu.edu/pdfs/Hochreiter97_lstm.pdf)
- [Eye movements in natural behavior](http://www.ncbi.nlm.nih.gov/pubmed/15808501)
- [Rich feature hierarchies for accurate object detection and semantic segmentation](http://arxiv.org/abs/1311.2524)
- [Cascade object detection with deformable part models.](https://www.cs.berkeley.edu/~rbg/papers/Cascade-Object-Detection-with-Deformable-Part-Models--Felzenszwalb-Girshick-McAllester.pdf)
- [Learning where to attend with deep architectures for image tracking.](http://arxiv.org/pdf/1109.3737.pdf)
- [I-POMDP: An infomax model of eye movement](http://ieeexplore.ieee.org/xpl/login.jsp?tp=&arnumber=4640819&url=http%3A%2F%2Fieeexplore.ieee.org%2Fxpls%2Fabs_all.jsp%3Farnumber%3D4640819)
- [Learning to combine foveal glimpses with a third-order Boltzmann machine](https://papers.nips.cc/paper/4089-learning-to-combine-foveal-glimpses-with-a-third-order-boltzmann-machine)
- [Action from Still Image Dataset and Inverse Optimal Control to Learn Task Specific Visual Scanpaths](http://papers.nips.cc/paper/5196-action-from-still-image-dataset-and-inverse-optimal-control-to-learn-task-specific-visual-scanpaths)
- [Contextual Guidance of Eye Movements and Attention in Real-World Scenes: The Role of Global Features in Object Search](http://cvcl.mit.edu/Papers/TorralbaOlivaPsychRev06.pdf)
- [The Dynamic Representation of Scenes](https://www.cs.ubc.ca/~rensink/publications/download/VisCog_00.02.pdf)
- [Evolving a Roving Eye for Go](http://nn.cs.utexas.edu/downloads/papers/stanley.gecco04.pdf)
- [Q-Learning of Sequential Attention for Visual Object Recognition from Informative Local Descriptors](https://pdfs.semanticscholar.org/e2b5/dca2c46232a232356ca9034e35bc5b559dad.pdf)


#### Currently Reading
- [State-of-the-Art in Visual Attention Modeling](http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=6180177&tag=1)
	- Reviews nearly 65 models, comparing advantages and shortcomings according to 13 criteria from behavioral & computational science
- [On Learning Where To Look](http://www.cs.toronto.edu/~ranzato/publications/ranzato_arxiv14.pdf)


#### Done
- [Recurrent Models of Visual Attention](https://papers.nips.cc/paper/5542-recurrent-models-of-visual-attention.pdf)
	- Attention model capable of extracting information from image/video by adaptively processing select areas at high resolution
	- Translation invariance, computation can be controlled independently of image size
	- Trained as a POMDP using REINFORCE
	-  Outperforms a convolutional neural network baseline on cluttered images, and on a dynamic visual control problem, where it learns to track a simple object without an explicit training signal for doing so
- [Testing Visual Attention in Dynamic Environments](http://arxiv.org/pdf/1510.08949.pdf)
	- Attention model with a different structure (2 LSTMs: "observer" and "controller")
	- Trained using stochastic variational inference with a learned proposal distribution
- [Show, Attend and Tell: Neural Image Caption Generation with Visual Attention](http://arxiv.org/pdf/1502.03044v2.pdf)
	- Two types of attention: "hard" and "soft"
		- "Soft": deterministic, trainable with gradient descent
		- "Hard": stochastic, trainable with maximization of approximate variational lower bound or REINFORCE
	- Advantage: can interpret "what"/"where" the model is "paying attention" to
	- Takes in feature vectors of lower level of convolutional neural net, outputs image caption

## Tutorials
- [Torch: Recurrent Model of Visual Attention](http://torch.ch/blog/2015/09/21/rmva.html)
