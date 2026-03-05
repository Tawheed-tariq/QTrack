<div align="left">
  <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif"
       width="100%" />
</div>


<div align="center">
# [QTrack: Query-Driven Reasoning for Multi-modal MOT](https://arxiv.org/abs/2504.15404)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/context-aware-grounded-teacher-for-source/source-free-object-detection-on-cityscapes-to)](https://paperswithcode.com/sota/source-free-object-detection-on-cityscapes-to?p=context-aware-grounded-teacher-for-source)
[![Website](https://img.shields.io/badge/website-grounded_teacher-purple)]()
[![Demo](https://img.shields.io/badge/demo-hugginface-blue)](https://huggingface.co/papers/2504.15404)
[![Arxiv](https://img.shields.io/badge/Arxiv-paper-red?style=plastic&logo=arxiv)](https://arxiv.org/abs/2504.15404)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)]()
</div>

This is the official Pytorch implementation of QTrack:

["**QTrack**"](https://arxiv.org/abs/2504.15404) by [Tajamul Ashraf](https://www.tajamulashraf.com/), [[Tavaheed Tariq](https://tavaheed.netlify.app/) and [Janibul Bashir](https://www.janibbashir.com/).

---

## NEWS
- **[04/26/2025]** :collision: We achieved new SoTA with 50.8 box mAP on [Cityscapes to Foggy Cityscapes](https://paperswithcode.com/sota/source-free-object-detection-on-cityscapes-to?p=context-aware-grounded-teacher-for-source)!
- **[04/21/2025]** We released an arxiv version.. See more details in our [updated arxiv](https://arxiv.org/abs/2504.15404)! 

---

<div align="center">
<img src="https://github.com/user-attachments/assets/4d94ee45-185b-4e10-b97e-b0a36e3ff42e" width="800px">
</div>

## 🎯 What is QTrack?

**QTrack** is a query-driven multi-object tracking framework that combines vision and language understanding to track specific targets in videos based on natural language queries. Unlike traditional tracking methods that detect and follow all objects in a scene, QTrack focuses only on the objects specified by the query. The framework performs spatiotemporal reasoning to identify the correct target and maintain its identity across frames, even in challenging scenarios such as occlusions, appearance changes, and crowded environments. QTrack integrates a vision-language model with reinforcement learning optimization, enabling accurate, reasoning-aware tracking and consistent trajectory prediction over time.

🔥 Check out our [website]() for more overview!

---

## 🔧 Installation

