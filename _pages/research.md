---
title: "Research"
layout: gridlay
sitemap: false
permalink: /Research/
---

<style>
img{
  border-radius: 10px;
}
.col-md-3 {
  margin-top:10px;
  margin-bottom:10px;
  padding:0px;
  display:block;
  overflow:hidden;
  text-align:center;
  display: table-cell;
  background: white;
  border-radius: 20px;
  height: auto;
}
iframe {
  margin:0;
  padding:0;
  width: 175px;
  display: inline;
  vertical-align: middle;
}
</style>

## Research Highlights

<div class="jumbotron" style="background-color:#EBEFF1; border-radius:5px; padding:10px; margin-bottom:20px;">
<div class="col-md-12 col-sm-12">
<h4>High-resolution subsurface imaging with seismic full-waveform inversion</h4>

Seismic exploration to locate geological resources near the Earth's surface is a costly endeavor with a low success rate and high risk. High-resolution seismic imaging with full-waveform inversion (FWI) helps determine geological structures accurately and allows people to drill wells in the best part of the reservoirs with low damage to the environment. However, due to the lack of low frequencies below ~3 Hz in active-source seismic data that is typically used in seismic exploration, the iterative updating procedure of FWI starting from a rough initial model can easily fail with large artifacts (known as the cycle-skipping issue). During my PhD, I led an industrial-supported project on FWI to solve the problem of lack of low frequencies. We (Sun and Demanet, 2018, 2019, SEG Extended Abstracts; 2020, Geophysics; 2021, IEEE Transactions on Geoscience and Remote Sensing) used deep learning to extrapolate the missing low frequencies from band-limited data. With the low-cost computational low frequencies, we relieved the dependence of FWI on initial models and achieved high-resolution subsurface imaging. In addition, we (Sun et al., 2023, Geophysical Journal International) proposed a strategy to avoid the generalization problem of training with only synthetic data when applied to real data. In a semi-supervised learning framework, we directly train neural networks with real data and “unpaired” synthetic labels. The proposed training strategy enables us to establish a learning framework for general geophysical problems where real labels are unavailable/rare.
</div>
</div>

<div class="jumbotron" style="background-color:#EBEFF1; border-radius:5px; padding:10px; margin-bottom:20px;">
<div class="col-md-12 col-sm-12">
<h4>Seismic monitoring of earthquake sequences for migration of geohazards</h4>

During my postdoctoral research, I have developed new earthquake detection and location algorithms with a bleeding-edge machine learning tool called neural operators to monitor earthquakes with a broad range of magnitudes, from large destructive natural earthquakes to microseismicity. We (Sun et al., 2023, Geophysical Research Letters) developed a multi-station picking algorithm called Phase Neural Operator (PhaseNO) to simultaneously pick seismic arrivals from a seismic network with arbitrary geometries. By leveraging both temporal and spatial information, we achieve F1 scores of 99% for P waves and 98% for S waves on an unseen test dataset. Our pre-trained model shows sufficient generalizability to various areas and geological settings. This approach has great potential to bring seismic monitoring into the next generation. Moreover, we (Sun et al., 2022, ArXiv preprint) present an alternative deep-learning approach for earthquake location by combining the benefits of neural operators for wave propagation and time reversal imaging with multi-station waveform recordings. The new full-waveform earthquake location approach can locate earthquakes without phase picking and is computationally efficient. All these efforts enable us to monitor, assess, and prevent geohazards due to all subsurface activities, such as CO2 and H2 injections and productions.
</div>
</div>

<div class="jumbotron" style="background-color:#EBEFF1; border-radius:5px; padding:10px; margin-bottom:20px;">
<div class="col-md-12 col-sm-12">
<h4>Sensing the near surface of the Earth with ambient noise</h4>

The widespread existence of seismic ambient noise provides unique opportunities to characterize the near surface properties of the Earth, with seismic interferometry (SI). With supervised learning, we (Sun and Demanet, 2022, IEEE Transactions on Neural Network and Learning Systems) train deep neural networks to overcome two limitations of correlation-based SI: the temporal limitation of passive recording length and the spatial limitation of noise source distribution. This study allows us to infer the Earth’s properties from the ambient noise using SI techniques with more accuracy. It also shows promise to provide reliable estimation of Green’s function in the absence of the long time-series needed for temporal averages; the proposed method may allow the application of SI for real-time monitoring of the subsurface.
</div>
</div>

<div class="jumbotron" style="background-color:#EBEFF1; border-radius:5px; padding:10px; margin-bottom:20px;">
<div class="col-md-12 col-sm-12">
<h4>Probing earthquake nucleation mechanisms with geomechanics</h4>

In addition to geophysical observations, fundamental studies of earthquake physics help us to understand earthquake nucleation mechanisms and to mitigate the hazards they pose. Fault zones accommodate relative motion between tectonic blocks and control earthquake nucleation. Extremely fine-grained fault rocks are commonly found in the fault cores, but it remains unclear whether these tiny crystals cause quakes or are merely formed by them. We (Sun and Pec, 2021, Nature Communications) performed rock deformation experiments and studied the mechanical and microstructural responses of these rocks to various driving forces associated with plate tectonic movements. We measured the rheological properties of these fault rocks and determined their flow law. We found that the crystals were extremely weak when shearing was initiated, but the nanocrystals became significantly stronger when the deformation rate accelerated (“rate-strengthening”). The experiment suggests that the crystals’ intrinsic weakness may cause an earthquake when enough accumulate within a fault. 
</div>
</div>