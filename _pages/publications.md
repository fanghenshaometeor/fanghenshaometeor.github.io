---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">Here lists a part of my publications on <b>trustworthy deep learning</b>. You can find a full collection of my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

<!-- {% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->

---

<div class="pub-tabs">

  <input type="radio" id="tab-journals" name="pub-tab" checked>
  <label class="pub-tab-label pub-tab--journals" for="tab-journals">Journal</label>

  <input type="radio" id="tab-conferences" name="pub-tab">
  <label class="pub-tab-label pub-tab--confs" for="tab-conferences">Conference</label>

  <input type="radio" id="tab-coauth" name="pub-tab">
  <label class="pub-tab-label pub-tab--coauth" for="tab-coauth">Co-authored</label>

  <!-- ===== Journals ===== -->
  <div id="content-journals" class="pub-tab-content" markdown="1">

**Kernel PCA for Out-of-Distribution Detection: Non-Linear Kernel Selection and Approximation**  
<span style="font-family:Comic Neue; font-size:1em;">**Kun FANG**, Qinghua TAO, Mingzhen HE, Kexin LV, Runze YANG, Haibo HU, Xiaolin HUANG, Jie YANG, Longbing CAO</span>  
<span style="font-family:Patrick Hand; font-size:1.1em;">IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2026.</span>  
<span style="font-size:0.85em;"><a href="https://github.com/fanghenshaometeor/ood-kernel-pca-ext" class="pub-link pub-link--code">Code</a> <a href="https://arxiv.org/abs/2505.15284" class="pub-link pub-link--arxiv">ArXiv</a> <a href="https://doi.org/10.1109/TPAMI.2026.3705778" class="pub-link pub-link--journal">Journal</a></span>

**Multi-head Ensemble of Smoothed Classifiers for Certified Robustness**  
<span style="font-family:Comic Neue; font-size:1em;">**Kun FANG**, Qinghua TAO, Yingwen WU, Tao LI, Xiaolin HUANG, Jie YANG</span>  
<span style="font-family:Patrick Hand; font-size:1.1em;">Neural Networks, 2025.</span>  
<span style="font-size:0.85em;"><a href="https://github.com/fanghenshaometeor/smoothed-multihead-ensemble" class="pub-link pub-link--code">Code</a> <a href="https://arxiv.org/abs/2211.10882" class="pub-link pub-link--arxiv">ArXiv</a> <a href="https://doi.org/10.1016/j.neunet.2025.107426" class="pub-link pub-link--journal">Journal</a></span>


**Revisiting Deep Ensemble for Out-of-Distribution Detection: A Loss Landscape Perspective**  
<span style="font-family:Comic Neue; font-size:1em;">**Kun FANG**, Qinghua TAO, Xiaolin HUANG, Jie YANG</span>  
<span style="font-family:Patrick Hand; font-size:1.1em;">International Journal of Computer Vision, 2024.</span>  
<span style="font-size:0.85em;"><a href="https://github.com/fanghenshaometeor/ood-mode-ensemble" class="pub-link pub-link--code">Code</a> <a href="https://arxiv.org/abs/2310.14227" class="pub-link pub-link--arxiv">ArXiv</a> <a href="https://doi.org/10.1007/s11263-024-02156-x" class="pub-link pub-link--journal">Journal</a></span>

**Towards Robust Neural Networks via Orthogonal Diversity**  
<span style="font-family:Comic Neue; font-size:1em;">**Kun FANG**, Qinghua TAO, Yingwen WU, Tao LI, Jia CAI, Feipeng CAI, Xiaolin HUANG, Jie YANG</span>  
<span style="font-family:Patrick Hand; font-size:1.1em;">Pattern Recognition, 2024.</span>  
<span style="font-size:0.85em;"><a href="https://github.com/fanghenshaometeor/DIversity-via-Orthogonality" class="pub-link pub-link--code">Code</a> <a href="https://arxiv.org/abs/2010.12190" class="pub-link pub-link--arxiv">ArXiv</a> <a href="https://doi.org/10.1016/j.patcog.2024.110281" class="pub-link pub-link--journal">Journal</a></span>


**End-to-end Kernel Learning via Generative Random Fourier Features**  
<span style="font-family:Comic Neue; font-size:1em;">**Kun FANG**, Fanghui LIU, Xiaolin HUANG, Jie YANG</span>  
<span style="font-family:Patrick Hand; font-size:1.1em;">Pattern Recognition, 2023.</span>  
<span style="font-size:0.85em;"><a href="https://github.com/fanghenshaometeor/GenerativeRFF" class="pub-link pub-link--code">Code</a> <a href="https://arxiv.org/abs/2009.04614" class="pub-link pub-link--arxiv">ArXiv</a> <a href="https://doi.org/10.1016/j.patcog.2022.109057" class="pub-link pub-link--journal">Journal</a></span>

  </div>

  <!-- ===== Conferences ===== -->
  <div id="content-conferences" class="pub-tab-content" markdown="1">

**Kernel PCA for Out-of-Distribution Detection**  
<span style="font-family:Comic Neue; font-size:1em;">**Kun FANG**, Qinghua TAO, Kexin LV, Mingzhen HE, Xiaolin HUANG, Jie YANG</span>  
<span style="font-family:Patrick Hand; font-size:1.1em;">Conference on Advances in Neural Information Processing Systems (NeurIPS), 2024.</span>  
<span style="font-size:0.85em;"><a href="https://github.com/fanghenshaometeor/ood-kernel-pca" class="pub-link pub-link--code">Code</a> <a href="https://arxiv.org/abs/2402.02949" class="pub-link pub-link--arxiv">ArXiv</a> <a href="https://papers.nips.cc/paper_files/paper/2024/hash/f2543511e5f4d4764857f9ad833a977d-Abstract-Conference.html" class="pub-link pub-link--conf">Conference</a></span>

  </div>

  <!-- ===== Co-authored ===== -->
  <div id="content-coauth" class="pub-tab-content" markdown="1">

**DIFT: Protecting Contrastive Learning against Data Poisoning Backdoor Attacks**  
<span style="font-family:Comic Neue; font-size:1em;">Jiang ZHU, Yulin JIN, Qingqing YE, Zhibiao GUO, **Kun FANG**, Ruochen DU, Yingnan ZHAO, Haibo HU</span>  
<span style="font-family:Patrick Hand; font-size:1.1em;">AAAI Conference on Artificial Intelligence (AAAI), 2026.</span>  
<span style="font-size:0.85em;"><a href="https://ojs.aaai.org/index.php/AAAI/article/view/37141" class="pub-link pub-link--conf">Conference</a></span>

**Adaptive Distillation on Hard Samples Benefits Consistency for Certified Robustness**  
<span style="font-family:Comic Neue; font-size:1em;">Jiawen LI, **Kun FANG**, Jie YANG</span>  
<span style="font-family:Patrick Hand; font-size:1.1em;">International Journal of Machine Learning and Cybernetics, 2025.</span>  
<span style="font-size:0.85em;"><a href="https://doi.org/10.1007/s13042-025-02568-2" class="pub-link pub-link--journal">Journal</a></span>

**Boosting Certified Robustness via An Expectation-based Similarity Regularization**  
<span style="font-family:Comic Neue; font-size:1em;">Jiawen LI, **Kun FANG**, Xiaolin HUANG, Jie YANG</span>  
<span style="font-family:Patrick Hand; font-size:1.1em;">Image and Vision Computing, 2024.</span>  
<span style="font-size:0.85em;"><a href="https://doi.org/10.1016/j.imavis.2024.105272" class="pub-link pub-link--journal">Journal</a></span>

**Improving Adversarial Robustness through A Curriculum-guided Reliable Distillation**  
<span style="font-family:Comic Neue; font-size:1em;">Jiawen LI, **Kun FANG**, Xiaolin HUANG, Jie YANG</span>  
<span style="font-family:Patrick Hand; font-size:1.1em;">Computers & Security, 2023.</span>  
<span style="font-size:0.85em;"><a href="https://github.com/kevinlee26/kevin_first" class="pub-link pub-link--code">Code</a> <a href="https://doi.org/10.1016/j.cose.2023.103411" class="pub-link pub-link--journal">Journal</a></span>

**Improving the Adversarial Robustness of Quantized Neural Networks via Exploiting the Feature Diversity**  
<span style="font-family:Comic Neue; font-size:1em;">Tianshu CHU, **Kun FANG**, Jie YANG, Xiaolin HUANG</span>  
<span style="font-family:Patrick Hand; font-size:1.1em;">Pattern Recognition Letters, 2023.</span>  
<span style="font-size:0.85em;"><a href="https://doi.org/10.1016/j.patrec.2023.10.024" class="pub-link pub-link--journal">Journal</a></span>

**Unifying Gradients to Improve Real-world Robustness for Deep Networks**  
<span style="font-family:Comic Neue; font-size:1em;">Yingwen WU, Sizhe CHEN, **Kun FANG**, Xiaolin HUANG</span>  
<span style="font-family:Patrick Hand; font-size:1.1em;">ACM Transactions on Intelligent Systems and Technology, 2023.</span>  
<span style="font-size:0.85em;"><a href="https://github.com/snowien/UniG-pytorch" class="pub-link pub-link--code">Code</a> <a href="https://arxiv.org/abs/2208.06228" class="pub-link pub-link--arxiv">ArXiv</a> <a href="https://dl.acm.org/doi/10.1145/3617895" class="pub-link pub-link--journal">Journal</a></span>

**Subspace Adversarial Learning**  
<span style="font-family:Comic Neue; font-size:1em;">Tao LI, Yingwen WU, Sizhe CHEN, **Kun FANG**, Xiaolin HUANG</span>  
<span style="font-family:Patrick Hand; font-size:1.1em;">IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2022.</span>  
<span style="font-size:0.85em;"><a href="https://github.com/nblt/sub-at" class="pub-link pub-link--code">Code</a> <a href="https://arxiv.org/abs/2111.12229" class="pub-link pub-link--arxiv">ArXiv</a> <a href="https://openaccess.thecvf.com/content/CVPR2022/html/Li_Subspace_Adversarial_Training_CVPR_2022_paper" class="pub-link pub-link--conf">Conference</a></span>

  </div>

</div>