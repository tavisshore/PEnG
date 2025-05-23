# 🚧 Finalising Code

<div align="center">    
 
# 🌍🕺 PEnG: Pose-Enhanced Geo-Localisation 📡🗺️ 
<p align="middle">
 <a href="https://tavisshore.co.uk/">Tavis Shore</a>
 <a href="https://cvssp.org/Personal/OscarMendez/index.html">Oscar Mendez</a>
 <a href="https://personalpages.surrey.ac.uk/s.hadfield/biography.html">Simon Hadfield</a>
</p>
<p align="middle">
 <a href="https://www.surrey.ac.uk/centre-vision-speech-signal-processing">Centre for Vision, Speech, and Signal Processing (CVSSP)</a>
</p>
<p align="middle">
 <a>University of Surrey, Guildford, GU2 7XH, United Kingdom </a>
</p>

[![arxiv](https://img.shields.io/badge/cs.LG-2411.15742-b31b1b?style=flat&logo=arxiv&logoColor=red)](https://arxiv.org/abs/2411.15742)
[![Conference](http://img.shields.io/badge/RA--L-2025-4b44ce.svg)](https://www.ieee-ras.org/publications/ra-l)
[![Project Page](http://img.shields.io/badge/Project-Page-green)](https://tavisshore.co.uk/peng/)
[![License](https://img.shields.io/badge/license-MIT-blue)](tavisshore.co.uk/posts/PEnG)

[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/peng-pose-enhanced-geo-localisation/multi-view-geo-localisation-on-peng-90deg)](https://paperswithcode.com/sota/multi-view-geo-localisation-on-peng-90deg?p=peng-pose-enhanced-geo-localisation)


</div>
 
## 📓 Description 
Cross-view Geo-localisation is typically performed at a coarse granularity, because densely sampled satellite image patches overlap heavily. This heavy overlap would make disambiguating patches very challenging. However, by opting for sparsely sampled patches, prior work has placed an artificial upper bound on the localisation accuracy that is possible. Even a perfect oracle system cannot achieve accuracy greater than the average separation of the tiles. To solve this limitation, we propose combining cross-view geo-localisation and relative pose estimation to increase precision to a level practical for real-world application. We develop PEnG, a 2-stage system which first predicts the most likely edges from a city-scale graph representation upon which a query image lies. It then performs relative pose estimation within these edges to determine a precise position. PEnG presents the first technique to utilise both viewpoints available within CVGL datasets, referring to this as Multi-View Geo-Localisation (MVGL). This enhances accuracy to a sub-metre level, with some examples achieving centimetre level precision. Our proposed ensemble achieves state-of-the-art accuracy - with relative Top-5m retrieval improvements on previous works of 213%. Decreasing the median euclidean distance error by 96.90% from the previous best of 734m down to 22.77m, when evaluating with 90° horizontal FOV images.


### 🧬 City Graph Representation

<!--
<p align="middle">
   <img src="https://github.com/user-attachments/assets/1f34ccbd-92ac-4374-b7a1-98bad9342277" width="32%" />
   <img src="/img2.png" width="32%" /> 
   <img src="/img3.png" width="32%" />
</p>
-->


---
## 🧰 PEnG: Benchmarking

🚧 Under Construction

#### 🐍 Environment Setup
```

```

#### 🏭 Data Download 
```

```

#### Submodule Pretraining
```

```

#### PEnG Evaluation
```

```


## PEnG: Benchmark Results


## ✒️ Citation
```
@ARTICLE{10906427,
  author={Shore, Tavis and Mendez, Oscar and Hadfield, Simon},
  journal={IEEE Robotics and Automation Letters}, 
  title={PEnG: Pose-Enhanced Geo-Localisation}, 
  year={2025},
  volume={10},
  number={4},
  pages={3835-3842},
  doi={10.1109/LRA.2025.3546513}}

```
## 📗 Related Works
### 🍝 [SpaGBOL: Spatial-Graph-Based Orientated Localisation](https://github.com/tavisshore/SpaGBOL)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![arxiv](https://img.shields.io/badge/cs.LG-2409.15514-b31b1b?style=flat&logo=arxiv&logoColor=red)](https://arxiv.org/abs/2409.15514)
[![Conference](http://img.shields.io/badge/WACV-2025-4b44ce.svg)](https://wacv2025.thecvf.com/)
[![Project Page](http://img.shields.io/badge/Project-Page-green)](https://tavisshore.co.uk/spagbol/)
[![GitHub](https://img.shields.io/badge/GitHub-SpaGBOL-%23121011.svg?logo=github&logoColor=white)](https://github.com/tavisshore/spagbol)

### 🦜 [BEV-CV: Birds-Eye-View Transform for Cross-View Geo-Localisation](https://github.com/tavisshore/BEV-CV)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![arxiv](https://img.shields.io/badge/cs.LG-2312.15363-b31b1b?style=flat&logo=arxiv&logoColor=red)](https://arxiv.org/abs/2312.15363)
[![Conference](http://img.shields.io/badge/IROS-2024-4b44ce.svg)](https://wacv2025.thecvf.com/)
[![Project Page](http://img.shields.io/badge/Project-Page-green)](https://tavisshore.co.uk/bevcv/)
[![GitHub](https://img.shields.io/badge/GitHub-BEV--CV-%23121011.svg?logo=github&logoColor=white)](https://github.com/tavisshore/BEV-CV)
