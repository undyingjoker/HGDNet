<div align="center">
  <h1 align="center">Hybrid Gaussian Deformation for Efficient
Remote Sensing Object Detection</h1>
  <div align="center">
        <div class="is-size-4 publication-authors">
              <span class="author-block"> <a href="https://ieeexplore.ieee.org/author/37086125479" target="_blank">Wenda Zhao</a>, </span>
              <span class="author-block"> <a href="https://github.com/undyingjoker" target="_blank">Xiao Zhang</a>, </span>
              <span class="author-block"><a href="https://ieeexplore.ieee.org/author/37089921660" target="_blank">Haipeng Wang</a>, </span>
              <span class="author-block"><a href="https://scholar.google.com/citations?hl=en&user=D3nE0agAAAAJ" target="_blank">Huchuan Lu</a>, </span>
        </div>
        <div class="is-size-4 publication-authors">
        </div>
    </div>
    <a style="font-size: 24px;">📖 IEEE Transactions on Pattern Analysis and Machine Intelligence 2025</a>
</div>
<div>
# Abstract
Large-scale high-resolution remote sensing images (LSHR) are increasingly adopted for object detection, since they capture finer details. However, LSHR imposes a substantial computational cost. Existing methods explore lightweight backbones and advanced oriented bounding box regression mechanisms. Nevertheless, they still rely on high-resolution inputs to maintain detection accuracy. We observe that LSHR comprise extensive background areas that can be compressed to reduce unnecessary computation, while object regions contain details that can be reserved to improve detection accuracy. Thus, we propose a hybrid Gaussian deformation module that dynamically adjusts the sampling density at each location based on its relevance to the detection task, i.e., high-density sampling preserves more object regions  and better retains detailed features, while low-density sampling diminishes the background proportion. Further, we introduce a bilateral deform-uniform detection framework to exploit the potential of the deformed sampled low-resolution images and original high-resolution images. Specifically, a deformed deep backbone takes the deformed sampled images as inputs to produce high-level semantic information,
and a uniform shallow backbone takes the original high-resolution images as inputs to generate precise spatial location information. Moreover, we incorporate a deformation-aware feature registration module that calibrates the spatial information of deformed features, preventing regression degenerate solutions while maintaining feature activation. Subsequently, we introduce a feature relationship interaction fusion module to balance the contributions of features from both deformed and uniform backbones. Comprehensive experiments on three challenging datasets show that our method achieves superior performance compared with the  state-of-the-art methods.
    <img src="docs\fig3.jpg?_t=202506181741" alt="HGD Module" width="60%">
</div>


<div align="left">
<h3>Comparison of various RL methods</h2>
<img src="docs\FPS.svg?_t=202506181400" alt="FPS1" width="50%">
</div>
<div align="right">
<h3>Comparison of various RL methods</h2>
<img src="docs/FPS2.svg?_t=202505061400" alt="FPS2" width="50%">
</div>
<div align="center">
<h3>Comparison of various RL methods</h2>
<img src="docs\fig8.jpg?_t=202505061400" alt="Results" width="100%">
</div>

------

## Code and Checkpoints

The code and checkpoint will be released soon.
