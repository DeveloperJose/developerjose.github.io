---
title: "Field Predictions of Hypersonic Cones Using Physics-Informed Neural Networks"
collection: publications
category: conferences
# permalink: /publication/2024-02-17-paper-title-number-4
# excerpt: 'This paper is about fixing template issue #693.'
date: 2022-09-30
venue: 'Proceedings of the ASME 2022 Fluids Engineering Division Summer Meeting'
paperurl: 'https://asmedigitalcollection.asme.org/FEDSM/proceedings-abstract/FEDSM2022/1147145'
citation: 'D. Villanueva, B. Paez, A. Rodriguez, A. Chattopadhyay, V.M. Kotteda, R. Baez, <b>J. Perez</b>, J. Terrazas, V. Kumar, "Field Predictions of Hypersonic Cones Using Physics-Informed Neural Networks". Proceedings of the ASME 2022 Fluids Engineering Division Summer Meeting, 2022.'
---
Physics Informed Neural Networks (PINNs) provide a way to apply deep learning to train a network using data and governing differential equations that control the physical behavior of a system. In this text, we propose using the PINNs framework to solve an inverse problem which will discover the partial differential equations for compressible flow from Mach number = 5 by coupling Navier Stokes Equations with a Deep Neural Network (DNN) based on training data generated by a CFD solver. The equations of momentum in 2-dimensions and the equation of energy will be parametrized to let Neural Networks calculate two established learnable parameters. This paper will focus on capturing physics governed by fluid flow phenomena applied to high-speed flows using PINNs, which will allow us to see disturbances such as a shock wave interaction with the free stream. Subsequently, a quantification of the predicted results of PINNs will be carried out, and it will be determined if PINNs are computationally less expensive than the Spectral Element Method codes so widely used.