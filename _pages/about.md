---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## About me
<div style="text-align: justify">
Welcome to my home on the web! My name is Frank, I am a fifth year Ph.D. student in Computer Engineering at the University of Illinois at Urbana-Champaign (UIUC). My academic advisor is <a href="http://dmnicol.web.engr.illinois.edu/">Prof. David M. Nicol</a>.
</div><br>
<div style="text-align: justify">
My research at UIUC lies at the intersection between network security, graph theory, probability theory, and quantitative risk. My first goal is to develop a theoretical framework for expressing uncertainty in modeling of multi-step cyber-attacks. My next goal is to design efficient algorithms based on Monte Carlo methods for quantifying the impacts of cyber-attacks against networked computer systems. The estimated impact will help network defenders make quantitative and risk-informed defense decisions prior to and during a cyber-attack.
</div><br>
<div style="text-align: justify">
Prior to Illinois, I worked for four years (2011-2015) as a full-time software engineer at the <a href="https://adsc.illinois.edu/">Advanced Digital Sciences Center</a> (ADSC), a Singapore-based research center established and led by UIUC and funded by Singapore's Agency for Science, Technology, and Research (A*STAR). I worked with <a href="https://istd.sutd.edu.sg/people/faculty/david-yau">Prof. David Yau</a>, <a href="https://personal.ntu.edu.sg/tanrui/">Prof. Rui Tan</a>, <a href="https://istd.sutd.edu.sg/people/faculty/binbin-chen">Prof. Binbin Chen</a>, and Dr. Daekwoo Jung on smart grid security, demand response, building energy efficency, and wireless sensor networks.
</div><br>
<div style="text-align: justify">
I got my undergraduate degree in Computer Engineering from the School of Computing, National University of Singapore (NUS) in 2011. In my undergrad thesis, I designed a control scheme to save mobile device's battery power by adapting the LCD screen brightness level to the ambient light and the running applications.
</div><br>

## Contact
<div style="text-align: justify">
<b>Office:</b> 448, Coordinated Science Lab, 1308 W Main St, Urbana, IL 61801<br>
<b>Email:<b/> nhh311(at)gmail(dot)com<br>
<b>Phone:</b> (217) 751-2eight4six<br>
</div><br>

<SCRIPT>
function ShowAndHide(SectionName) {
    var x = document.getElementById(SectionName);
    if (x.style.display == 'none') {
        x.style.display = 'block';
    } else {
        x.style.display = 'none';
    }
}
</SCRIPT>

## Announcement
<div style="text-align: justify">
<b>March 14th, 2022:</b> My paper <i>"Exploiting monotonicity and symmetry for evaluation of highly dependable systems"</i> has been accepted to appear in The 52nd Annual IEEE/IFIP International Conference on Dependable Systems and Networks (DSN 2022).
<BUTTON ONCLICK="ShowAndHide('DSN_Abstract')">Abstract</BUTTON>
<DIV ID="DSN_Abstract" STYLE="display:none; padding-left: 7px; padding-right: 7px; background-color:Gainsboro;"><i>"Evaluation of highly dependable systems requires estimating the probability of a significant rare event under which the system fails to meet the requirement. To improve the estimation accuracy, advanced Monte Carlo simulation techniques such as importance sampling (IS) are commonly used. However, IS is known to misbehave under high dimension. As a result, the IS estimator can have a large relative error and underestimate the rare event probability. In this paper, we propose a novel IS method based on the idea of maximum weight minimization (MWM). Our method works by finding the sampling distribution that minimizes the maximum weight of a rare event sample. To alleviate the curse of dimensionality, we develop several heuristics based on two problem-specific structures, namely, monotonicity and symmetry. Using extensive examples from network reliability, stochastic flow analysis, cyber-security risk assessment, and fault tree analysis, we evaluate the performance of MWM, demonstrate its accuracy and scalability, and highlight applications where it outperforms state-of-the-art techniques."</i></DIV>
</div><br>
  
<div style="text-align: justify">
<b>February 23rd, 2022:</b> My paper <i>"A model-based approach for quantitative decision-making in cybersecurity incident response"</i>, has been accepted to the HotSoS 2022 Special Session on Works-in-Progress.
<BUTTON ONCLICK="ShowAndHide('HOTSOS_Abstract')">Abstract</BUTTON>
<DIV ID="HOTSOS_Abstract" STYLE="display:none; padding-left: 7px; padding-right: 7px; background-color:Gainsboro;"><i>"Cybersecurity incident response (CSIR) is an integral part of the organization's risk management strategy to reduce the damage to the network after the initial breach. In spite of the great financial interest and the recent developments, CSIR remains a rather complex process. In particular, the existing literature lacks a quantitative approach that can effectively deal with the complex, uncertain, and rapidly changing nature of cyberattacks. In this work, we developed a model-based approach that seeks to address part of this challenge. The approach allows the defender to (i) aggregate noisy, incomplete, and sometimes conflicting information about the attack and, without fully knowing the scope of the attack, (ii) come up with a containment plan that minimizes the impact of the attack on the network and the cost of making wrong containment decisions based on inaccurate information. We illustrated the approach using an example of a small network and discussed ideas for the future work."</i></DIV>
</div><br>

<div style="text-align: justify">
  <b>February 20th, 2022:</b> I'm excited to share that I will be working at <a href="https://imanage.com/">iManage</a> as a Data Science Intern this summer. My role is to work on various algorithms and use Natural Language Processing (NLP) methods to "rigorously measure the product quality, improve enterprise products, and understand the behavior of end-users".
</div><br>



