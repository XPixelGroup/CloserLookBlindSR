# CloserLookBlindSR
### Paper accepted by CVPR Workshop, NTIRE 2022
[Paper](https://arxiv.org/pdf/2205.04910.pdf) | [Supplementary file](https://openaccess.thecvf.com/content/CVPR2022W/NTIRE/supplemental/Zhang_A_Closer_Look_CVPRW_2022_supplemental.pdf)

### A Closer Look at Blind Super-Resolution: Degradation Models, Baselines, and Performance Upper Bounds


 By [Wenlong Zhang](https://wenlongzhang0517.github.io/), [Guangyuan Shi](https://scholar.google.com/citations?user=fL_osukAAAAJ&hl=en), [Yihao Liu](http://xpixel.group/2010/03/29/yihaoliu.html), [Chao Dong](https://scholar.google.com.hk/citations?user=OSDCB0UAAAAJ&hl=en), [Xiao-Ming Wu](http://www4.comp.polyu.edu.hk/~csxmwu/)
 

<p align="center">
  <img height="330" src="./figure/method.png">
</p>

 
## Codes and models will be released soon.
The code is based on [BasicSR](https://github.com/XPixelGroup/BasicSR) and [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN). Thanks to [Xintao Wang](https://xinntao.github.io/).
## An example of the gate operation on adding blur

```python
 ############## add blur ################### 
 
 # self.opt['gate_blur_prob'] = 0.5
 
 if np.random.uniform() < self.opt['gate_blur_prob']:
     out = filter2D(self.gt, self.kernel1)
 else:
     out = self.gt
```


