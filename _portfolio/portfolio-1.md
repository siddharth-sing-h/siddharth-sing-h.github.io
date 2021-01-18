---
title: "Superconducting Qubits"
excerpt: " Microwave package design for qubits and qubit fabrication with Prof. Vibhor Singh at SQD Lab, IISc, Bangalore <br/><img src='/images/1.jpg' style='width:400px;height:350px;'>"
collection: portfolio
---
<p>I joined the SQD lab in January, 2020 for my master thesis project. Initially I was working in the lab, but as COVID pandemic hit, I returned home and the institution was closed for some time. I was fortunate enough to catch a flight back home, given the mass-migration that followed the lockdown anouncement. I started working back again to complete my thesis in such a way that we can do remote work. Starting November I returned to the lab and have continued working on different parts, involving simulation, fabrication and learning measurements with the group during measurement cycles. Implementing a multiqubit chip, from the designing phase to the measurement phase is the overarching goal.  </p>

 <b> Flux mediated coupling of a mechanical oscillator and Fluxonium qubit </b>
 
We developed on the idea ([arxiv.org/abs/2001.05700](https://arxiv.org/abs/2001.05700))  of changing flux without changing magnetic field, by integrating a mechanical oscillator in the SQUID loop though which we are flux-biasing a fluxonium qubit. The [Thesis](https://drive.google.com/file/d/1kyM2c8sp7pLhTdi-nWjw6gwNrvJg8iEY/view?usp=sharing) was submitted as my graduation requirement in July,2020.

 
 <b> High frequency-impedance controlled circuit designing </b>
 <p> Operating a qubit requires controlled exchanges of microwave photons. There should be no disturbance or noise sneeking into the system. While the measurements on the qubit are done, microwave lines with 50 ohm impedance are used. These lines then make several transitions with connectors, filters, amplifiers, couplers and several other microwave circuit components. During this transition the amount of cross-talk or interefernce of signals should be minimum. I have designed several PCB designs where we use different dielectrics and transmission lines design to get desired characteristics from the PCB. </p>
Reference: [Microwave Package Design for Superconducting Quantum Processors](https://arxiv.org/abs/2012.01438)
 
 <p> <b> Finite element Electromagnetic simulations  </b></p>
  <p>Modelling the impedance controlled circuits required understanding the impedance and the amount of reflections and transmission happening between a multiple port network with multiple signals. I used COMSOL to model the S-parametrs. </p> <p>A qubit's frequency, modes and different parameters can be calculated using black box quantisation, which divides the system into linear and non-linear parts. The impedance and admittance calculation is done using COMSOL.</p>
Reference: [Black-box superconducting circuit quantization](https://arxiv.org/abs/1204.0587)
 
 <b> CAD modelling </b>
 <p>To manufacture 3-D cavities, which house the qubit chip and get attached to the cryo-fridge, we calculate the operational frequency of a cavity and design the dimensions accordingly. To make solid-models of the cavities I have used Solidworks and Fusion 360. Similarly I have made appendages for a dilution refrigerator, which allow to house and mount different microwave components as well as shielding components which block multiple sources of noises from the surroundings.   </p>
