---
page_id: Publications
layout: page
title:
permalink: /Publications/
title: Publications
description: Main research achievements in the fields of wireless communication and sensing
nav: true
nav_order: 2
---

<style>

/* =========================================================
   Publications 标题 + ICS Logo
   ========================================================= */

.publications-header {
    width: 100%;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
    margin-top: 5px;
    margin-bottom: 15px;
}


/* Publications标题 */
.publications-header-title {
    flex: 1;
}


/* 标题本身 */
.publications-header-title h2 {
    margin-top: 0;
    margin-bottom: 0;
}


/* 右侧Logo */
.publications-header-logo {
    flex: 0 0 auto;
    margin-left: 40px;
    display: flex;
    align-items: center;
    justify-content: center;
}


/* Logo大小 */
.publications-header-logo img {
    width: 150px;
    height: auto;
    display: block;
}


/* =========================================================
   手机端
   ========================================================= */

@media screen and (max-width: 768px) {

    .publications-header {
        flex-direction: column;
        align-items: flex-start;
        gap: 15px;
    }

    .publications-header-logo {
        width: 100%;
        margin-left: 0;
        justify-content: center;
    }

    .publications-header-logo img {
        width: 90px;
    }
}

</style>


<style>

.pub-list {
    list-style: none;
    counter-reset: pub-counter;
    padding-left: 0;
    margin-left: 0;
    margin-top: 0;
}


/* 每篇论文 */
.pub-list > li {
    counter-increment: pub-counter;
    position: relative;
    padding-left: 3.2em;

    /* 每篇论文之间的间距 */
    margin-bottom: 0.7em;

    /* 同一篇论文内部行距 */
    line-height: 1.65;

    text-align: justify;

    font-family: "Times New Roman", "Songti SC", "SimSun", serif;
    font-size: 17px;
    font-weight: 400;
}


/* 自动生成 [1]、[2]、[3] ... */
.pub-list > li::before {
    content: "[" counter(pub-counter) "]";
    position: absolute;
    left: 0;
    top: 0;
    width: 2.5em;
    text-align: right;

    font-family: "Times New Roman", serif;
    font-size: 17px;
    font-weight: 400;
}


/* Xuejun Cheng：粗体正体 */
.pub-list .author-name {
    font-weight: 700 !important;
    font-style: normal !important;
}


/* 期刊名称：粗体 + 斜体 */
.pub-list .journal-name {
    font-weight: 700 !important;
    font-style: italic !important;
}


/* et al.：斜体 */
.pub-list .etal {
    font-style: italic !important;
    font-weight: 400 !important;
}


/* JCR、IF、论文状态等 */
.pub-list .paper-info {
    font-weight: 800 !important;
    font-style: normal !important;
}


/* 会议简称 */
.pub-list .conference-name {
    font-weight: 800 !important;
    font-style: normal !important;
}

</style>


<div class="publications-header">

  <div class="publications-header-title">
    <h2>📚 <strong>Publications</strong></h2>

    <div style="margin-top: 6px;">
      (*通讯作者)
    </div>

  </div>

  <div class="publications-header-logo">
    <img src="{{ '/assets/img/ICS_LOGO.png' | relative_url }}" alt="ICS Logo">
  </div>

</div>

---

### 📘 **Journal Papers**

<ol class="pub-list">


<!-- =========================
     第一作者论文
     ========================= -->

<li>
<span class="author-name">Xuejun Cheng</span>,
Qian Zhang,
Zheng Dong,
Ju Liu,
Bruno Clerckx,
"Robust Beamforming for Practical RIS-Aided RSMA Systems with Imperfect SIC under Transceiver Hardware Impairments,"
<span class="journal-name">IEEE Transactions on Vehicular Technology</span>,
vol. 75, no. 8, pp. 18703–18708, Aug. 2026.
<span class="paper-info">(JCR Q1, IF = 7.5)</span>
</li>


<li>
<span class="author-name">Xuejun Cheng</span>,
Qian Zhang,
Yuhui Jiao,
Yufei Zhao,
Zheng Dong,
Ju Liu,
"Joint Beamforming and Phase Shifts Design for RIS-Enabled RSMA-ISAC Systems,"
<span class="journal-name">IEEE Wireless Communications Letters</span>.
<span class="paper-info">(Accepted, JCR Q1, IF = 5.5)</span>
<a href="https://doi.org/10.1109/LWC.2026.3725182">DOI</a>
</li>


<li>
<span class="author-name">Xuejun Cheng</span>,
Yuhui Jiao,
Qian Zhang,
<span class="etal">et al.</span>,
"Cramer-Rao Bound Minimization for Stacked Intelligent Metasurfaces-Aided ISAC Systems,"
<span class="journal-name">IEEE Internet of Things Journal</span>.
<span class="paper-info">(Major Revision, JCR Q1, IF = 8.7)</span>
</li>


<li>
<span class="author-name">Xuejun Cheng</span>,
Qian Zhang,
Maoyuan Wang,
Ju Liu,
"Discrete Phase Shifts Optimization for SIM-Aided ISAC Systems: A CRB Perspective,"
<span class="journal-name">IEEE Transactions on Wireless Communications</span>.
<span class="paper-info">(To Be Submitted, JCR Q1, IF = 10.3)</span>
</li>


<!-- =========================
     通讯作者论文
     ========================= -->

<li>
Qian Zhang,
<span class="author-name">Xuejun Cheng</span>*,
Yufei Zhao,
Maoyuan Wang,
Guanghui Luo,
Shiyao Guo,
"RIS-Assisted Multiuser NOMA Networks With Imperfect CSI Under Transceiver Hardware Impairments,"
<span class="journal-name">IEEE Internet of Things Journal</span>.
<span class="paper-info">(学生一作, Major Revision, JCR Q1, IF = 8.7)</span>
</li>


<li>
Qian Zhang,
Lingchen Gu,
Yao Ge,
<span class="author-name">Xuejun Cheng</span>*,
Maoyuan Wang,
"Joint Beamforming and Antenna Position Optimization for Fluid Antenna-Aided ISAC Systems,"
<span class="journal-name">China Communications</span>.
<span class="paper-info">(学生一作, Major Revision, JCR Q2, IF = 3.0)</span>
</li>


<li>
Qian Zhang,
<span class="author-name">Xuejun Cheng</span>*,
Jiaming Shi,
Yufei Zhao,
Rugui Yao,
"Sum Rate Maximization for Practical RIS-Enhanced Rate-Splitting Multiple-Access Systems,"
<span class="journal-name">IEEE Internet of Things Journal</span>.
<span class="paper-info">(学生一作, Under Review, JCR Q1, IF = 8.7)</span>
</li>


<li>
Qian Zhang,
Rugui Yao,
Zheng Dong,
Ye Fan,
Maoyuan Wang,
<span class="author-name">Xuejun Cheng</span>*,
"Low-Complexity Beamforming Algorithm for Sum-Rate Maximization in Intelligent Metasurface-Aided Multiuser Systems,"
<span class="journal-name">IEEE Internet of Things Journal</span>.
<span class="paper-info">(Under Review, JCR Q1, IF = 8.7)</span>
</li>


<li>
Qian Zhang,
Shiyao Guo,
Guanghui Luo,
<span class="author-name">Xuejun Cheng</span>*,
Maoyuan Wang,
"Join Precoding and Phase-Shift Optimization Algorithm for RIS-aided Multiple Access Communication Systems,"
<span class="journal-name">IEEE Transactions on Wireless Communications</span>.
<span class="paper-info">(Under Review, JCR Q1, IF = 10.3)</span>
</li>


<!-- =========================
     合作作者论文
     ========================= -->

<li>
Yunxiao Li,
Qian Zhang,
<span class="author-name">Xuejun Cheng</span>,
Zhiguo Wang,
Ju Liu,
"Secure Transmission for Fluid Antenna-Aided ISAC Systems,"
<span class="journal-name">IEEE Wireless Communications Letters</span>.
<span class="paper-info">(Accepted, JCR Q1, IF = 5.5)</span>
<a href="https://doi.org/10.1109/LWC.2026.3672225">DOI</a>
</li>


<li>
Yuhui Jiao,
Qian Zhang,
<span class="author-name">Xuejun Cheng</span>,
Ju Liu,
"Beyond-Diagonal Stacked Intelligent Metasurface Aided ISAC: Joint Power Allocation and Phase-Shift Design,"
<span class="journal-name">IEEE Wireless Communications Letters</span>.
<span class="paper-info">(Accepted, JCR Q1, IF = 5.5)</span>
<a href="https://ieeexplore.ieee.org/abstract/document/11614485">DOI</a>
</li>


<li>
Maoyuan Wang,
Qian Zhang,
Jiancheng An,
<span class="author-name">Xuejun Cheng</span>,
Zheng Dong,
Deqiang Wang,
"DRL-Based Joint Beamforming and Surface Shape Optimization for Flexible Intelligent Metasurface-Aided ISAC Systems,"
<span class="journal-name">IEEE Wireless Communications Letters</span>,
vol. 15, pp. 4090–4094, 2026.
<span class="paper-info">(JCR Q1, IF = 5.5)</span>
<a href="https://doi.org/10.1109/LWC.2026.3709756">DOI</a>
</li>


<li>
Maoyuan Wang,
Qian Zhang,
Yufei Zhao,
<span class="author-name">Xuejun Cheng</span>,
Zheng Dong,
Deqiang Wang,
Yong Liang Guan,
"DRL-Based Antenna Position Optimization For MA-Assisted OTFS System Under Imperfect CSI,"
<span class="journal-name">IEEE Communications Letters</span>,
vol. 30, pp. 1905–1909, 2026.
<span class="paper-info">(JCR Q2, IF = 4.5)</span>
<a href="https://doi.org/10.1109/LCOMM.2026.3688633">DOI</a>
</li>


<li>
Xiaoxi Liu,
Ju Liu,
<span class="author-name">Xuejun Cheng</span>,
Jing Li,
Wenbo Wan,
"VT-Grapher: Video Tube Graph Network With Self-Distillation for Human Action Recognition,"
<span class="journal-name">IEEE Sensors Journal</span>,
vol. 24, no. 9, pp. 14855–14868, May 2024.
<span class="paper-info">(JCR Q2, IF = 4.5)</span>
</li>


</ol>

---

### 🧑‍🏫 **Conference Papers**

<ol class="pub-list">


<!-- =========================
     第一作者会议论文
     ========================= -->

<li>
<span class="author-name">Xuejun Cheng</span>,
Qian Zhang,
Yunxiao Li,
Zhichao Gao,
Meihui Liu,
Ju Liu,
"Robust Beamforming for Discrete RIS Enhanced RSMA-ISAC Systems,"
2025 IEEE/CIC International Conference on Communications in China
(<span class="conference-name">ICCC</span>),
Shanghai, China, 2025, pp. 1–6.
<span class="paper-info">(EI, 通信领域重要国际会议)</span>
<a href="https://ieeexplore.ieee.org/document/11148732">DOI</a>
</li>


<li>
<span class="author-name">Xuejun Cheng</span>,
Qian Zhang,
Yuhui Jiao,
Shiyao Guo,
Ju Liu,
"Joint Precoding and Phase-Shift Optimization for Beyond-Diagonal RIS-Aided ISAC System,"
2026 IEEE International Conference on Communications
(<span class="conference-name">ICC</span>),
Glasgow, United Kingdom, 2026, pp. 1–6.
<span class="paper-info">(EI, IEEE旗舰会议)</span>
<a href="https://ieeexplore.ieee.org/abstract/document/11586512">DOI</a>
</li>


<!-- =========================
     合作作者会议论文
     ========================= -->

<li>
Yuhui Jiao,
Qian Zhang,
<span class="author-name">Xuejun Cheng</span>,
Yunxiao Li,
Yufei Zhao,
Ju Liu,
Yong Liang Guan,
"Efficient Beamforming for Discrete SIM-Aided Multiuser Systems Under Statistical CSI,"
IEEE Wireless Communications and Networking Conference
(<span class="conference-name">WCNC</span>).
<span class="paper-info">(EI, IEEE旗舰会议)</span>
<a href="https://ieeexplore.ieee.org/document/11555646">DOI</a>
</li>


<li>
Xiaotong Xu,
Qian Zhang,
Yunxiao Li,
<span class="author-name">Xuejun Cheng</span>,
Meihui Liu,
Ju Liu,
"Beamforming Optimization for Extremely Large-Scale RIS-Aided Near-Field Secure Communications,"
International Conference on Signal and Information Processing, Networking and Computers
(<span class="conference-name">ICSINC</span>).
</li>


<li>
Xu Cao,
Ju Liu,
Jinghui Yin,
<span class="author-name">Xuejun Cheng</span>,
Jing Li,
Hao Ma,
Guanghui Luo,
"Reversible Adversarial Examples Based on Self-Embedding Watermark for Image Privacy Protection,"
2024 International Joint Conference on Neural Networks
(<span class="conference-name">IJCNN</span>),
Yokohama, Japan, 2024, pp. 1–8.
</li>


<li>
Meihui Liu,
Qian Zhang,
<span class="author-name">Xuejun Cheng</span>,
<span class="etal">et al.</span>,
"Hierarchical Beam Training and Codebook Design for Movable Antenna-Assisted Near-Field Systems,"
2026 25th International Symposium on Communications and Information Technologies
(<span class="conference-name">ISCIT</span>).
<span class="paper-info">(Accepted)</span>
</li>


</ol>
