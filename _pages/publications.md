---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

**Rohit Rangwani**, Aamir Abbasi, and Tanuj Gulati.
 "Robust neuroprosthetic control from the cerebellum in the stroke brain". (under review) 
 
Abbasi, Aamir, **Rohit Rangwani**, Daniel W. Bowen, Andrew W. Fealy, Nathan P. Danielsen, and Tanuj Gulati.
 "Cortico-cerebellar coordination facilitates neuroprosthetic control." Science Advances 10, no. 15 (2024): eadm8246.
[Link](https://www.science.org/doi/full/10.1126/sciadv.adm8246)

**Rohit Rangwani***, Simpson, Benjamin K.*, Aamir Abbasi, Jeffrey M. Chung, Chrystal M. Reed, and Tanuj Gulati. 
"Disturbed laterality of non-rapid eye movement sleep oscillations in post-stroke human sleep: a pilot study." Frontiers in Neurology 14 (2023). (*co-first authors)
[Link](https://www.frontiersin.org/journals/neurology/articles/10.3389/fneur.2023.1243575/full)

**Rohit Rangwani**, and Hangue Park.
 "A new approach of inducing proprioceptive illusion by transcutaneous electrical stimulation." Journal of NeuroEngineering and Rehabilitation 18, no. 1 (2021): 1-16.
 [Link](https://jneuroengrehab.biomedcentral.com/articles/10.1186/s12984-021-00870-y)

**Rohit Rangwani**, and Hangue Park. 
"Vibration Induced Proprioceptive Modulation in Surface-EMG Based Control of a Robotic Arm." In 2019 9th International IEEE/EMBS Conference on Neural Engineering (NER), pp. 1105-1108. IEEE, 2019.
[Link](https://ieeexplore.ieee.org/document/8717117)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
