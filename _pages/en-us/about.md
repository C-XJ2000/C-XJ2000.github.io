---
page_id: about
layout: about
title: Profile
permalink: /
subtitle: >
  <br>

selected_papers: false
social: false

announcements:
  enabled: false

latest_posts:
  enabled: false
---

<style>

/* =========================================================
   Overall Page
   ========================================================= */

html,
body {
    overflow-x: hidden;
}


/* =========================================================
   Top Section: Photo + Personal Information + Logo
   ========================================================= */

.top-header-row {
    width: 100%;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
    gap: 40px;
    margin-top: 10px;
    margin-bottom: 35px;
}


/* Photo on the left */
.top-header-photo {
    flex: 0 0 auto;
}

.top-header-photo img {
    width: 210px;   /* Smaller than before */
    max-width: 100%;
    height: auto;
    display: block;
    border-radius: 4px;
}


/* Personal information in the middle */
.top-header-info {
    flex: 1;
    min-width: 0;
    font-size: 16px;
    line-height: 2.0;
}

.top-header-info p {
    margin-top: 6px;
    margin-bottom: 6px;
}


/* Logo on the right */
/* Overall top section */
.top-header-row {
    position: relative;
}


/* Right Logo: customized position */
.top-header-logo {
    position: absolute;

    top: 60px;      /* Vertical position */
    right: 40px;    /* Horizontal position */

    z-index: 10;
}


/* Logo size */
.top-header-logo img {
    width: 170px;
    height: auto;
    display: block;
}


/* =========================================================
   Name and Welcome Message
   ========================================================= */

.profile-name {
    margin-top: 5px;
    margin-bottom: 8px;
}

.profile-welcome {
    margin-top: 0;
    margin-bottom: 20px;
    font-size: 16px;
}


/* =========================================================
   Main Text Layout
   ========================================================= */

.bio-justify p {
    text-align: justify;
    text-align-last: left;
    text-justify: inter-character;
    line-height: 1.8;
    margin-top: 0;
    margin-bottom: 1.3em;
}


/* =========================================================
   Mobile Adaptation
   ========================================================= */

@media screen and (max-width: 768px) {

    .container,
    .container.mt-5 {
        width: 100% !important;
        max-width: 100% !important;
        padding-left: 18px !important;
        padding-right: 18px !important;
    }

    /* Change the top section to a vertical layout on mobile devices */
    .top-header-row {
        flex-direction: column;
        align-items: center;
        justify-content: center;
        gap: 18px;
        margin-top: 5px;
        margin-bottom: 28px;
    }

    .top-header-photo {
        width: 100%;
        text-align: center;
    }

    .top-header-photo img {
        width: 190px;
        max-width: 78%;
        margin-left: auto;
        margin-right: auto;
    }

    .top-header-info {
        width: 100%;
        font-size: 15px;
        line-height: 1.8;
    }

    .top-header-info p {
        margin-top: 4px;
        margin-bottom: 4px;
    }

    .top-header-logo {
        width: 100%;
        text-align: center;
    }

    .top-header-logo img {
        width: 95px;
        margin-left: auto;
        margin-right: auto;
    }

    h2 {
        font-size: 24px;
    }

    html,
    body {
        overflow-x: hidden !important;
    }
}

</style>


<!-- =====================================================
     Top Section: Photo + Personal Information + Logo
     ===================================================== -->

<div class="top-header-row">

  <div class="top-header-photo">
    <img src="{{ '/assets/img/Xuejun_Cheng_GitHub.png.jpg' | relative_url }}" alt="Xuejun Cheng">
  </div>

  <div class="top-header-info">
    <p>- University: Shandong University</p>
    <p>- School: School of Information Science and Engineering</p>
    <p>- Major: Communication Engineering</p>
    <p>- Education: Ph.D. Student</p>
    <p>- Joint Training Institution: National University of Singapore</p>
    <p>- Email: 19854191236@163.com</p>
  </div>

  <div class="top-header-logo">
    <img src="{{ '/assets/img/ICS_LOGO.png' | relative_url }}" alt="ICS Logo">
  </div>

</div>


# Xuejun Cheng

Welcome to my personal homepage!

---

## 👨‍🏫 **Biography**

<div class="bio-justify" markdown="1">

**Xuejun Cheng** is a Ph.D. student and an IEEE Graduate Student Member.  
In September 2023, he was admitted to Shandong University through the postgraduate recommendation program to pursue a Ph.D. degree in Communication Engineering under the successive master's-doctoral program, under the supervision of Prof. Ju Liu (Second-level Professor), with Prof. Zheng Dong as his co-supervisor.  
In 2026, supported by the **China Scholarship Council**, he joined the National University of Singapore as a visiting Ph.D. student under the supervision of Prof. Mehul Motani (IEEE Fellow).

His current research interests include reconfigurable intelligent surfaces (RIS), rate-splitting multiple access (RSMA), integrated sensing and communication (ISAC), stacked intelligent metasurfaces (SIM), and optimization theory. He has conducted a series of studies on beamforming, phase-shift design, and resource optimization for intelligent metasurface-aided wireless communication and sensing systems. He has published research papers in international journals and conferences, including IEEE TVT, IEEE WCL, IEEE ICC, and ICCC. Three papers have been ranked among the **TOP 50 Most Popular Articles of IEEE TVT, WCL, and CL**, respectively. He has been granted three national invention patents, with four additional patents accepted for processing. He serves as a reviewer for international journals including IEEE TVT, IOTJ, and WCL, and as a TPC Member for international conferences including GlobalCom and PIMRC.
 
He has participated in research projects including the National Key Research and Development Program of China and the General Program of the National Natural Science Foundation of China, and has also led a National College Students' Innovation and Entrepreneurship Training Program project. He has received the Samsung Scholarship, First-Class Scholarship for Ph.D. Students, Excellent Award in the Ph.D. Midterm Assessment, Outstanding Graduate of Shandong Province, First-Class Undergraduate Scholarship, and more than forty national-level awards in innovation, entrepreneurship, and academic competitions. 


</div>

---

## 🎓 **Academic Background**

- 2026.09—Present     College of Design and Engineering, National University of Singapore, Joint Ph.D. Training, Supervisor: Mehul Motani (IEEE Fellow)
- 2023.09—Present     School of Information Science and Engineering, Shandong University, Ph.D. in Engineering, Supervisor: Prof. Ju Liu (Second-level Professor)

---

## 🔬 **Research Interests**

- Reconfigurable Intelligent Surfaces (RIS)
- Rate-Splitting Multiple Access (RSMA)
- Integrated Sensing and Communication (ISAC)
- Stacked Intelligent Metasurfaces (SIM)
- Optimization Theory

---

## 🌐 **Academic Services**

- TPC Member of international conferences including IEEE ICC and PIMRC
- Reviewer for international journals including IEEE TVT, IOTJ, and WCL

---

## 📖 **Selected Achievements**

**-** **Please refer to the Publications page at the top for details**

**-** **5 papers completed as first author**

**-** **5 papers completed as corresponding author**


**-** **Patents**

[1] Ju Liu; Xuejun Cheng; Qian Zhang; Guanghui Luo; Yuhui Jiao; Beamforming Method for Practical Intelligent Surface-Aided RSMA Systems. (Invention Patent, Publication No.: CN120110450A)

[2] Ju Liu; Xuejun Cheng; Guanghui Luo; Qian Zhang; Zheng Dong; Beamforming Method for Beyond-Diagonal Intelligent Surface-Aided NOMA Systems. (Invention Patent, Publication No.: CN119051703A)

[3] Ju Liu; Shiyao Guo; Xuejun Cheng; Rang Zhang; Shuai Jiang; Beamforming Method for BD-RIS-Aided ISAC Systems. (Invention Patent, Publication No.: 202611013004.2)

[4] Ju Liu; Xu Cao; Jinghui Yin; Xuejun Cheng; Jing Li; Reversible Adversarial Example Generation Method Based on Self-Embedding Watermarking. (Invention Patent, Publication No.: CN118115343A)

[5] Xuejun Cheng; Chunjing Wang; Niuxiao Liang; Yuan Li; Xinning Geng; Intelligent Flower-Assisted Cultivation Method and System Based on Image Recognition. (Invention Patent, Grant No.: CN114982580B)

[6] Chunjing Wang; Xuejun Cheng; Longxi Liu; Yuan Li; Wanchen Hou; Intelligent Scale, System, and Weighing Method Based on Image Recognition. (Invention Patent, Grant No.: CN114543960B)

[7] Chunjing Wang; Xuejun Cheng; Niuxiao Liang; Longxi Liu; Yuan Li; Wenhao Yu; Intelligent Trash Bin. (Invention Patent, Grant No.: CN114044279B)

---

## 🏆 **Honors and Awards**

- Recommended Admission to Postgraduate Studies without Entrance Examination (2020)
- National Scholarship for Undergraduate Students (2020, Ranked First in the School)
- National Encouragement Scholarship (2018, 2019)
- National Scholarship for Ph.D. Students (2024, 2025)
- Outstanding Graduate of Shandong Province (2021)
- Outstanding Graduate of Shandong University (2026)
- Academic Star of Shandong University (2026, Sole Recipient in the School)
- Outstanding Graduate Research Achievement Award of Shandong University (2026, Sole Recipient in the School)
- Excellent Award in the Ph.D. Midterm Assessment (Ranked First)
- First-Class Undergraduate Academic Scholarship (Sole Recipient in the Major for Four Consecutive Years)
- Outstanding Ph.D. Student Source Scholarship and First-Class Freshman Scholarship


- Samsung Scholarship
- First-Class Scholarship for Ph.D. Students
- Excellent Award in the Ph.D. Midterm Assessment
- Outstanding Graduate of Shandong Province
- First-Class Undergraduate Academic Scholarship
- Outstanding Graduate Student and Outstanding Graduate Student Leader
- Advanced Individual in Innovation and Entrepreneurship
- Outstanding Volunteer Service Team and Advanced Individual in Social Practice (Four Consecutive Times)
- First Prize in the 9th "Datang Cup" National College Students Mobile Communication 5G Technology Competition (National Level)
- Third Prize in the 10th "Datang Cup" National College Students Mobile Communication 5G Technology Competition (National Level)
- First Prize in the 11th "Datang Cup" National College Students Mobile Communication 5G Technology Competition (National Level)

---

<div style="text-align: center; margin-top: 30px; font-size: 14px; opacity: 0.75;">
  👁️ Total Page Views:
  <span id="busuanzi_site_pv">Loading...</span>
  &nbsp;&nbsp;|&nbsp;&nbsp;
  👤 Total Visitors:
  <span id="busuanzi_site_uv">Loading...</span>
</div>

<script src="https://cdn.busuanzi.cc/busuanzi/3.6.9/busuanzi.min.js" defer></script>
