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
   Keep the same layout as the Chinese homepage
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

    /* Required when the Logo uses absolute positioning */
    position: relative;
}


/* =========================================================
   Photo on the Left
   ========================================================= */

.top-header-photo {
    flex: 0 0 auto;
}

.top-header-photo img {
    width: 190px;
    max-width: 100%;
    height: auto;
    display: block;
    border-radius: 4px;
}


/* =========================================================
   Personal Information in the Middle
   ========================================================= */

.top-header-info {
    flex: 1;
    min-width: 0;

    font-size: 16px;
    line-height: 2.0;

    /*
       Reserve space for the Logo on the right
       to avoid overlap with long English text
    */
    padding-right: 210px;
    box-sizing: border-box;
}

.top-header-info p {
    margin-top: 6px;
    margin-bottom: 6px;
}


/* =========================================================
   Logo on the Right
   The position can be customized using top and right
   ========================================================= */

.top-header-logo {
    position: absolute;

    top: 60px;      /* Larger value moves the Logo downward */
    right: 40px;    /* Larger value moves the Logo to the left */

    z-index: 10;
}


/* Logo Size */

.top-header-logo img {
    width: 180px;
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


    /* =====================================================
       Change the Top Section to a Vertical Layout on Mobile
       ===================================================== */

    .top-header-row {
        flex-direction: column;

        align-items: center;
        justify-content: center;

        gap: 18px;

        margin-top: 5px;
        margin-bottom: 28px;
    }


    /* Photo on Mobile */

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


    /* Personal Information on Mobile */

    .top-header-info {
        width: 100%;

        font-size: 15px;
        line-height: 1.8;

        padding-right: 0;
    }

    .top-header-info p {
        margin-top: 4px;
        margin-bottom: 4px;
    }


    /* =====================================================
       Logo on Mobile
       Disable the absolute positioning used on desktop
       ===================================================== */

    .top-header-logo {
        position: static;

        width: 100%;
        text-align: center;

        margin-top: 5px;
    }

    .top-header-logo img {
        width: 0px;

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
    <p>- Academic Status: Ph.D. Student</p>
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
In September 2023, he was recommended for admission to the successive master's–doctoral program in Communication Engineering at Shandong University. He is supervised by Prof. Ju Liu (Second-Level Professor), with Prof. Zheng Dong as his co-supervisor.  
In 2026, supported by the **China Scholarship Council (CSC)**, he undertook joint Ph.D. training at the National University of Singapore under the supervision of Prof. Mehul Motani (IEEE Fellow).

His research interests include reconfigurable intelligent surfaces (RIS), rate-splitting multiple access (RSMA), integrated sensing and communication (ISAC), stacked intelligent metasurfaces (SIM), and optimization theory. His research focuses on beamforming, phase-shift design, and resource optimization for intelligent metasurface-aided wireless communication and sensing systems. He has published papers in international journals and conferences, including IEEE Transactions on Vehicular Technology (TVT), IEEE Wireless Communications Letters (WCL), IEEE International Conference on Communications (ICC), and IEEE/CIC International Conference on Communications in China (ICCC). Three of his papers have been ranked among the **Monthly Top 50 Most Popular Articles** in IEEE TVT, IEEE WCL, and IEEE Communications Letters (CL), respectively. He has been granted **three Chinese invention patents**, with **four additional invention patent applications accepted for processing**. He serves as a reviewer for journals including IEEE TVT, IEEE Internet of Things Journal (IoTJ), and IEEE WCL, and as a Technical Program Committee (TPC) member for conferences including IEEE GLOBECOM and PIMRC.

He has participated in projects funded by the National Key Research and Development Program of China and the General Program of the National Natural Science Foundation of China, and has led a project under the National College Students' Innovation and Entrepreneurship Training Program. His honors include the Samsung Scholarship, the Kehui Scholarship, the First-Class Scholarship for Ph.D. Students, the Outstanding Award in the Ph.D. Midterm Assessment, the Outstanding Graduate of Shandong Province, and the First-Class Undergraduate Scholarship. He has received more than 40 honors and awards, including awards in national-level innovation, entrepreneurship, and academic competitions.

</div>

---

## 🎓 **Academic Background**

- **Sep. 2026 – Present** | National University of Singapore, College of Design and Engineering | Joint Ph.D. Training | Supervisor: Prof. Mehul Motani (IEEE Fellow)
- **Sep. 2023 – Present** | Shandong University, School of Information Science and Engineering | Ph.D. in Engineering (in progress) | Supervisor: Prof. Ju Liu (Second-Level Professor)

---

## 🔬 **Research Interests**

- Reconfigurable Intelligent Surfaces (RIS)
- Rate-Splitting Multiple Access (RSMA)
- Integrated Sensing and Communication (ISAC)
- Stacked Intelligent Metasurfaces (SIM)
- Optimization Theory

---

## 🌐 **Academic Service**

- Technical Program Committee (TPC) Member for international conferences, including IEEE ICC and PIMRC
- Reviewer for international journals, including IEEE TVT, IEEE IoTJ, and IEEE WCL

---

## 📖 **Selected Research Achievements**

**-** **For details, please see the Publications page in the top navigation bar.**

**-** **7 first-author papers**: IEEE TVT, IEEE IoTJ, IEEE WCL, IEEE ICC, and IEEE ICCC

**-** **4 corresponding-author papers**: IEEE TWC, IEEE IoTJ, and China Communications

**-** **Patents**

[1] Ju Liu; Xuejun Cheng; Qian Zhang; Guanghui Luo; Yuhui Jiao; "A Beamforming Method for Practical RIS-Aided RSMA Systems." (Chinese Invention Patent, Publication No.: CN120110450A)

[2] Ju Liu; Xuejun Cheng; Guanghui Luo; Qian Zhang; Zheng Dong; "A Beamforming Method for Beyond-Diagonal RIS-Aided NOMA Systems." (Chinese Invention Patent, Publication No.: CN119051703A)

[3] Ju Liu; Shiyao Guo; Xuejun Cheng; Rang Zhang; Shuai Jiang; "A Beamforming Method for BD-RIS-Aided ISAC Systems." (Chinese Invention Patent, Application No.: 202611013004.2)

[4] Ju Liu; Xu Cao; Jinghui Yin; Xuejun Cheng; Jing Li; "A Method for Generating Reversible Adversarial Examples Based on Self-Embedding Watermarking." (Chinese Invention Patent, Publication No.: CN118115343A)

[5] Xuejun Cheng; Chunjing Wang; Niuxiao Liang; Yuan Li; Xinning Geng; "An Image Recognition-Based Intelligent Flower Cultivation Assistance Method and System." (Chinese Invention Patent, Grant No.: CN114982580B)

[6] Chunjing Wang; Xuejun Cheng; Longxi Liu; Yuan Li; Wanchen Hou; "An Image Recognition-Based Smart Scale, System, and Weighing Method." (Chinese Invention Patent, Grant No.: CN114543960B)

[7] Chunjing Wang; Xuejun Cheng; Niuxiao Liang; Longxi Liu; Yuan Li; Wenhao Yu; "A Smart Trash Bin." (Chinese Invention Patent, Grant No.: CN114044279B)

---

## 🏆 **Honors and Awards**

- Samsung Scholarship and Kehui Scholarship
- First-Class Scholarship for Ph.D. Students
- Outstanding Award in the Ph.D. Midterm Assessment
- Outstanding Graduate of Shandong Province
- First-Class Undergraduate Academic Scholarship
- Outstanding Graduate Student and Outstanding Graduate Student Leader
- Outstanding Individual in Innovation and Entrepreneurship
- Outstanding Volunteer Service Team and Outstanding Individual in Social Practice (Four Consecutive Times)
- First Prize, 9th “Datang Cup” National College Students' 5G Mobile Communication Technology Competition (National Level)
- Third Prize, 10th “Datang Cup” National College Students' 5G Mobile Communication Technology Competition (National Level)
- First Prize, 11th “Datang Cup” National College Students' 5G Mobile Communication Technology Competition (National Level)

---


<!-- Website Visitor Statistics -->
<div style="text-align: center; margin-top: 30px; font-size: 14px; opacity: 0.75;">
  👁️ Total Page Views:
  <span id="vercount_value_site_pv">Loading...</span>
  &nbsp;&nbsp;|&nbsp;&nbsp;
  👤 Total Visitors:
  <span id="vercount_value_site_uv">Loading...</span>
</div>

<script defer src="https://events.vercount.one/js"></script>

