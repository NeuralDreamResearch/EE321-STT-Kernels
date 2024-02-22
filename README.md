# EE321-STT-Kernels
Speech to Text kernel module

## Model Architecture
<pre>
 model xcorr_out_10
 Layer (type)                Output Shape              Param #   
=================================================================
 input (InputLayer)        [(None, 16890)]           0         
                                                                 
 dense (Dense)             (None, 10)                168910    
                                                                 
=================================================================
Total params: 168910 (659.80 KB)
Trainable params: 168910 (659.80 KB)
Non-trainable params: 0 (0.00 Byte)
_________________________________________________________________

 model_xcorr_out_2
 _________________________________________________________________
 Layer (type)                Output Shape              Param #   
=================================================================
 input (InputLayer)        [(None, 16890)]           0         
                                                                 
 dense (Dense)             (None, 1)                 16891     (--activation=sigmod)
                                                                 
=================================================================
Total params: 16891 (65.98 KB)
Trainable params: 16891 (65.98 KB)
Non-trainable params: 0 (0.00 Byte)
_________________________________________________________________
</pre>
