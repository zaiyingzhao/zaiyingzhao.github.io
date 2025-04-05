---
layout: home
title: Zaiying Zhao (趙 在瀛)
---

<!-- # Zaiying Zhao (趙 在瀛) -->
Graduate School of Information Science and Technology, University of Tokyo
<!-- linkとicon入れる -->

mail: zhao@cvm.t.u-tokyo.ac.jp

<!-- ![Your photo](assets/images/yourphoto.jpg) -->

<!-- ## About Me

I'm a researcher in [your field] interested in ... -->

<h2>News</h2>

<div id="news-list">
  <div class="news-item"><span class="news-date">Apr 2025</span> – 🎉</div>
  <div class="news-item"><span class="news-date">Feb 2025</span> – Gave a talk</div>
  <div class="news-item"><span class="news-date">Nov 2024</span> – Launched this personal website</div>
  <div class="news-item"><span class="news-date">Sep 2024</span> – 4</div>
  <div class="news-item"><span class="news-date">Jul 2024</span> – 5</div>

  <!-- 以下は最初非表示 -->
  <div class="news-item extra-news" style="display: none;"><span class="news-date">Apr 2024</span> – 6</div>
  <div class="news-item extra-news" style="display: none;"><span class="news-date">Jan 2024</span> – 7</div>
</div>

<button id="toggle-news" class="news-button">More</button>

<style>
  .news-item {
    margin: 0.4em 0;
    padding: 0.4em 1em;
    background: #f9f9f9;
    border-left: 4px solid #007acc;
    border-radius: 0px;
    transition: background 0.2s;
  }

  .news-item:hover {
    background: #f0f8ff;
  }

  .news-date {
    font-weight: bold;
    color: #007acc;
  }

  .news-button {
    margin-top: 0.8em;
    padding: 0.4em 1em;
    background-color: #007acc;
    color: white;
    border: none;
    border-radius: 6px;
    cursor: pointer;
    font-size: 0.9em;
    transition: background-color 0.2s;
  }

  .news-button:hover {
    background-color: #005e99;
  }
</style>

<script>
  const btn = document.getElementById("toggle-news");
  const extras = document.querySelectorAll(".extra-news");
  let expanded = false;

  btn.onclick = function () {
    expanded = !expanded;
    extras.forEach(e => e.style.display = expanded ? "block" : "none");
    btn.innerText = expanded ? "Less" : "More";
  };
</script>

## Publications

<ul class="pub-list">
  <li>
    <a href="https://arxiv.org/abs/1234.5678" target="_blank">
      Exploring Fairness Across Fine-Grained Attributes in Large Vision-Language Models
    </a><br>
    <strong>Zaiying Zhao</strong>, and Toshihiko Yamasaki<br>
    <em><strong>CVPR ReGenAI 2025</strong></em>
  </li>

  <!-- <li>
    <a href="https://arxiv.org/abs/2345.6789" target="_blank">
      Resampled Datasets Are Not Enough: Mitigating Societal Bias Beyond Single Attributes
    </a><br>
    Yuseke Hirota, Jerone T. A. Andrews, Dora Zhao, Orestis Papakyriakopoulos, Apostolos Modas, Yuta Nakashima, <strong>Zaiying Zhao</strong><br>
    <em>EMNLP 2024 (main track)</em>
  </li>

  <li>
    <a href="https://arxiv.org/abs/3456.7890" target="_blank">
      Would Deep Generative Models Amplify Bias in Future Models?
    </a><br>
    Tianwei Chen, <strong>Zaiying Zhao</strong>, Mayu Otani, Noa Garcia, Yuta Nakashima<br>
    <em>CVPR 2024</em>
  </li> -->
</ul>

<style>
  .pub-list {
    list-style-type: none;
    padding-left: 0;
  }

  .pub-list li {
    margin-bottom: 1em;
  }

  .pub-list a {
    font-weight: 600;
    color: #0066cc;
    text-decoration: none;
  }

  .pub-list a:hover {
    text-decoration: underline;
  }
</style>

## Links
<!-- - [Google Scholar](https://scholar.google.com/) -->
<!-- - [GitHub](https://github.com/yourname) -->
- [LinkedIn](https://www.linkedin.com/in/zaiyingzhao/)