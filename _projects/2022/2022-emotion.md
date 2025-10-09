---
layout:         project_detail
title:          Comparison of Recognizing Emotions Depending on Bandwidth-limitation of Digital Speech
start_date:     Mar
end_date:       Jun 2022
selected:       false
pub:            "Bachelor's Thesis in Industrial Engineering, Seoul National University."
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Commercialized</span>'

abstract: >-
  An empirical study examining whether bandwidth limitations in digital speech affect emotional transmission.
# cover:          /assets/images/covers/smart-things.png
links:
  Paper (KOR): 2022/2022-emotion_report.pdf
---

### Problem & Motivation
With the rise of digital communication accelerated by COVID-19 and metaverse technologies, speech signals frequently undergo bandwidth limitations during network transmission. While previous studies on Western languages showed degraded emotion recognition with reduced bandwidth, the impact on Korean speech remained unexplored.

### Research Design
I conducted an experiment with 18 participants who listened to Korean emotional speech across four bandwidth conditions: NB (4kHz), WB (8kHz), SWB (16kHz), and FB (24kHz). The study used professional actors expressing seven emotions (happiness, anger, disgust, fear, neutral, sadness, surprise) from the [KETI emotion dataset](https://aihub.or.kr/opendata/keti-data/recognition-visual/KETI-01-001).

### Result
<div style="margin:1em 0; text-align:center;">
<img src = "images/emotion_result1.png" width=300>
<img src = "images/emotion_result2.png" width=300>
<p style="color:#555; font-size:0.95em; margin-top:0.5em;">
Confusion matrixes
</p>
<br>
<img src="images/emotion_answer.png" width=600>
<p style="color:#555; font-size:0.95em; margin-top:0.5em;">
Emotion Recognition Accuracy
</p>
<br>
<img src="images/emotion_response.png" width=600>
<p style="color:#555; font-size:0.95em; margin-top:0.5em;">
Response time
</p>
</div>

**Bandwidth Effects**
<br>
Bandwidth limitation had no statistically significant effect on emotion recognition accuracy or response time (p > 0.05). This contrasts with previous Western language studies, likely due to Korean having fewer fricatives that require high-frequency information and more limited prosodic variation compared to English.

**Emotion-Specific Patterns**
<br>
Emotion type significantly influenced recognition performance :
* **Anger**: Highest accuracy (Odds Ratio = 31.16) due to distinct vocal characteristics
* **Disgust**: Lowest accuracy (Odds Ratio = 0.53) and longest response times
* **Fear, Neutral, Surprise**: Moderate-to-high recognition rates



### Conclusion
This study provides empirical evidence that linguistic content preservation is sufficient for emotional communication in Korean speech, contradicting assumptions from Western language research. The findings suggest that multimodal approaches (combining audio with visual cues) may be necessary for emotions like disgust that are difficult to convey through voice alone.


### Resources
- Paper: [[KOR]](2022-emotion_report.pdf)