# MCAT
Multi-level context-adaptive correlation tracking

https://authors.elsevier.com/c/1XyFn77nKSbrh

## Abstract
The discriminative correlation filter (DCF) has shown impressive performance in visual tracking. Context has two functions in DCF: addressing the disturbance in target locating, and supplying cues for locating the target within the context. To improve the context utilization, we introduce a multi-level context- adaptive tracking (MCAT) approach for DCF tracking. Firstly, a multi-level context representation—called a context pyramid—is proposed to exploit the relationship between the target and its context for better visual tracking. Secondly, for each level of the context pyramid, we control the effect of context in DCF learning and tracking using context-adaptive spatial windows. An accurate target model can thereby be learned, even when the background clutter is severe. Moreover, the target can be more easily tracked when the background is weakened by the spatial window. Thirdly, a robust prediction of the target posi- tion is obtained with the multi-level structure of the context pyramid. Experimental results showed that, with conventional hand-crafted features, our tracker provided state-of-the-art performance on OTB100 comparable to those of deep-learning-based trackers.

## OTB100 results

![OTB100 rsults](https://github.com/chantcalf/MCAT/blob/master/MCAT.png)

## Cite
@article{MCAT,

  author    = {Peng Liu and 
               Chang Liu and           
               Wei Zhao and             
               Xianglong Tang},
                
  title     = {Multi-level context-adaptive correlation tracking},
  
  journal   = {Pattern Recognition},
  
  volume    = {87},
  
  pages     = {216-225},
  
  year      = {2019},
  
  url       = {https://doi.org/10.1016/j.patcog.2018.10.013},
  
  doi       = {10.1016/j.patcog.2018.10.013},
  
}

