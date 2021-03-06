# Correlation Filter Trackers notes

The notes are ordered by year ascendant. Tracker listed in each year are in no particular order

Conferences names:
* __CVPR__ = IEEE Conference on Computer Vision and Pattern Recognition
* __ECCV__ = European Conference on Computer Vision
* __ICCV__ = International Conference on Computer Vision
* __IJCV__ = International Journal of Computer Vision
* __TPAMI__ = IEEE Transactions on Pattern Analysis and Machine Intelligence

## 2018

* _MKCFup_
	* __Paper:__ ["High-speed Tracking with Multi-kernel Correlation Filters"](https://arxiv.org/pdf/1806.06418.pdf)
	* __Presented in:__ [arXiv](https://arxiv.org/abs/1806.06418)
	* __Major Contribution/s:__ Introduce the multi-kernel learning (MKL) into KCF in a different way compared to the MKCF tracker, achieving better performance with not much drop in fps.
	* __Code:__ - 

* _LCT Tracker v2_
	* __Paper:__ ["Adaptive Correlation Filters with Long-Term and Short-Term Memory for Object Tracking"](https://drive.google.com/open?id=0B8-i_hZvGyZNb2I2aVVxbmpWZmM)
	* __Presented in:__ ICJV
	* __Major Contribution/s:__ Learn multiple adaptive correlation filters with both long-term memory and short-term memory of target appearance for robust object tracking.
	* __Code:__ [Matlab](https://github.com/chaoma99/lct-tracker) 

## 2017

* _ACFN_
	* __Paper:__ ["Attentional Correlation Filter Network for Adaptive Visual Tracking"](https://drive.google.com/open?id=0B0ZkG8zaRQoLUHdlTGNtUWFjd1E)
	* __Presented in:__ CVPR
	* __Major Contribution/s:__ Propose a new framework in which an attention network that selects the best module (a set of Correlation Filters) to track the object in a certain frame.
	* __Code:__ [Matlab](https://github.com/jongwon20000/ACFN) 
	
* _CFNet_ ([Project Page](https://www.robots.ox.ac.uk/~luca/cfnet.html))
	* __Paper:__ ["End-to-end representation learning for Correlation Filter based tracking"](http://openaccess.thecvf.com/content_cvpr_2017/html/Valmadre_End-To-End_Representation_Learning_CVPR_2017_paper.html)
	* __Presented in:__ CVPR
	* __Major Contribution/s:__ First work to propose training the Correlation Filter jointly with a Siamese Network in an end-to-end fashion.
	* __Code:__ [Matlab](https://github.com/bertinetto/cfnet)
	
* _DCFNet_
	* __Paper:__ ["DCFNet: Discriminant Correlation Filters Network for Visual Tracking"](https://arxiv.org/pdf/1704.04057.pdf)
	* __Presented in:__ arXiv
	* __Major Contribution/s:__ Another work to propose training the Correlation Filter jointly with a Siamese Network. Different from CFNet in network architecture and place of the Correlation Filter in the Tracker architecture.
	* __Code:__ [Matlab](https://github.com/foolwood/DCFNet) | [Python (PyTorch)](https://github.com/foolwood/DCFNet_pytorch)

## 2015

* _MKCF_ 
	* __Paper:__ ["Multi-kernel Correlation Filter for Visual Tracking"](https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Tang_Multi-Kernel_Correlation_Filter_ICCV_2015_paper.pdf)
	* __Presented in:__ ICCV
	* __Major Contribution/s:__ Introduce multi-kernel to correlation filter based trackers.
	* __Code:__ [.exe file](http://vision.ia.ac.cn/Faculty/mtang/MKCF_exe.rar) 

* _KCF_ ([Project Page](http://www.robots.ox.ac.uk/~joao/circulant/))
	* __Paper:__ ["High-Speed Tracking with Kernelized Correlation Filters"](http://www.robots.ox.ac.uk/~joao/publications/henriques_tpami2015.pdf)
	* __Presented in:__ TPAMI
	* __Major Contribution/s:__ Derive a new Kernelized Correlation Filter (KCF) and propose a fast multi-channel extension of
linear correlation filters, via a linear kernel, called by authors Dual Correlation Filter (DCF).
	* __Code:__ [Matlab](http://www.robots.ox.ac.uk/~joao/circulant/tracker_release2.zip) | More codes in Project page

* _LCT Tracker v1_
	* __Paper:__ ["Long-Term Correlation Tracking"](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Ma_Long-Term_Correlation_Tracking_2015_CVPR_paper.pdf)
	* __Presented in:__ CVPR
	* __Major Contribution/s:__ Introduced online random fern classifier as re-detection component for long-term tracking.
	* __Code:__ [Matlab](https://github.com/chaoma99/lct-tracker) 

* _CF2_ ([Project Page](https://sites.google.com/site/chaoma99/iccv15-tracking))
	* __Paper:__ ["Hierarchical Convolutional Features for Visual Tracking"](https://drive.google.com/file/d/0B8-i_hZvGyZNZS1YV2tvSDVTeE0/view?usp=sharing)
	* __Presented in:__ ICCV
	* __Major Contribution/s:__ Learn a Correlation Filter on each Convolutional Layer of a pre-trained network, taking advantage of the different information of features from different layers.
	* __Code:__ [Matlab](https://github.com/jbhuang0604/CF2) 

## 2012

* _CSK_ ([Project Page](http://www.robots.ox.ac.uk/~joao/circulant/))
	* __Paper:__ ["Exploiting the Circulant Structure of Tracking-by-detection with Kernels"](http://www.robots.ox.ac.uk/~joao/publications/henriques_eccv2012.pdf)
	* __Presented in:__ ECCV
	* __Major Contribution/s:__ Introduced Ridge Regression problem with circulant matrix to apply kernel methods.
	* __Code:__ [Matlab](http://www.robots.ox.ac.uk/~joao/circulant/tracker_release.zip) | More codes in Project page

## 2010

* _MOSSE (Minimum Output Sum of Squared Errors)_
	* __Paper:__ ["Visual Object Tracking using Adaptive Correlation Filters"](http://www.cs.colostate.edu/~vision/publications/bolme_cvpr10.pdf)
	* __Presented in:__ CVPR
	* __Major Contribution/s:__ Pioneering work in introducing Correlation Filters for visual tracking. Filter is single channel.
	* __Code:__ -

