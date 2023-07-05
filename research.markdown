---
layout: page
title: Research
permalink: /research/
---

### [GEO-FPN: A convolutional neural network for detecting GEO and near-GEO space objects from optical images](https://www.researchgate.net/publication/351152998_GEO-FPN_A_convolutional_neural_network_for_detecting_GEO_and_near-GEO_space_objects_from_optical_images)
##### *April 2021*
It is labour-intensive to detect space objects in the images captured by telescopes. In this paper, we proposed a framework that leverages the Feature Pyramid Network (FPN), a convolutional neural network for image segmentation, to automate RSO detection in telescope images. The backbone used for detecting low-level patterns from images is the pre-trained EfficientNet-B7 on ImageNet. A simple preprocessing is applied to images that are overexposed to scale the input image pixel values, and this thresholding is only conducted using the statistics of the training data. A custom deterministic post-processing method based on vector mathematics is developed to clean the false detections. F1 score of the proposed machine learning framework is 92%, and this performance shows that the convolutional neural networks can be utilised for automating RSO detection from telescope images. 
<img style="float: left;" src="/assets/geo_fpn_example.png" width="750" height="200">
<hr>
<br>

### [M.Sc. Thesis: Generating orbital transfers with Differentiable Programming](https://www.researchgate.net/publication/366138300_Generating_Orbital_Transfers_with_Differential_Programming)
##### *May 2020*
My master's thesis studied transfer trajectories in the Earth-Moon Circular Restricted Three Body Problem. In this system, cost-free transfers known as heteroclinic connections exist between Lyapunov orbits around Lagrange points. I explored an alternate approach to finding heteroclinic connections, by using differentiable programming in place of the differential correction scheme used by the traditional approach. The program used to correct the initial conditions for heteroclinic transfer is written in a differentiable programming framework which allows the use of back-propagation and gradient descent based optimization similar to the training of Machine Learning models.

<img style="float: left;" src="/assets/LP_orbits.png" width="245" height="245">
<img style="float: center;" src="/assets/manifolds.png" width="245" height="245">
<img style="float: right;" src="/assets/hetroclinic_connection.png" width="245" height="245">
<hr>
<br>

### [Study of pulsar emission mechanism using the Giant Metrewave Radio Telescope](/assets/Report_Single_Pulse_Analysis_GMRT.pdf)
##### *July 2018*
Owing to its high sensitivity and extensive frequency coverage, the GMRT allows study of individual
pulses of pulsars. Individual pulses show a variety of structures over a range of timescales, which reveals
a wealth of information about the emission process. These pulses have been observed to consist of one
or more subpulses, which further show quasi-periodic intensity fluctuations known as microstructures.
Furthermore, the pulse intensity often drops to a low value for a few pulses and then abruptly returns to
normal. This phenomenon, known as nulling, is inversely correlated with the age of the pulsar. In this
project, we try to explain the underlying emission mechanism through a detailed analysis of individual
pulse data from several pulsars. The raw data obtained from the GMRT is processed by making use of the
software package GPTool. The output from GPTool is analyzed to obtain the intensity profile for individual
pulses which are then scanned for the presence of microstructures and pulse nulling. The analysis is
performed for several normal pulsars, as well as a few millisecond pulsars which can be observed using
the GMRT.

[Related poster presented at 37th annual meeting of the Astronomical Society of India (February 2019)](/assets/ASI_Poster_Pulsar_Microstructure_with_GMRT.pdf)
<img style="float: left;" src="/assets/single_pulse.jpg" width="750" height="300">
<hr>
<br>

### [Search for two tone suppression using a minimal model for auditory transduction](/assets/Two_tone_suppression.pdf)
##### *December 2018*
In this project we have looked into the phenomenon of two tone suppression inside the
inner ear. From our analysis, we conclude that the suppression occurs at the membrane
level (the oscillator in our model), and is carried over to the neuronal spike level.

<img style="float: left;" src="/assets/two_tone_membrane_displacement.png" width="370" height="300">
<img style="float: right;" src="/assets/two_tone_frequency.png" width="370" height="300">
<hr>
<br>

### [Optimization of orbital parameters for eLISA spacecraft configuration](/assets/eLISA_Project_Report.pdf)
##### *December 2017*
At the undergraduate level, my research was concerned with the optimization of initial conditions for the planned eLISA gravitational wave detector. The mission proposes a constellation of three spacecraft in a heliocentric, Earth-trailing orbit while maintaining a triangular formation with fixed arm length. The initial phases of the spacecraft were optimized in the presence of gravitational effects of the Sun, Earth, Moon and Jupiter, in order to have minimum variation in arm length over a course of three years.
<img style="float: left;" src="/assets/elisa_geometry.png" width="340" height="200">
<img style="float: right;" src="/assets/elisa_optimised.png" width="400" height="200">