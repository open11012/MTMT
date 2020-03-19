# A Multi-task Mean Teacher for Semi-supervised Shadow Detection

by Zhihao Chen, Lei Zhu, Liang Wan, Song Wang, Wei Feng, and Pheng-Ann Heng [[paper link]()]

The implementation is comming soon.
%This implementation is written by Zhihao Chen at the Tianjin University.

***

## Citation
@inproceedings{chen20MTMT,   
&nbsp;&nbsp;&nbsp;&nbsp;  author = {Chen, Zhihao and Zhu, Lei and Wan, Liang and Wang, Song and Feng, Wei and Heng, Pheng-Ann},    
&nbsp;&nbsp;&nbsp;&nbsp;  title = {A Multi-task Mean Teacher for Semi-supervised Shadow Detection},    
&nbsp;&nbsp;&nbsp;&nbsp;  booktitle = {CVPR},    
&nbsp;&nbsp;&nbsp;&nbsp;  year  = {2020}    
}

## Shadow detection results at test datasets
The results of shadow detection(w & w/o crf) on three datasets (SBU, UCF, ISTD) can be found 
at [Google Drive]() or [BaiduNetdisk]().

## Trained Model
You can download the trained model which is reported in our paper at 
[Google Drive]() or [BaiduNetdisk]().

## Requirement
* Python 3.6
* PyTorch 1.3.1(After 0.4.0 would be ok)
* torchvision
* numpy
* tqdm
* PIL
* pydensecrf ([here](https://github.com/Andrew-Qibin/dss_crf) to install)

## Training
1. Set ...
2. Set ...
3. Run by ```python train.py```

The pretrained ResNeXt model is ported from the [official](https://github.com/facebookresearch/ResNeXt) torch version,
using the [convertor](https://github.com/clcarwin/convert_torch_to_pytorch) provided by clcarwin. 
You can directly [download](https://drive.google.com/open?id=1dnH-IHwmu9xFPlyndqI6MfF4LvH6JKNQ) the pretrained model ported by me.

## Testing
1. Set ...
2. Put ...
2. Run by ```python infer.py```

## Useful links
