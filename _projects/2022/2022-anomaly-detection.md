---
layout:         project_detail
title:          "Anomaly Sound Detection for Home Appliances"
start_date:     Oct 2022
end_date:       Dec 2024
selected:       true
pub:            "Samsung Research."
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Commercialized</span>'

abstract: >-
  An AI-powered diagnostic system of home appliances, released in the domestic market.
cover:          /assets/images/covers/washing_machine.png

---

<div style="margin:1em 0; text-align:center;">
  <iframe width="560" height="315" src="https://youtube.com/embed/opsje6mc7CM?si=cc-X_uY9Lbvhbbs9&start=729" title="YouTube video player" frameborder="0" allowfullscreen></iframe>
  <p style="color:#555; font-size:0.95em; margin-top:0.5em;">
    Official replay video of SDC 2024
  </p>
</div>

### Problem & Real-World Impact
Sound-related complaints comprised large portion of customer Voice of Customer (VoCs), significantly impacting costs and satisfaction. While experts can diagnose appliance problems by listening to machine sounds, most users cannot distinguish between normal operation and malfunction sounds. The goal was to imitate this expert knowledge through AI-powered sound analysis integrated into Samsung's SmartThings ecosystem.

### Technical Solution
<div style="margin:1em 0; text-align:center;">
  <img src="images/ad_architecture.png" width=600>
<img src="images/ad_loss.png" width=600>
  <p style="color:#555; font-size:0.95em; margin-top:0.5em;">
    Screenshots from the presentation video.
  </p>
</div>

**Transformer Architecture**
* Patch-Based Processing: Spectrograms divided into patches for better temporal modeling
* Cascaded Group Attention: Split channels for efficient attention computation
* Bottleneck Structure: Optimized processing efficiency while maintaining accuracy

**Hybrid Contrastive Learning**
* Combined contrastive loss (increases distance between similar yet distinct features) with cross-entropy loss to better discriminate subtle variations in appliance sounds.