# CloserLookBlindSR
### [Paper](https://arxiv.org/pdf/2205.04910.pdf) accepted by CVPR Workshop, NTIRE 2022

### A Closer Look at Blind Super-Resolution: Degradation Models, Baselines, and Performance Upper Bounds


 By [Wenlong Zhang](https://wenlongzhang0517.github.io/), Guangyuan Shi, [Yihao Liu](http://xpixel.group/2010/03/29/yihaoliu.html), [Chao Dong](https://scholar.google.com.hk/citations?user=OSDCB0UAAAAJ&hl=en), [Xiao-Ming Wu](http://www4.comp.polyu.edu.hk/~csxmwu/)
 
## Codes and models will be released soon.

## An example of the gate operation on adding blur

```python
 ############## add blur ################### 
 
 # self.opt['gate_blur_prob'] = 0.5
 
 if np.random.uniform() < self.opt['gate_blur_prob']:
     out = filter2D(self.gt, self.kernel1)
 else:
     out = self.gt
```


