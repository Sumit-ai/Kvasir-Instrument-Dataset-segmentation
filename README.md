
# Kvasir Instrument Segmentation Using UNet
`Author: Sumit Pandey (CGMH Taiwan) Dr. Arvind Keprate (Oslo Metropolitan University, Norway)`

Here is the kaggle notebook: https://www.kaggle.com/sumitai/segmentation-unet/notebook
### Libraries:
-----------------------------------------------------------------
``` python 
pip install gradio
pip install tensorflow 
pip install keras 
pip install matplotlib 
pip install pandas # numpy will be installed autimaticallly 


import numpy 
import tensorflow 
import keras
import matplotlib.pyplot as plt
import glob 
import keras 

```

### Models used: 
In this work I used UNet segmentation. 

### Results:
``` python
Train DSC: 0.831
Validation DSC: 0.80
Test DSC: 0.767
```
##### here are the prediction results on testing dataset. 

<img align="center" src="result.png" width="500" />

**Note:** Please check the .csv files attached in `DSC_train_test_valid` folder to check the individual DSC of every image in training, testing and validation folder.  
