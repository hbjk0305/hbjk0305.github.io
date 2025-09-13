---
layout:         project_detail
title:          "Smootify: Infinite AI Music Streaming"
start_date:     Jan
end_date:       Jun 2021
selected:       false
pub:            Tobigs, Big Data Study Group
# pub_pre:        "Submitted to "
# pub_post:       'advised by VP. Chanwoo Kim.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Commercialized</span>'

abstract: >-
  Smootify is an AI-powered music streaming project that <strong>generates seamless, natural transitions</strong> between songs using MIDI data and deep learning, enabling infinite and uninterrupted listening experiences.
cover:          /assets/images/covers/smootify.png

links:
  code: https://github.com/ToBigsSound-1516/Smootify
  demo: https://smootify-tobigs1516.netlify.app/project
---

_Smootify_ is an **AI-driven music streaming** project designed to create seamless transitions between songs, enabling truly infinite music streaming experiences. By leveraging advanced **music generation** techniques, Smootify analyzes and connects two different pieces of music in a natural and musically coherent way. The system utilizes MIDI-format music data, specifically drawing from the Lakh Pianoroll Dataset based on the Million Song Dataset, to train its models.
<br><br>
For mashup point detection, Smootify employs Dynamic Time Warping (DTW) and distribution similarity methods to identify optimal mixing points between tracks. To generate smooth transitions, the project adapts convolutional structures from MuseGAN and incorporates a U-Net-based architecture, training the model to predict masked segments between two songs. This approach allows Smootify to generate high-quality, context-aware transitions, resulting in a continuous and enjoyable listening experience.

### Result
<img src="images/smootify_result.png" width=600>

### Demo
<img src="images/smootify_demo1.png" width=300><img src="images/smootify_demo2.png" width=300>

The demo page is [here](https://smootify-tobigs1516.netlify.app/project) and code is [here](https://github.com/ToBigsSound-1516/Smootify).