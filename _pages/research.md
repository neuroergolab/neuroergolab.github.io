---
title: "NeuroergoLab - Research"
layout: textlay
excerpt: "NeuroergoLab Lab -- Research"
sitemap: false
permalink: /research/
---

<script>
  function toggleSection(sectionId) {
    var section = document.getElementById(sectionId);
    if (section.style.display === "none") {
      section.style.display = "block";
    } else {
      section.style.display = "none";
    }
  }
</script>

<style>
    .collapsible {
      background-color: #f1f1f1;
      border: none;
      cursor: pointer;
      padding: 18px;
      width: 100%;
      text-align: left;
      outline: none;
      font-size: 18px;
      transition: background-color 0.3s;
    }

    .collapsible.active, .collapsible:hover {
      background-color: #ddd;
    }

    .content {
      padding: 0 18px;
      display: none;
      overflow: hidden;
      /* background-color: #f1f1f1; */
      transition: max-height 0.2s ease-out;
    }

    .content p {
      margin-top: 0;
    }
  </style>


# Research

Click on the research themes below to learn more about our ongoing research projects.

<br>




<div class="collapsible" onclick="toggleSection('hri')">
  <h2>Human-Automation Interactions</h2>
  <p>Fundamental and applied human technology (HRI, HCI) research includes studies of human-machine interactions with collaborative, teleoperated, and wearable robotics to study the impact of human states of fatigue and stress on human-machine trust, situation awareness, and overall task performance.</p>
</div>
<div class="content" id="hri" style="display:none">

## T2D (Team Trust Dynamics in HRI)
**Sponsor: UW Madison**
<div class="row">
<div class="col-sm-3 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/researchimgs/t2d.png" class="img-responsive" width="100%" style="float: center"/>
</div>
<div class="col-sm-9 clearfix">
This work seeks to comprehensively investigate trust dynamics and teaming behaviors within multi-human-robot teams (mHRTs) operating in complex environments, particularly focusing on search and rescue (SAR) scenarios. With the increasing integration of robots into human teams, understanding trust networks between humans and autonomy agents is crucial for operational effectiveness. This study aims to compare trust dynamics, including individual and team trust levels, as well as associated performance metrics, between all-human teams and mHRTs under various conditions, including reliable and unreliable robot behaviors. By utilizing both behavioral and neurophysiological measures, such as neural synchrony and team cognition insights from hyperscanning techniques, the research seeks to provide a deeper understanding of how trust evolves and propagates within mHRTs and its impact on team performance. The investigation also aims to assess the sensitivity of neural measures to changing robot performance in mHRTs, thereby contributing to the development of measurement systems that enable continuous assessment of team trust dynamics in real-world settings.
</div>
</div>
<br>

## Dynamic Trust in Avs
**Sponsor: NSF**
<div class="row">
<div class="col-sm-3 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/researchimgs/dynamictrustav.jpg" class="img-responsive" width="100%" style="float: center"/>
</div>
<div class="col-sm-9 clearfix">
Trust calibration in automated vehicles is an elusive challenge because of limitations in trust measurement and methods that illuminate the impact of technology design decisions on trust and driver behavior. This project will promote the progress of science and advance the national health by advancing an understanding of human-automation trust. Specifically, the project will address the limitations of existing trust measures, model trust and driver behavior, and determine how autonomous vehicles that incorporate trust calibration models can influence dynamic trust and driving behavior. The project will consist of three phases designed to (1) develop a novel and objective measure of dynamic trust using real-time measures of neural activation during AV interactions, (2) model driver interactions with automated vehicles along the spectrum of dynamic trust, and (3) validate the trust measure and driver behavior model with a trust calibration intervention-based driving simulation experiment.
</div>
</div>
<br>

## Shared-space HRC
**Sponsor: NSF – Cyber Human Systems**
<div class="row">
<div class="col-sm-3 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/researchimgs/amelia.png" class="img-responsive" width="100%" style="float: center"/>
</div>
<div class="col-sm-9 clearfix">
  Augmenting Human Cognition with Collaborative Robots. This research will contribute new knowledge and theory of Human-Computer Interaction and Human-Robot Interaction (HRI), by augmenting human cognition for safer and more efficient collaborative robot interaction. The team plans to: (1) develop a novel HRI task/scenario classification scheme in collaborative robotics environments vulnerable to observable systems failures; (2) establish fundamental neurophysiological, cognitive, and socio-behavioral capability models (e.g., workload, cognitive load, fatigue/stress, affect, and trust) during these HRI (i.e., the mind motor machine nexus); (3) use these models to determine when and how a human’s cognitive, social, behavioral and environmental states require adjustment via technology to enhance HRI for efficient and safe work performance; and finally (4) create an innovative and transformative Work 4.0 architecture (AMELIA: AugMEnted Learning InnovAtion) that includes a layer of augmented reality (AR) for human and robots to mutually learn and communicate current states.
</div>
</div>
<br>

## Disaster Robotics
**Sponsor: NSF, Secure America Institute**
<div class="row">
<div class="col-sm-3 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/researchimgs/disasterhri.png" class="img-responsive" width="100%" style="float: center"/>
</div>
<div class="col-sm-9 clearfix">
The objective of the project is to systematically explore how human-robotic interactions are affected during disaster recovery, specifically pertaining to operator states related to fatigue, stress, and insufficient training. Through this project, we have collected operator physiological and cognitive data during Hurricanes Harvey (2017) and Michael (2018) and during the 2018 Kilauea Volcano Eruption.
</div>
</div>
<br>




## Human-Exoskeleton Interactions
**Sponsor: TAMU/TEES, NSF, NIOSH**

<div class="row">
<div class="col-sm-3 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/researchimgs/exo.jpeg" class="img-responsive" width="100%" style="float: center"/>
</div>
<div class="col-sm-9 clearfix">
Recent advances in human-robotic cooperation, across the spectrum of passive assistance to powered augmentation, have shown strong potential to reduce injury risks by reducing or transferring biomechanical loading from targeted joints. However, natural human-robot synchrony (i.e., reducing the mismatch between motor, mind, and machine interactions), learnability, and usability of these technological solutions remain untested. The ultimate goal of this study is to improve exoskeleton-workplace safety and productivity by understanding, assessing, and augmenting the neuroergonomic fit exoskeletons during occupationally fatiguing tasks.
</div>
</div>
<br>
</div>
<br>






<div class="collapsible" onclick="toggleSection('phas')">
  <h2>Predictive Performance, Health, and Safety</h2>
  <p>We analyze worker physiological, movement, and performance-based markers using wearables, digital tech, and IoT across different work contexts (oil and gas, driving) and health conditions (diabetes, OUD) to better understand and predict human states of fatigue and stress, as well as to develop public health and safety engineering solutions to proactively assess and improve human and work conditions.</p>
</div>
<div class="content" id="phas" style="display:none">

## DS-FRM (Decision Support for Fatigue Risk Management)
**Sponsor: NASEM**
<div class="row">
<div class="col-sm-3 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/researchimgs/dsfrm.jpg" class="img-responsive" width="100%" style="float: center"/>
</div>
<div class="col-sm-9 clearfix">
This project adopts a stakeholder-driven approach to develop a technology-enabled decision- support tool to assess and control fatigue risks. Successful implementation of any new and modified safety management system (SMS) elements, such as those proposed here, requires a deeper understanding of the organization’s culture and practices of existing workflows. As such, the proposed research will also uncover opportunities and barriers to empowering offshore energy stakeholders to integrate the decision-support tool as part of the company’s SMS and/or FRMS. Informed by these efforts, the team will implement the tool and provide training across three offshore platforms and evaluate the tool's effectiveness on safety outcomes (behaviors and reports of incidents/near misses), safety culture, tool utilization, and user experience through a longitudinal intervention study. 
</div>
</div>
<br>


## EMPOWER Safety Dashboard
**Sponsor: National Academies of Sciences, Engineering, and Medicine**
<div class="row">
<div class="col-sm-3 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/researchimgs/empower.jpeg" class="img-responsive" width="100%" style="float: center"/>
</div>
<div class="col-sm-9 clearfix">
Sustaining a healthy personal and process safety culture is critical to the well-being and integrity of all organizations especially high-reliability organizations like offshore installations. Traditionally, safety culture is measured with a lengthy employee survey on an annual basis. Survey methodology is fraught with limitations including low response rates, social desirability concerns, the considerable time required to summarize and interpret the survey data, and failure to capture meaningful changes between surveys. Further, survey data do not lend themselves to quick interpretation through visualization and action. Our interdisciplinary team composed of organizational and human factors safety researchers and offshore subject matter experts proposes to address these limitations by developing a novel assessment of safety culture and pairing these data with readiness data in a format that is easy for supervisors to view and act upon. The purpose of the proposed research project is twofold: (1) to develop and test novel measurement tools to capture safety culture and worker readiness using field-friendly methodologies, including experience sampling methodology and wearable devices, and (2) to design, develop, and evaluate the value of a dashboard of worker data called EMPOWER (Evaluate, Measure, Promote Offshore Worker Engagement and Readiness). This dashboard will visually display worker psychological (safety culture) and physiological (lack of fatigue or readiness) data on an interactive user-centered-designed interface so that supervisors can easily access it on a daily basis to support organizational decision-making. The research team will evaluate the extent to which offshore installation supervisors and workers value and anticipate using such previously unavailable safety culture and worker readiness data in real-time, as well as its impact on hypothetical offshore scenario-based decision making.
</div>
</div>
<br>

## Fatigue Assessment with Breath
**Sponsor: DARPA**
<div class="row">
<div class="col-sm-3 clearfix">
  <!-- <img src="{{ site.url }}{{ site.baseurl }}/assets/researchimgs/fab.jpeg" class="img-responsive" width="100%" style="float: center"/> -->
</div>
<div class="col-sm-9 clearfix">
Identifying the state of fatigue, which has a multifaceted etiology, is of significant interest to the defense and industrial sectors. The ability to estimate and predict the states of fatigue remains a critical unmet technical gap. We are working toward creating an integrated suite of algorithms leveraging breath analysis and various wearable biomarkers to assess and predict fatigue. Our integrated solution considers all three fatigue categories, namely sleep deprivation, and physical and mental fatigue, as well as their interactions. We will identify biomarkers of each type of fatigue through the completion of a set of experiments and analyses that induce fatigue in controlled environments, allowing us to study various biomarkers/signatures while controlling several important confounders.
</div>
</div>
<br>

## Sensorimotor functions under multiple spaceflight hazards
**Sponsor: NASA**
<div class="row">
<div class="col-sm-3 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/researchimgs/sensorimotorfun.png" class="img-responsive" width="100%" style="float: center"/>
</div>
<div class="col-sm-9 clearfix">
Crews during lunar orbital and surface missions will be exposed to multiple spaceflight stressors simultaneously, which can adversely impact their sensorimotor and behavioral capacities and subsequently result in performance decrements on manual/vehicle control or extravehicular activities. Fatigue due to cognitive overload or sleep loss has been shown to adversely impact sensorimotor functions in terrestrial studies. Under vestibular challenges following G- transitions, when neurocognitive resources are needed to reinterpret vestibular inputs, fatigue may exacerbate sensorimotor impairment, as the tired brain cannot effectively allocate those resources. Our project characterizes the potential interactive impacts of multiple spaceflight hazards (i.e., cognitive overload, sleep deprivation, and altered gravity) on sensorimotor functions and associated adaptive or disruptive neural responses that explain these interactive effects.
</div>
</div>
<br>



## Smart, Secure, Non-invasive Wearable System for Proactive Detection of Hypoglycemic Events
**Sponsors: Qatar Foundation, TEES**


<div class="row">
<div class="col-sm-3 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/researchimgs/hypodetect.jpeg" class="img-responsive" width="100%" style="float: center"/>
</div>
<div class="col-sm-9 clearfix">
Existing solutions for glucose monitoring such as continuous glucose monitors (CGMs) are invasive, costly, and reactive. Self-monitored glucose approaches are intermittent and miss hypoglycemic events, especially at night. Also, a significant portion of the type 2diabetes patients currently do not use CGM and thus cannot monitor for hypoglycemic events. We propose to develop a wearable, non-invasive, reliable, inexpensive, and proactive device to detect and prevent hypoglycemic events by detecting early onsets of hypoglycemic tremors. The innovation of our approach is to develop a machine-learning-based pattern detection algorithm to explicitly detect and characterize the frequency and amplitude of tremors. Predictive algorithms will be developed for personalized hypoglycemia event risk characterization based on the detected tremors, activity monitoring, and baseline characterization. Finally, the system will provide feedback to the patient using (1) vibration in the haptic wearable sensor system, and (2) smartphone-based auditory and vibrotactile alerts and store/relay hypoglycemic event data to healthcare providers.
</div>
</div>
 

## SOS (Smart Opiate-Withdrawal Symptoms) System
**Sponsors: TAMU Triads for Transformation**

<div class="row">
<div class="col-sm-3 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/researchimgs/sos.jpeg" class="img-responsive" width="100%" style="float: center"/>
</div>
<div class="col-sm-9 clearfix">
Our multi-disciplinary and collaborative proposal aims to develop Smart Opiate-withdrawal Symptoms (SOS) Technology, which is non-invasive, reliable, and proactive, to detect and manage opiate withdrawal symptoms. Existing commercially-available off-the-shelf (COTS) sensors will be employed to detect temporal patterns of physiological and psychological responses associated with short- and long-term opiate withdrawal symptoms (e.g., sweating, heart rate changes, anxiety, muscle cramps, tremors, etc.). The innovation of our approach is to develop machine learning-based pattern detection algorithms to explicitly detect and characterize specific features obtained from the COTS sensor configuration (e.g., sleep quality, heart rate change, tremors) and existing contextual information (e.g., medication use and compliance, age, gender, etc.). Predictive algorithm results will be compared to existing methods of detecting opioid withdrawal episodes (e.g., survey assessment). Finally, the system will explore feedback modalities to different stakeholders: (1) to the patient using vibration in the haptic wearable sensor system or auditory-, haptic- or text-based alerts in smartphones; (2) real-time feedback to healthcare providers to facilitate interventions; and (3) text-based alerts to support groups for social support strengthening.
</div>
</div>

## FRAME (Fatigue Risk Assessment and Management in high-risk Environments)
**Sponsor: Ocean Energy Safety Institute, National Academies of Sciences, Engineering, and Medicine**
<div class="row">
<div class="col-sm-3 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/researchimgs/frame.jpeg" class="img-responsive" width="100%" style="float: center"/>
</div>
<div class="col-sm-9 clearfix">
The oil and gas extraction (OGE) industry continues to experience a fatality rate nearly seven times higher than that for all U.S. workers. OGE workers are exposed to intensive shift patterns and long work durations inherent in this environment. This leads to fatigue, thereby increasing the risks of accidents and injuries. Fatigue is a physiological state of reduced mental or physical performance capability resulting from sleep loss, circadian phase, and/or workload. It has been implicated as a critical risk in OGE operations and was identified as a causal risk factor in two major incidents – the BP Texas City Refinery Explosion and the Macondo Well Explosion and Fire. However, systematic studies to identify, assess, and manage fatigue-related risks in OGE operations are limited. Effective fatigue assessment methods must be developed to address the elevated fatality rate in the OGE onshore and offshore industries. The objectives of the proposed work are to develop a reliable fatigue survey and a personalized fatigue prediction tool, using innovative machine learning algorithms, that employ the survey responses, worker characteristics, and planned workload/schedules.
</div>
</div>
To access the Fatigue Risk Assessment and Management in high-risk Environments (FRAME) survey, please click here: FRAME survey
<br>

## Mechanisms of Neuromuscular Fatigue
**Sponsor: NIH**
Obesity is associated with decreased functional mobility and increased falls risk among adults over 65 years, especially in women. The project will identify the central (neural) mechanisms that contribute to the reduction in motor function (decreased strength and increased limb fatigability) that occurs with obesity in older men and women. We will utilize a variety of non-invasive integrated approaches (fNIRS and TMS as well as a dynamic fatigue protocol) to probe the central nervous system in order to examine obesity and sex differences in neural control. Findings will help identify subgroups of older adults who are more vulnerable to declines in functional mobility. Knowing the relative contributions of neural and muscular mechanisms of motor function will aid in developing targeted novel strategies to offset motor declines and functional mobility in older and vulnerable older adults.
<img src="{{ site.url }}{{ site.baseurl }}/assets/researchimgs/fatiguemech.jpeg" class="img-responsive" width="100%" style="float: center"/>
</div>
<br>







<div class="collapsible" onclick="toggleSection('neurotech')">
  <h2>Human Augmentation Technologies</h2>
  <p>Our applied research and technology development efforts focus on augmenting and supporting embodied cognition through equitable multimodal interface designs, wearable brain-computer interfaces (BCIs), and neurostimulation that are applicable during learning, skill acquisition, and performance augmentation in high-stress operational settings.</p>
</div>
<div class="content" id="neurotech" style="display:none">

## N-HANCE (Neurotechnology for Human AugmeNtation in Critical Environments)
**Sponsor: TAMU, TEES**

<div class="row">
<div class="col-sm-3 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/researchimgs/nhance.jpeg" class="img-responsive" width="100%" style="float: center"/>
</div>
<div class="col-sm-9 clearfix">
Advances in cyber-human systems, e.g., brain-computer interfaces (BCIs), have expanded knowledge of, and support for, human cognition in various educational, work, and health domains. In particular, BCIs have the potential to fundamentally improve the performance of first responders, such as firefighters, who often perform risky operations in life-threatening stressful circumstances. Stress significantly disrupts (i.e., alters and inhibits) neural pathways of cognitive and motor capabilities, resulting in cognitive deficits (e.g., inattention, memory impairments), which ultimately leads to poor situation awareness, impaired decision-making, or increased psychomotor errors. Current user interfaces leverage multimodal feedback and displays to support cognition by facilitating information processing and communication, however, augmentation paradigms to tackle cognitive deficits directly at the source, i.e., the brain, may prove more effective but have been poorly explored. We will develop closed-loop BCIs using fNIRS and tDCS (N-HANCE: Neurotechnology for Human AugmeNtation in Critical Environments) to augment and support cognition under stress in VR-simulated emergency response tasks.
</div>
</div>
<br>


## LEARNER (Learning Environments with Advanced Robotics for Next-generation Emergency Responders)
**Sponsor: NSF – Convergence Accelerator**
<div class="row">
<div class="col-sm-3 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/researchimgs/learner.jpeg" class="img-responsive" width="100%" style="float: center"/>
</div>
<div class="col-sm-9 clearfix">
  Human augmentation technologies such as robotics and augmented reality have the potential to dramatically transform the landscape of emergency response (ER) work. Specifically, collaborative semi-autonomous ground robots can potentially aid surveillance as well as search and rescue operations, powered exoskeletons can augment human physical capacity while still preserving human autonomy, and augmented reality can enhance ER worker cognition both as a tool in itself to support wayfinding, situational collaboration and decision making, but also as a means to operate robots and exoskeletons. The core of this work examines context-sensitive and use-inspired combinations of these augmentation technologies in emergency response to benefit both ER work and workers. 
</div>
</div>
<br>

## iPAL: intelligent Pervasive Augmented reaLity therapies
**Sponsor: NSF Smart & Connected Health**
<div class="row">
<div class="col-sm-3 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/researchimgs/ipal.png" class="img-responsive" width="100%" style="float: center"/>
</div>
<div class="col-sm-9 clearfix">
Opioid use disorder and addiction are now characterized as a nationwide “opioid epidemic,” with overdoses now the leading cause of injury deaths in the United States. While opioid overdose deaths have increased greatly over the past two decades as compared to other chronic diseases (e.g., heart disease) the development of remote monitoring and management tools and techniques for opioid cravings, recovery, and relapse have not kept pace. This project will develop intelligent Pervasive Augmented reaLity therapies (iPAL) – a technology-enabled OUD intervention that aims to help OUD sufferers manage their cravings to reduce their risk for relapse or overdose. iPAL integrates complementary psychotherapies (cognitive behavioral therapy and heart rate variability biofeedback) with immersive technologies (augmented and mixed reality) that will offer convenience, discretion in use, in the moment/real-time through personalized strategies. This work is poised to revolutionize how individuals learn, discover, create, and heal in the broader context of developing treatment strategies for those with OUD.
</div>
</div>

<br> 

</div>
<br>



**Our research is funded by several national and international research and industry agencies.**

<figure class="fourth">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/logos/nsf.png" style="height: 150px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/logos/oesi.jpeg" style="height: 150px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/logos/nih.jpeg" style="height: 150px">
    <img src="{{ site.url }}{{ site.baseurl }}/assets/logos/nasem.jpeg" style="height: 150px">
    <img src="{{ site.url }}{{ site.baseurl }}/assets/logos/qnrf.png" style="height: 150px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/logos/nasa.png" style="height: 150px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/logos/niosh.png" style="height: 150px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/logos/dot.png" style="height: 150px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/logos/cos.png" style="height: 150px">
  <img src="{{ site.url }}{{ site.baseurl }}/assets/logos/sai.jpeg" style="height: 150px">
</figure>
