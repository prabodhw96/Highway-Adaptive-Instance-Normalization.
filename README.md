# Local Image to Image Translation Via Pixel wise Highway Adaptive Instance Normalization

### The result of LOcal Mask based Image Translation (LOMIT)
##### (black, smile) => (blonde, non-smile)
<img src="https://user-images.githubusercontent.com/20943085/46212917-2b99fc00-c372-11e8-8da0-384b7ba7418c.png" width="90%"></img>

##### Prerequisite
* python3.6  
* Pytorch0.4.1
* matplotlib 2.2.2

##### To download the data:
>$ bash data_download.sh

##### Train
* Import run.py file from the jupyter notebook. (An example is example.ipynb)

##### Training Time
28 hours on GTX 1080 Ti (12 GB)

##### Test link will be released soon.

### Our model overview
<img src="https://user-images.githubusercontent.com/20943085/47040629-a57b1380-d1c1-11e8-9635-32d449db0227.png" width="90%"></img>

### The cosegmentation module
<img src="https://user-images.githubusercontent.com/20943085/46211908-aada0080-c36f-11e8-9b1a-7d8f683313e4.png" width="90%"></img>

### Comparing with the baseline(MUNIT,DRIT)
<img src="https://user-images.githubusercontent.com/20943085/47747758-6a520780-dccc-11e8-94bf-a20a7d3975cb.png" width="90%"></img>
