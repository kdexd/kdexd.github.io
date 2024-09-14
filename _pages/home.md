---
layout: default
permalink: "/"
---

<div class="row">
  <div class="col-12">
    <h1 style="text-align: center; margin: 1em">{{ site.title }}</h1>
  </div>
  <!--
      Display picture and bio
  -->
  <div class="col-sm-4 col-xs-12"><img alt="{{ site.author.name }}" id="display-pic" src="/static/img/kd1.jpeg"></div>
  <div class="col-sm-8 col-xs-12">
    <p>Building <a href="//worldlabs.ai">World Labs</a> from the ground up.</p>
    <p>
      I finished my PhD in Computer Science at the University of Michigan in May 2024,
      advised by <a href="//web.eecs.umich.edu/~justincj/">Justin Johnson</a>.
      I do computer vision, and these days I spend most of my time in building high-quality datasets.
      My PhD thesis, titled <a href="https://deepblue.lib.umich.edu/handle/2027.42/193220">Language Supervision for Computer Vision</a>, is available publicly.
      <span style="color:#FFFFFF">In my free time, I love rickrolling all my friends.</span>
    </p>
    <p>
      Feel free to say hi: <b>kdexd at umich dot edu</b>
      <br />
      <a href="{{ site.author.cv }}"><i class="ai ai-cv-square ai-3x"></i></a>
      <a href="//scholar.google.com/citations?user={{ site.author.scholar }}"><i class="ai ai-google-scholar-square ai-3x"></i></a>
      <a href="//github.com/{{ site.author.github }}"><i class="fab fa-github fa-3x"></i></a>
      <a href="//twitter.com/{{ site.author.twitter }}"><i class="fab fa-twitter fa-3x"></i></a>
    </p>
  </div>
</div>

<!-- --------------------------------------------------------------------- -->
<hr />

<div class="row">
  <div class="col">
    <h2>Selected Publications</h2>
  </div>
</div>

<!-- MERU -->
<div class="card-row row">
  <div class="col-sm-4 col-xs-12"><img src="/static/paper-figs/Slide7.jpeg" alt="meru" /></div>
  <div class="col-sm-8 col-xs-12">
    <span class="card-title">Hyperbolic Image-Text Representations</span>
    <br />
    <span class="card-desc">
      <b>Karan Desai</b>, Maximilian Nickel, Tanmay Rajpurohit, Justin Johnson, Ramakrishna Vedantam
    </span>
    <br />
    <span><b>ICML 2023</b></span>
    <a class="paper-link" href="//arxiv.org/abs/2304.09172">paper</a>
    <a class="paper-link" href="/static/bibliography/meru_bibtex.txt">bibtex</a>
    <a class="paper-link" href="//github.com/facebookresearch/meru">code</a>
  </div>
</div>

<!-- LG-SSL -->
<div class="card-row row">
  <div class="col-sm-4 col-xs-12"><img src="/static/paper-figs/Slide6.jpeg" alt="lgssl" /></div>
  <div class="col-sm-8 col-xs-12">
    <span class="card-title">Learning Visual Representations via Language-Guided Sampling</span>
    <br />
    <span class="card-desc">
      Mohamed El Banani, <b>Karan Desai</b>, Justin Johnson
    </span>
    <br />
    <span><b>CVPR 2023</b></span>
    <a class="paper-link" href="//arxiv.org/abs/2302.12248">paper</a>
    <a class="paper-link" href="/static/bibliography/lgssl_bibtex.txt">bibtex</a>
    <a class="paper-link" href="//github.com/mbanani/lgssl">code</a>
  </div>
</div>

<!-- RedCaps -->
<div class="card-row row">
  <div class="col-sm-4 col-xs-12"><img src="/static/paper-figs/Slide5.jpeg" alt="redcaps" /></div>
  <div class="col-sm-8 col-xs-12">
    <span class="card-title">RedCaps: Web-curated image-text data created by the people, for the people</span>
    <br />
    <span class="card-desc">
      <b>Karan Desai</b>, Gaurav Kaul, Zubin Aysola, Justin Johnson
    </span>
    <br />
    <span><b>NeurIPS 2021 (Datasets and Benchmarks)</b></span>
    <a class="paper-link" href="//arxiv.org/abs/2111.11431">paper</a>
    <a class="paper-link" href="/static/bibliography/redcaps_bibtex.txt">bibtex</a>
    <a class="paper-link" href="//github.com/redcaps-dataset">code</a>
    <a class="paper-link" href="//redcaps.xyz">website</a>
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
    <span class="card-desc">
      Ramprasaath R. Selvaraju<sup>*</sup>, <b>Karan Desai</b><sup>*</sup>, Justin Johnson, Nikhil Naik
    </span>
    <br />
    <span><b>CVPR 2021</b></span>
    <a class="paper-link" href="//arxiv.org/abs/2012.04630">paper</a>
    <a class="paper-link" href="/static/bibliography/cast_bibtex.txt">bibtex</a>
    <a class="paper-link" href="//github.com/salesforce/CAST">code</a>
    <a class="paper-link" href="//blog.einstein.ai/casting-your-model-learning-to-localize-improves-self-supervised-representations/">blog</a>
  </div>
</div>

<!-- VirTex -->
<div class="card-row row">
  <div class="col-sm-4 col-xs-12"><img src="/static/paper-figs/Slide3.jpeg" alt="virtex" /></div>
  <div class="col-sm-8 col-xs-12">
    <span class="card-title">VirTex: Learning Visual Representations from Textual Annotations</span>
    <br />
    <span class="card-desc">
      <b>Karan Desai</b> and Justin Johnson
    </span>
    <br />
    <span><b>CVPR 2021</b></span>
    <a class="paper-link" href="//arxiv.org/abs/2006.06666">paper</a>
    <a class="paper-link" href="/static/bibliography/virtex_bibtex.txt">bibtex</a>
    <a class="paper-link" href="//github.com/kdexd/virtex">code</a>
    <a class="paper-link" href="//kdexd.github.io/virtex">website</a>
    <a class="paper-link" href="//youtube.com/watch?v=01Pa_1tb5dQ">video</a>
  </div>
</div>

<!-- ProbNMN -->
<div class="card-row row">
  <div class="col-sm-4 col-xs-12"><img src="/static/paper-figs/Slide2.jpeg" alt="probnmn" /></div>
  <div class="col-sm-8 col-xs-12">
    <span class="card-title">Probabilistic Neural-symbolic Models for Interpretable Visual Question Answering</span>
    <br />
    <span class="card-desc">
      Ramakrishna Vedantam, <b>Karan Desai</b>, Stefan Lee, Marcus Rohrbach, Dhruv Batra, Devi Parikh
    </span>
    <br />
    <span><b>ICML 2019</b></span>
    <a class="paper-link" href="//arxiv.org/abs/1902.07864">paper</a>
    <a class="paper-link" href="/static/bibliography/probnmn_bibtex.txt">bibtex</a>
    <a class="paper-link" href="//github.com/kdexd/probnmn-clevr">code</a>
    <a class="paper-link" href="//kdexd.github.io/probnmn-clevr">website</a>
  </div>
</div>

<!-- nocaps -->
<div class="card-row row">
  <div class="col-sm-4 col-xs-12"><img src="/static/paper-figs/Slide1.jpeg" alt="nocaps"/></div>
  <div class="col-sm-8 col-xs-12">
    <span class="card-title">nocaps: novel object captioning at scale</span>
    <br />
    <span class="card-desc">
      Harsh Agrawal<sup>*</sup>, <b>Karan Desai</b><sup>*</sup>, Yufei Wang, Xinlei Chen,
      Rishabh Jain, Mark Johnson, Dhruv Batra, Devi Parikh, Stefan Lee, Peter Anderson
    </span>
    <br />
    <span><b>ICCV 2019</b></span>
    <a class="paper-link" href="//arxiv.org/abs/1812.08658">paper</a>
    <a class="paper-link" href="/static/bibliography/nocaps_bibtex.txt">bibtex</a>
    <a class="paper-link" href="//github.com/nocaps-org">code</a>
    <a class="paper-link" href="//nocaps.org">website</a>
  </div>
</div>

<hr>

<div class="row">
  <div class="col">
    <h2>First Projects</h2>
  </div>
</div>

These are my humble beginnings, I try to keep them functional over the years!

<div class="card-row row">
  <div class="col-md-2 col-sm-2 col-xs-4">
    <img src="/static/img/digit_banner.jpeg" alt="digit-classifier" title="digit classifier"/>
  </div>
  <div class="col-sm-4 col-xs-8">
    <span class="card-title">
      <a href="//github.com/kdexd/digit-classifier"><i class="fab fa-github"></i></a> digit-classifier
    </span>
    <br />
    <span class="card-desc">
      My first neural network using numpy (2015), a multi layer perceptron classifier for MNIST.
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
    <span class="card-desc">
      My first github repository (2015), snake game implemented in JavaScript.
      The game is still functional and hosted on <a href="//kdexd.github.io/snake">Github pages</a>.
    </span>
  </div>
</div>

<script>
  // ------------------------------------------------------------------
  // Cycle through display pictures.
  // Assign a random color to anchors.
  // ------------------------------------------------------------------
  var dpNums = ["2", "3", "4", "1"];

  // Colors from materializecss.com
  // green, orange, blue, brown
  var colors = ["#388e3c", "#e64a19", "#1976d2", "#8d6e63"];
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

      // Change every 5 seconds.
      setTimeout("dpCycler()", 5000);
  }
  window.onload = dpCycler;

</script>
