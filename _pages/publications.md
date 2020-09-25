---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

*Y. Sun, **Z. Wu**, B. Wohlberg, and U. S. Kamilov, “Scalable Plug-and-Play ADMM with Convergence Guarantees,” arXiv:2006.03224, 2020.

* **Z. Wu**, Y. Sun, A. Matlock, J. Liu, L. Tian, and U. S. Kamilov, “SIMBA: Scalable Inversion in Optical Tomography using Deep Denoising Priors,” _IEEE Journal of Selected Topics in Signal Processing (JSTSP)_, vol. 14, no. 6, pp. 1163-1175, Oct. 2020, doi: 10.1109/JSTSP.2020.2999820.

* **Z. Wu**, Y. Sun, J. Liu, and U. S. Kamilov, “Online Regularization by Denoising with Applications to Phase Retrieval,” _Proceedings of the IEEE International Conference on Computer Vision Workshop (ICCVW)_, 2019. [**Oral presentation**]

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
