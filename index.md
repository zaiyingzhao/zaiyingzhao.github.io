---
layout: home
title: Zaiying Zhao (趙 在瀛)
---

<!-- RUN LOCALLY: bundle exec jekyll serve -->
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
### Conference Paper (International)
<ul class="pub-list">
  <li>
    <a href="https://arxiv.org" target="_blank">
      Exploring Fairness Across Fine-Grained Attributes in Large Vision-Language Models
    </a><br>
    <strong>Zaiying Zhao</strong>, and Toshihiko Yamasaki<br>
    <em><strong>CVPR ReGenAI 2025</strong></em>
  </li>
  <li>
    <a href="https://arxiv.org" target="_blank">
      Self-examination Mechanism: Improving Standard Accuracy in Adversarial Purification
    </a><br>
    Sora Suegami, Yutaro Oguri, <strong>Zaiying Zhao</strong>, Yu Kagaya, Toshihiko Yamasaki<br>
    <em><strong>IVSP 2024</strong></em>
  </li>
</ul>

### Conference Paper (Domestic)
<ul class="pub-list">
  <li>
    <a href="https://arxiv.org" target="_blank">
      Large Vision-Language Modelの多様な属性に対する公平性の検証
    </a><br>
    <strong>趙 在瀛</strong>, 山崎 俊彦<br>
    <em><strong>MIRU 2025</strong></em>
  </li>
  <li>
    <a href="https://arxiv.org" target="_blank">
      多様な属性に対する大規模視覚言語モデルの公平性に関する分析
    </a><br>
    <strong>趙 在瀛</strong>, 山崎 俊彦<br>
    <em><strong>JSAI 2025</strong></em>
  </li>
  <li>
    <a href="https://arxiv.org" target="_blank">
      Vision-Languageモデルを利用した画像分類におけるバイアスの言語的抽出と緩和
    </a><br>
    <strong>趙 在瀛</strong>, 熊野 創一郎, 山崎 俊彦<br>
    <em><strong>MIRU 2024, Oral (peer-reviewed)</strong></em>
  </li>
  <li>
    <a href="https://arxiv.org" target="_blank">
      視覚言語モデルを利用した画像分類モデルのバイアス検知と緩和
    </a><br>
    <strong>趙 在瀛</strong>, 熊野 創一郎, 山崎 俊彦<br>
    <em><strong>IPSJ 2024</strong></em>
  </li>
  <li>
    <a href="https://arxiv.org" target="_blank">
      Self-Examination Mechanism: 説明可能AIを用いた敵対的攻撃に対する軽量な防御機構
    </a><br>
    末神 奏宙, 小栗 悠太郎, <strong>趙 在瀛</strong>, 加賀谷 湧, 向井 皇喜, 吉田 舜, 琛 付, 山崎 俊彦<br>
    <em><strong>JSAI 2023</strong></em>
  </li>
</ul>

## Awards / Scholarship

<ul class="award-list">
  <li>
    <span class="award-date">Apr 2025</span> – Research Assistant (WINGS-RA), The University of Tokyo
  </li>
  <li>
    <span class="award-date">Aug 2024</span> – Student Encouragement Award, MIRU2024
  </li>
  <li>
    <span class="award-date">Mar 2024</span> – Best Presentation Award, IVSP 2024
  </li>
</ul>

## Links
<!-- - [Google Scholar](https://scholar.google.com/) -->
<!-- - [GitHub](https://github.com/yourname) -->
- [LinkedIn](https://www.linkedin.com/in/zaiyingzhao/)


<style>
/* News Section */
.news-item{
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

/* Publication Section */
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
} -->

/* Award Section */
.award-list{
    list-style-type: none;
    padding-left: 0;
}

.award-list li {
  margin: 0.4em 0;
  padding: 0.4em 1em;
  background: #fdfdfd;
  border-left: 4px solid #ff9900;
  border-radius: 0px;
  transition: background 0.2s;
}

.award-list li:hover {
    background: #fffaf0;
}

.award-date {
    font-weight: bold;
    color: #cc7a00;
}
</style>

