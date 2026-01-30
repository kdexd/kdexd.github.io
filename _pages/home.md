---
layout: default
permalink: "/"
---

<div class="row">
  <div class="col-12">
    <h1 style="text-align: center; margin: 1em">{{ site.title }}</h1>
  </div>
</div>
<div class="row">
  <div class="col-sm-4 col-xs-12">
    <img alt="{{ site.author.name }}" id="display-pic" src="/static/img/kd1.jpeg" style="margin-top: 1em">
    <br />
    <p style="text-align: center;">
      <a href="{{ site.author.cv }}"><i class="ai ai-cv-square ai-3x"></i></a>
      <a href="//scholar.google.com/citations?user={{ site.author.scholar }}"><i class="ai ai-google-scholar-square ai-3x"></i></a>
      <a href="//github.com/{{ site.author.github }}"><i class="fab fa-github fa-3x"></i></a>
      <a href="//twitter.com/{{ site.author.twitter }}"><i class="fab fa-twitter fa-3x"></i></a>
    </p>

  </div>
  <div class="col-sm-8 col-xs-12">
    <p>
    I am a founding member at <a href="https://worldlabs.ai">World Labs</a>.
    I curate petabyte-scale datasets and train large diffusion models that power <a href="https://worldlabs.ai/blog/marble-world-model">Marble</a>,
    our first product allowing users to generate, edit, and export 3D worlds.
    My data work has also shaped the pre-training strategy of <a href="https://worldlabs.ai/blog/rtfm">RTFM</a>, our research on Real-Time Frame Models.
    </p>
    <p>
    I finished my PhD in Computer Science at the University of Michigan in May 2024, advised by <a href="https://web.eecs.umich.edu/~justincj/">Justin Johnson</a>.
    My PhD work centered on visual representation learning, vision-language models, and image segmentation.
    I am glad to have enjoyed working on these topics in academia back then,
    before they became mainstream in the current wave of Gen AI products since the virality of ChatGPT release in 2022.
    My thesis, titled <a href="https://deepblue.lib.umich.edu/handle/2027.42/193220">Language Supervision for Computer Vision</a>, is available publicly.
    </p>
    <p>
    These days, my favorite pockets of time at work and in personal projects are with data.
    I enjoy the process of iteratively growing web-scale datasets, increasing their quality density by hand-designing data transforms to filter or select samples to better train generative models.
    I like finding simple ways to source data, be it from the internet or by manually recording videos.
    I like vibe coding web interfaces to manually hand-annotate samples or to simply eyeball thousands of images.
    During and before my PhD, I worked on three dataset projects: <a href="https://nocaps.org">nocaps</a>, <a href="https://redcaps.xyz">RedCaps</a>, and <a href="https://cocorem.xyz">COCO-ReM</a>. For the last one, I manually inspected and refined nearly 40,000 segmentation masks to ensure high quality. Those few days were very exhausting, yet very satisfying.
    </p>
    <span style="color:#FFFFFF">In my free time, I love rickrolling all my friends.</span>
  </div>
</div>

<!-- --------------------------------------------------------------------- -->
<hr />

<div class="row">
  <div class="col">
    <h2>Selected Blogs</h2>
  </div>
</div>

<div class="card-row row">
  <div class="col-sm-6 col-xs-12">
    <a href="//worldlabs.ai/blog/marble-world-model">
      <video autoplay loop muted playsinline style="width: 100%; border-radius: 8px;">
        <source src="https://wlt-ai-cdn.art/videos/2025-11-12-clean-720p-24crf/hero.mp4" type="video/mp4">
      </video>
    </a>
    <span class="card-title"><a href="//worldlabs.ai/blog/marble-world-model">Marble: A Multimodal World Model</a></span>
    <br />
    <span class="card-summary">
      World Labs' first product to generate 3D worlds from text, images, videos, and 3D layouts.
      Users can edit and export as Gaussian splats, meshes, and videos.
    </span>
  </div>
  <div class="col-sm-6 col-xs-12">
    <a href="//worldlabs.ai/blog/rtfm">
      <video autoplay loop muted playsinline style="width: 100%; border-radius: 8px;">
        <source src="https://wlt-ai-cdn.art/videos/2025-10-15/hero_video_1024x576.mp4" type="video/mp4">
      </video>
    </a>
    <span class="card-title"><a href="//worldlabs.ai/blog/rtfm">RTFM: A Real-Time Frame Model</a></span>
    <br />
    <span class="card-summary">
      Research work on generating video in real-time based on user interactions,
      treating sets of posed images as spatial memory for conditioning.
    </span>
  </div>
</div>

<!-- --------------------------------------------------------------------- -->
<hr />

<div class="row">
  <div class="col">
    <h2>Selected Publications</h2>
  </div>
</div>

<!-- COCO-ReM -->
<div class="card-row row">
  <div class="col-sm-4 col-xs-12"><img src="/static/paper-figs/Slide8.jpeg" alt="cocorem" /></div>
  <div class="col-sm-8 col-xs-12">
    <span class="card-title">Benchmarking Object Detectors with COCO: A New Path Forward</span>
    <br />
    <span class="card-subtitle">
      Shweta Singh, Aayan Yadav, Jitesh Jain, Humphrey Shi, Justin Johnson, <b>Karan Desai</b>
    </span>
    <br />
    <span><b>ECCV 2024</b></span>
    <a class="paper-link" href="//arxiv.org/abs/2403.18819">paper</a>
    <a class="paper-link" href="/static/bibliography/cocorem_bibtex.txt">bibtex</a>
    <a class="paper-link" href="//github.com/kdexd/coco-rem">code</a>
    <a class="paper-link" href="//cocorem.xyz">website</a>
    <br />
    <span class="card-summary">
    New evaluation dataset and training dataset to study image segmentation models.
    Our dataset rectifies the inconsistencies in COCO dataset -- imprecise mask boundaries and missing non-exhaustive annotations.
    </span>
  </div>
</div>

<!-- MERU -->
<div class="card-row row">
  <div class="col-sm-4 col-xs-12"><img src="/static/paper-figs/Slide7.jpeg" alt="meru" /></div>
  <div class="col-sm-8 col-xs-12">
    <span class="card-title">Hyperbolic Image-Text Representations</span>
    <br />
    <span class="card-subtitle">
      <b>Karan Desai</b>, Maximilian Nickel, Tanmay Rajpurohit, Justin Johnson, Ramakrishna Vedantam
    </span>
    <br />
    <span><b>ICML 2023</b></span>
    <a class="paper-link" href="//arxiv.org/abs/2304.09172">paper</a>
    <a class="paper-link" href="/static/bibliography/meru_bibtex.txt">bibtex</a>
    <a class="paper-link" href="//github.com/facebookresearch/meru">code</a>
    <br />
    <span class="card-summary">
    Images and text can be naturally organized into a hierarchy of concepts.
    Hyperbolic manifolds can embed hierarchies better than flat Euclidean spaces,
    so we train models that yield hyperbolic image-text representations.
    </span>
  </div>
</div>

<!-- LG-SSL -->
<div class="card-row row">
  <div class="col-sm-4 col-xs-12"><img src="/static/paper-figs/Slide6.jpeg" alt="lgssl" /></div>
  <div class="col-sm-8 col-xs-12">
    <span class="card-title">Learning Visual Representations via Language-Guided Sampling</span>
    <br />
    <span class="card-subtitle">
      Mohamed El Banani, <b>Karan Desai</b>, Justin Johnson
    </span>
    <br />
    <span><b>CVPR 2023</b></span>
    <a class="paper-link" href="//arxiv.org/abs/2302.12248">paper</a>
    <a class="paper-link" href="/static/bibliography/lgssl_bibtex.txt">bibtex</a>
    <a class="paper-link" href="//github.com/mbanani/lgssl">code</a>
    <br />
    <span class="card-summary">
    Instead of using augmentations to create positive pairs for contrastive learning, use captions to find semantically similar images.
    Language abstracts away visual variation.
    </span>
  </div>
</div>

<!-- RedCaps -->
<div class="card-row row">
  <div class="col-sm-4 col-xs-12"><img src="/static/paper-figs/Slide5.jpeg" alt="redcaps" /></div>
  <div class="col-sm-8 col-xs-12">
    <span class="card-title">RedCaps: Web-curated image-text data created by the people, for the people</span>
    <br />
    <span class="card-subtitle">
      <b>Karan Desai</b>, Gaurav Kaul, Zubin Aysola, Justin Johnson
    </span>
    <br />
    <span><b>NeurIPS 2021 (Datasets and Benchmarks)</b></span>
    <a class="paper-link" href="//arxiv.org/abs/2111.11431">paper</a>
    <a class="paper-link" href="/static/bibliography/redcaps_bibtex.txt">bibtex</a>
    <a class="paper-link" href="//github.com/redcaps-dataset">code</a>
    <a class="paper-link" href="//redcaps.xyz">website</a>
    <br />
    <span class="card-summary">
    Reddit is a goldmine of naturally paired images and captions.
    We collect 12M pairs from curated subreddits &mdash; high quality data with minimal filtering for representation learning and image captioning.
    </span>
  </div>
</div>

<!-- CAST -->
<div class="card-row row">
  <div class="col-sm-4 col-xs-12">
    <img src="/static/paper-figs/Slide4.jpeg" alt="cast" />
  </div>
  <div class="col-sm-8 col-xs-12">
    <span class="card-title">CASTing Your Model: Learning to Localize Improves Self-Supervised Representations</span>
    <br />
    <span class="card-subtitle">
      Ramprasaath R. Selvaraju<sup>*</sup>, <b>Karan Desai</b><sup>*</sup>, Justin Johnson, Nikhil Naik
    </span>
    <br />
    <span><b>CVPR 2021</b></span>
    <a class="paper-link" href="//arxiv.org/abs/2012.04630">paper</a>
    <a class="paper-link" href="/static/bibliography/cast_bibtex.txt">bibtex</a>
    <a class="paper-link" href="//github.com/salesforce/CAST">code</a>
    <a class="paper-link" href="//blog.einstein.ai/casting-your-model-learning-to-localize-improves-self-supervised-representations/">blog</a>
    <br />
    <span class="card-summary">
    Self-supervised learning works great on ImageNet's iconic single-object images, but struggles with busy scenes.
    Teaching the model to localize objects via attention fixes this.
    </span>
  </div>
</div>

<!-- VirTex -->
<div class="card-row row">
  <div class="col-sm-4 col-xs-12"><img src="/static/paper-figs/Slide3.jpeg" alt="virtex" /></div>
  <div class="col-sm-8 col-xs-12">
    <span class="card-title">VirTex: Learning Visual Representations from Textual Annotations</span>
    <br />
    <span class="card-subtitle">
      <b>Karan Desai</b> and Justin Johnson
    </span>
    <br />
    <span><b>CVPR 2021</b></span>
    <a class="paper-link" href="//arxiv.org/abs/2006.06666">paper</a>
    <a class="paper-link" href="/static/bibliography/virtex_bibtex.txt">bibtex</a>
    <a class="paper-link" href="//github.com/kdexd/virtex">code</a>
    <a class="paper-link" href="//kdexd.github.io/virtex">website</a>
    <a class="paper-link" href="//youtube.com/watch?v=01Pa_1tb5dQ">video</a>
    <br />
    <span class="card-summary">
    We train image captioning models, then transfer their visual backbone to downstream recognition tasks.
    Captions provide richer supervision than class labels, matching ImageNet pretraining with 10x fewer images.
    </span>
  </div>
</div>

<!-- ProbNMN -->
<div class="card-row row">
  <div class="col-sm-4 col-xs-12"><img src="/static/paper-figs/Slide2.jpeg" alt="probnmn" /></div>
  <div class="col-sm-8 col-xs-12">
    <span class="card-title">Probabilistic Neural-symbolic Models for Interpretable Visual Question Answering</span>
    <br />
    <span class="card-subtitle">
      Ramakrishna Vedantam, <b>Karan Desai</b>, Stefan Lee, Marcus Rohrbach, Dhruv Batra, Devi Parikh
    </span>
    <br />
    <span><b>ICML 2019</b></span>
    <a class="paper-link" href="//arxiv.org/abs/1902.07864">paper</a>
    <a class="paper-link" href="/static/bibliography/probnmn_bibtex.txt">bibtex</a>
    <a class="paper-link" href="//github.com/kdexd/probnmn-clevr">code</a>
    <a class="paper-link" href="//kdexd.github.io/probnmn-clevr">website</a>
    <br />
    <span class="card-summary">
    For visual question answering, we treat the reasoning program as a latent variable.
    This makes the model more interpretable and lets you ask "what program would have given this answer?"
    </span>
  </div>
</div>

<!-- nocaps -->
<div class="card-row row">
  <div class="col-sm-4 col-xs-12"><img src="/static/paper-figs/Slide1.jpeg" alt="nocaps"/></div>
  <div class="col-sm-8 col-xs-12">
    <span class="card-title">nocaps: novel object captioning at scale</span>
    <br />
    <span class="card-subtitle">
      Harsh Agrawal<sup>*</sup>, <b>Karan Desai</b><sup>*</sup>, Yufei Wang, Xinlei Chen,
      Rishabh Jain, Mark Johnson, Dhruv Batra, Devi Parikh, Stefan Lee, Peter Anderson
    </span>
    <br />
    <span><b>ICCV 2019</b></span>
    <a class="paper-link" href="//arxiv.org/abs/1812.08658">paper</a>
    <a class="paper-link" href="/static/bibliography/nocaps_bibtex.txt">bibtex</a>
    <a class="paper-link" href="//github.com/nocaps-org">code</a>
    <a class="paper-link" href="//nocaps.org">website</a>
    <br />
    <span class="card-summary">
    Can captioning models describe objects they've never seen captions for?
    This benchmark tests generalization to 400+ novel object classes using detection data as a bridge.
    </span>
  </div>
</div>

<hr>

<div class="row">
  <div class="col">
    <h2>First Projects</h2>
  </div>
</div>

I managed to preserve my 'firsts' from back in 2015 on Github, and I try to keep them functional for as long as I can.
These are my humble beginnings.

<div class="card-row row">
  <div class="col-md-2 col-sm-2 col-xs-4">
    <img src="/static/img/digit_banner.jpeg" alt="digit-classifier" title="digit classifier"/>
  </div>
  <div class="col-sm-4 col-xs-8">
    <span class="card-title">
      <a href="//github.com/kdexd/digit-classifier"><i class="fab fa-github"></i></a> digit-classifier
    </span>
    <br />
    <span class="card-summary">
      My first neural network using numpy, a multi layer perceptron classifier for MNIST.
      Back then, this repo made to the Github trending charts for almost two weeks.
      Simpler times.
    </span>
  </div>
  <!-- -->
  <!-- -->
  <div class="col-md-2 col-sm-2 col-xs-4">
    <img src="/static/img/snake_banner.jpeg" alt="snake" title="snake"/>
  </div>
  <div class="col-sm-4 col-xs-8">
    <span class="card-title">
      <a href="//github.com/kdexd/snake"><i class="fab fa-github"></i></a> snake
    </span>
    <br />
    <span class="card-summary">
      My first github repository, snake game implemented in JavaScript.
      The game is still functional and hosted on <a href="//kdexd.github.io/snake">Github pages</a>.
    </span>
  </div>
</div>

<script>
  // ------------------------------------------------------------------
  // Cycle through display pictures.
  // Assign a random color to anchors.
  // ------------------------------------------------------------------
  var dpNums = ["4", "2", "3", "1"];

  // Colors from materializecss.com
  // green, brown, orange, blue
  var colors = ["#388e3c", "#8d6e63", "#e64a19", "#1976d2"];
  var id = -1;

  var anchors = document.getElementsByTagName("a");
  var icons = document.getElementsByTagName("i");

  function dpCycler() {
      if (id != -1) {
          document.getElementById("display-pic").src = "/static/img/kd" + dpNums[id] + ".jpeg";
      }
      id = (id + 1) % dpNums.length;

      for (var i = 0; i < anchors.length; i++) {
        anchors[i].style.color = colors[id];
      }
      for (var i = 0; i < icons.length; i++) {
        icons[i].style.color = colors[id];
      }

      // Change every 10 seconds.
      setTimeout("dpCycler()", 10000);
  }
  window.onload = dpCycler;

</script>
