**Deep learning models** often require high amount of computation power in order to train. This requirement is often met via parallel-processing the execution of these model and thus reducing the training time by several orders of magnitude. Due to this benefit, researches have shifted from CPU based processing to a more GPU based approach (like the [NVIDIA Tesla](https://www.nvidia.com/en-us/data-center/tesla-k80/)) when training their models. However, these GPUs and GPU clusters are often quite expensive and thus inaccessible to most.  

<img src="http://cms.ipressroom.com.s3.amazonaws.com/219/files/201410/546e36f5fe058b665800ba50_NVIDIA_Tesla_K80_Dual-GPU_Accelerator_3qtr/NVIDIA_Tesla_K80_Dual-GPU_Accelerator_3qtr_16bd47ef-d58a-47ee-8c39-b71702c88f7c-prv.jpg" style="display: block ; margin: 0 auto;" />


Google has recently started its [Colaboratory Project](https://colab.research.google.com/) that is essentially a [Jupyter notebook](http://jupyter.org/) environment that requires no setup to use and runs entirely in the cloud. It provides you free access to [NVIDIA TESLA K80 GPU](https://www.nvidia.com/en-us/data-center/tesla-k80/) clusters.

  -   You have the option to use either no Hardware Acceleration or you can use a **GPU Hardware Accelerator**, which then connects you to a runtime (provided that GPUs are available). 

- Colab also has several popular ML and Deep Learning** libraries pre-installed** and is essentially a plug and play methodology.  

- It also** bypasses some of the challenges** and nuances we face when setting up CUDA for a native GPU (which is a decent saving grace). 

Personally I would say that one of the biggest downsides of Colab is the **availability of GPU hardware on the cloud**.

Although powerful, the GPUs are shared between Virtual Machines and hence at many times you would find that GPUs are unavailable. 

Another issue that may creep up is that you have to** upload your datasets** to the cloud which is quite cumbersome.

*Nevertheless, Colab gives you an extreme amount of capability free of cost and it is definitely worth a shot.*


**You can try Colab at:** https://colab.research.google.com/

**Learning Resources on Using Google Colab** 

[1]  [3 Essential Google Colaboratory Tips & Tricks](https://www.kdnuggets.com/2018/02/essential-google-colaboratory-tips-tricks.html)


[2] [Deep Learning Development with Google Colab, TensorFlow, Keras & PyTorch](https://www.kdnuggets.com/2018/02/google-colab-free-gpu-tutorial-tensorflow-keras-pytorch.html)
