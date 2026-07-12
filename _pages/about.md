---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<div id="bibtex-modal" class="bibtex-modal">
  <div class="bibtex-modal-content">
    <div class="bibtex-modal-header">
      <h3 id="bibtex-title">BibTeX Citation</h3>
      <button class="bibtex-close" onclick="closeBibTeX()">&times;</button>
    </div>
    <pre id="bibtex-content" class="bibtex-content"></pre>
    <div class="bibtex-actions">
      <button class="bibtex-copy-btn" onclick="copyBibTeX()">Copy</button>
    </div>
  </div>
</div>

<span class='anchor' id='about-me'></span>
I'm now a 2nd-year PhD student at <a href='https://en.sjtu.edu.cn/'>Shanghai Jiao Tong University</a>, <a href='https://www.sii.edu.cn/'>Shanghai Innovation Institute</a>, advised by Prof. <a href='https://scholar.google.com/citations?user=c66GnOEAAAAJ&hl=en'>Xiaosong Wang</a> and Prof. <a href='https://weijiemax.github.io/'>Weijie Ma</a>.

Research Interest: World Models, Video Generation, LLM & VLM Reasoning, 3D Reconstruction, Medical AI.

<span style="color: #e74c3c; font-style: italic;">NOTE: I'm currently working on a startup focusing on glasses-free 3D display technology. Welcome students with backgrounds in 3D reconstruction and interactive world models to apply for internships and collaborate! Please send your resume to hr@lynnreal.com</span>


# 🔥 News
- [2026-07] 🎉 One paper accepted by NPJ Digital Medicine (<span style="color: #e74c3c;">IF=18.0</span>).
- [2026-07] 🎉 One paper accepted by Medical Image Analysis (<span style="color: #e74c3c;">IF=14.0</span>).
- [2026-07] 🎉 One paper accepted by ACM MM 2026.
- [2026-06] 🎉 One paper accepted by ECCV 2026.
- [2026-06] Open-sourced BiWM, the first bidirectional autoregressive training framework in the field.
- [2026-05] 🎉 Two papers accepted by ICML 2026.
- [2026-02] 🎉 One paper accepted by CVPR 2026.
- [2026-01] 🎉 One paper accepted by ICASSP 2026 as <span style="color: #e74c3c;">Oral</span>.
- [2025-12] 🎉 One paper accepted by TMI (<span style="color: #e74c3c;">IF=12.4</span>).
- [2025-12] Started internship at Shanda AI Tokyo Research Institute.
- [2025-02] 🎉 Two papers accepted by MICCAI 2025.
- [2025-02] 🎉 One paper accepted by CVPR 2025 as <span style="color: #e74c3c;">Highlight</span>.
- [2024-09] Started joint Ph.D. program at Shanghai Innovation Institute.
- [2023-09] Started internship at Shanghai AI Laboratory.


# 📝 Selected Publications 

<div class='paper-box'><div class='paper-box-image'><div data-venue="ACM MM 2026"><img src='images/medcco_overview.png' alt="MedCCO" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MedCCO: Improving Medical Reasoning with Curriculum-Aware Reinforcement Learning](https://arxiv.org/abs/2505.19213)

***Shaohao Rui***, Kaitao Chen, Weijie Ma, Xiaosong Wang, ACM MM 2026

<div class="pub-links"><a href="https://arxiv.org/abs/2505.19213">[Paper]</a><a href="https://github.com/shaohao011/MedCCO">[Code]</a><a href="javascript:void(0);" onclick="showBibTeX('bib-medcco', 'MedCCO: Improving Medical Reasoning with Curriculum-Aware Reinforcement Learning')">[BibTeX]</a></div>

<span> We introduce MedCCO, a curriculum-driven reinforcement learning framework that unifies close-ended and open-ended medical VQA to improve robust, clinically relevant multimodal reasoning.</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div data-venue="ECCV 2026"><img src='https://raw.githubusercontent.com/ShandaAI/PackForcing/main/assets/overview.png' alt="PackForcing" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PackForcing: Short Video Training Suffices for Long Video Sampling and Long Context Inference](https://arxiv.org/abs/2603.25730)

**Xiaofeng Mao**\*, **Shaohao Rui**\*, Kaining Ying, Bo Zheng, Chuanhao Li, Mingmin Chi, Kaipeng Zhang, ECCV 2026

<span style="font-size:0.9em">\* Equal contribution.</span>

<div class="pub-links"><a href="https://arxiv.org/abs/2603.25730">[Paper]</a><a href="https://github.com/ShandaAI/PackForcing">[Code]</a><a href="javascript:void(0);" onclick="showBibTeX('bib-packforcing', 'PackForcing: Short Video Training Suffices for Long Video Sampling and Long Context Inference')">[BibTeX]</a></div>

<span> We present PackForcing, a framework for autoregressive video diffusion that manages generation history with a three-partition KV-cache: sink tokens for global semantics, highly compressed mid tokens (with dynamic top-k selection), and full-resolution recent tokens for local coherence, plus Temporal RoPE adjustment. It enables long coherent video generation with bounded memory—for example ~2-minute 832×480 video at 16 FPS on one H200 with ~4 GB KV cache and strong VBench temporal metrics—using only short-clip supervision.</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div data-venue="Technical Report 2026"><img src='images/biwm_overview.png' alt="BiWM" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[BiWM: Advancing Open-Source Interactive Video World Models with Bidirectional Autoregression](https://arxiv.org/abs/2606.10135)

***Shaohao Rui***\*, Xiaofeng Mao\*, Zhanyu Zhang, Peijia Lin, Yansong Zhu, Yibo Zhang, Haibin Wan, Weijie Ma, Technical Report 2026

<span style="font-size:0.9em">\* Equal contribution.</span>

<div class="pub-links"><a href="https://arxiv.org/abs/2606.10135">[Paper]</a><a href="https://github.com/LynnReal-AI/BiWM">[Code]</a><a href="javascript:void(0);" onclick="showBibTeX('bib-biwm', 'BiWM: Advancing Open-Source Interactive Video World Models with Bidirectional Autoregression')">[BibTeX]</a></div>

<span> We present BiWM, an open-source full-stack framework for interactive video world models under the bidirectional autoregressive paradigm, balancing generation quality, controllability, and inference speed.</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div data-venue="ICML 2026"><img src='images/adathinkmed.png' alt="AdaThink-Med" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AdaThink-Med: Medical Adaptive Thinking with Uncertainty-Guided Length Calibration](https://arxiv.org/abs/2509.24560)

***Shaohao Rui***, Kaitao Chen, Weijie Ma, Xiaosong Wang, ICML 2026

<div class="pub-links"><a href="https://arxiv.org/abs/2509.24560">[Paper]</a><a href="https://github.com/shaohao011/AdaThinkMed">[Code]</a><a href="javascript:void(0);" onclick="showBibTeX('bib-adathink', 'AdaThink-Med: Medical Adaptive Thinking with Uncertainty-Guided Length Calibration')">[BibTeX]</a></div>

<span> We propose AdaThink-Med, an end-to-end framework that improves adaptive thinking in medical reasoning LLMs via uncertainty-guided length calibration—penalizing overly long chains on easy, solved cases while encouraging deeper reasoning on hard ones. On six medical QA benchmarks it cuts average output length by up to 6.4× with only minor accuracy loss and yields emergent “thinking” vs. “non-thinking” modes.</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div data-venue="CVPR 2026"><img src='images/invcoss.png' alt="InvCoSS" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[InvCoSS: Inversion-driven Continual Self-supervised Learning in Medical Multi-modal Image Pre-training](https://arxiv.org/abs/2512.19213)

**Zihao Luo**\*, **Shaohao Rui**\*, Zhenyu Tang, Guotai Wang, Xiaosong Wang, CVPR 2026

<span style="font-size:0.9em">\* Equal contribution.</span>

<div class="pub-links"><a href="https://arxiv.org/abs/2512.19213">[Paper]</a><a href="https://github.com/Zihaoluoh/InvCoSS">[Code]</a><a href="javascript:void(0);" onclick="showBibTeX('bib-invcoss', 'InvCoSS: Inversion-driven Continual Self-supervised Learning in Medical Multi-modal Image Pre-training')">[BibTeX]</a></div>

<span> We propose InvCoSS, an inversion-driven continual self-supervised learning framework for medical multi-modal image pre-training. It synthesizes images by inverting prior-stage models—avoiding raw data replay—while mitigating catastrophic forgetting under privacy constraints. We introduce InvUNet for higher-fidelity inversion and repulsive representation learning to improve diversity; experiments on nine downstream tasks show performance comparable to or better than data-replay methods without storing past raw data.</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div data-venue="ICASSP 2026"><img src='images/cardio_cot.png' alt="CardioCoT" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CardioCoT: Hierarchical Reasoning for
Multimodal Survival Analysis](https://ieeexplore.ieee.org/abstract/document/11461484)

**Shaohao Rui**, Haoyang Su, Jinyi Xiang,
Lian-Ming Wu, and Xiaosong Wang, ICASSP 2026 <span style="color: #e74c3c;">Oral</span>

<div class="pub-links"><a href="https://ieeexplore.ieee.org/abstract/document/11461484">[Paper]</a><a href="https://github.com/shaohao011/CardioCoT.git">[Code]</a><a href="javascript:void(0);" onclick="showBibTeX('bib-cardiocot', 'CardioCoT: Hierarchical Reasoning for Multimodal Survival Analysis')">[BibTeX]</a></div>

<span> We propose CardioCoT, a hierarchical reasoning-enhanced survival analysis framework for MACE recurrence risk prediction in AMI patients, leveraging postoperative cardiac MRI and clinical notes. CardioCoT integrates evidence-augmented reasoning with imaging data, achieving superior predictive performance and interpretability to support precision clinical decision-making.</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div data-venue="CVPR 2025"><img src='images/cvpr2025.png' alt="BrainMVP" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[BrainMVP: Multi-modal Vision Pre-training for Medical Image Analysis](https://github.com/shaohao011/BrainMVP)

***Shaohao Rui***, Lingzhi Chen, Zhenyu Tang, Lilong Wang, Mianxin Liu, Shaoting Zhang, Xiaosong Wang, CVPR 2025 <span style="color: #e74c3c;">Highlight</span>

<div class="pub-links"><a href="https://github.com/shaohao011/BrainMVP">[Paper]</a><a href="https://github.com/shaohao011/BrainMVP">[Code]</a><a href="javascript:void(0);" onclick="showBibTeX('bib-brainmvp', 'BrainMVP: Multi-modal Vision Pre-training for Medical Image Analysis')">[BibTeX]</a></div>

<span> We introduce the first multi-modal vision pre-training method (BrainMVP) for missing modality medical data. We demonstrate the superior performance and the enhanced generalizability of our BrainMVP pre-trained models on ten public segmentation and classification
benchmarks compared to state-of-the-art methods.</span>

</div>
</div>


# 🎖 Honors and Awards
- *2024.06*, Outstanding Undergraduate Graduate.
- *2023.11*, National Scholarship.
- *2023.09*, Outstanding Student Award.


# 📖 Educations
- *2024.09 - now*, PHD, Shanghai Jiao Tong University.

# 💼 Internships
- *2025.12 - 2026.04*, Shanda AI Tokyo Research Institute, Tokyo, Japan
- *2023.09 - 2025.11*, Shanghai AI Laboratory, Shanghai, China

<p>
  <center>
  <div id="clustrmaps-widget" style="width:100%">
  <script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=a&t=tt&d=VKem6KGRbZnPBJRQf_6HAyxQnIXt5Paw0U1zfFjbuwU'></script>
  </div> 
  </center>
 </p >

<script>
var BIBTEX_ENTRIES = {
  'bib-medcco': `@article{rui2025improving,
  title={Improving medical reasoning with curriculum-aware reinforcement learning},
  author={Rui, Shaohao and Chen, Kaitao and Ma, Weijie and Wang, Xiaosong},
  journal={arXiv preprint arXiv:2505.19213},
  year={2025}
}`,
  'bib-packforcing': `@article{mao2026packforcing,
  title={Packforcing: Short video training suffices for long video sampling and long context inference},
  author={Mao, Xiaofeng and Rui, Shaohao and Ying, Kaining and Zheng, Bo and Li, Chuanhao and Chi, Mingmin and Zhang, Kaipeng},
  journal={arXiv preprint arXiv:2603.25730},
  year={2026}
}`,
  'bib-biwm': `@article{rui2026biwm,
  title={BiWM: Advancing Open-Source Interactive Video World Models with Bidirectional Autoregression},
  author={Rui, Shaohao and Mao, Xiaofeng and Zhang, Zhanyu and Lin, Peijia and Zhu, Yansong and Zhang, Yibo and Wan, Haibin and Ma, Weijie},
  journal={arXiv preprint arXiv:2606.10135},
  year={2026}
}`,
  'bib-adathink': `@article{rui2025adathink,
  title={AdaThink-Med: Medical Adaptive Thinking with Uncertainty-Guided Length Calibration},
  author={Rui, Shaohao and Chen, Kaitao and Ma, Weijie and Wang, Xiaosong},
  journal={arXiv preprint arXiv:2509.24560},
  year={2025}
}`,
  'bib-invcoss': `@inproceedings{luo2026invcoss,
  title={InvCoSS: Inversion-driven Continual Self-supervised Learning in Medical Multi-modal Image Pre-training},
  author={Luo, Zihao and Rui, Shaohao and Tang, Zhenyu and Wang, Guotai and Wang, Xiaosong},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={42626--42636},
  year={2026}
}`,
  'bib-cardiocot': `@inproceedings{rui2026cardiocot,
  title={Cardiocot: Multimodal Prediction of Mace Recurrence Risk with Hierarchical Chain-of-Thought Reasoning},
  author={Rui, Shaohao and Su, Haoyang and Xiang, Jinyi and Wu, Lian-Ming and Wang, Xiaosong},
  booktitle={ICASSP 2026-2026 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)},
  pages={11812--11816},
  year={2026},
  organization={IEEE}
}`,
  'bib-brainmvp': `@inproceedings{rui2025multi,
  title={Multi-modal vision pre-training for medical image analysis},
  author={Rui, Shaohao and Chen, Lingzhi and Tang, Zhenyu and Wang, Lilong and Liu, Mianxin and Zhang, Shaoting and Wang, Xiaosong},
  booktitle={Proceedings of the Computer Vision and Pattern Recognition Conference},
  pages={5164--5174},
  year={2025}
}`
};

function showBibTeX(bibId, title) {
  var modal = document.getElementById('bibtex-modal');
  var titleElement = document.getElementById('bibtex-title');
  var contentElement = document.getElementById('bibtex-content');
  if (!modal || !titleElement || !contentElement) return;
  titleElement.textContent = title || 'BibTeX Citation';
  contentElement.textContent = BIBTEX_ENTRIES[bibId] || '';
  modal.style.display = 'block';
}

function closeBibTeX() {
  var modal = document.getElementById('bibtex-modal');
  if (modal) modal.style.display = 'none';
}

function copyBibTeX() {
  var contentElement = document.getElementById('bibtex-content');
  if (!contentElement) return;
  navigator.clipboard.writeText(contentElement.textContent);
}

window.addEventListener('click', function(event) {
  var modal = document.getElementById('bibtex-modal');
  if (event.target === modal) closeBibTeX();
});

document.addEventListener('keydown', function(event) {
  if (event.key === 'Escape') closeBibTeX();
});
</script>
