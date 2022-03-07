---
title: "Article: CFD Post Processing for a Formula Student Car"
categories:
  - Articles
tags:
  - Aerodynamics
  - CFD
header:
  teaser: "/assets/images/cpt-opaque.jpeg"
classes: wide
---

<video width="100%" muted playsinline autoplay="autoplay" loop="loop">
  <source src="/assets/videos/cpt-opaque.mp4" type="video/mp4">
</video>

$$ C_LA = \frac{L}{\frac{1}{2} \rho U_{\infty} ^ 2}$$

<figure>
	<img src="/assets/images/cfd-post-proc-data.jpg">
</figure>

| C_L\*A | C_D\*A | L/D |
| -----: | -----: | --: |
| 2.7 | 1.3 | 2.1 |

$$ p_S = \rho RT $$

$$ p_D = \frac{1}{2}\rho U ^ 2 $$

$$ p_T = p_S + p_D $$

$$ C_{p_T} = \frac{p_T - p_{T_{\infty}}}{p_{D_{\infty}}} $$

<figure>
  <video width="100%" muted playsinline autoplay="autoplay" loop="loop">
    <source src="/assets/videos/CpT-anim-1.mp4" type="video/mp4">
  </video>
</figure>

|  | Lift | Downforce | Drag |
| :--------------- | -------: | -------: | -------------: |
| Bodywork | - | 14.8% | 20.1% |
| Driver | 5.8% | - | 1.3% |
| Engine | 17.1% | - | 5.4% |
| Front Wheel | 36.3% | - | 6.4% |
| Front Wing | - | 42.2% | 10.1% |
| Rear Wheel | 26.9% | - | 9.4% |
| Rear Wing | - | 43.0% | 37.3% |
| Roll Hoop | 2.9% | - | 2.9% |
| Suspension | 10.9% | - | 7.0% |
