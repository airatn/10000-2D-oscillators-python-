# A multi-component wave propagation model in a system of 100 linked bodies

A multi-component wave propagation model in a system of 100 linked bodies is the subject of further investigation. The model that is being described can be conceived as an extended Kuramoto model. We can observe such processes in numerous physical phenomena, for example, in water, sound, seismic or electromagnetic waves. The main property of these systems is the transfer of energy without the transfer of matter since the particles of the medium do not move along with the wave during the propagation of a wave but oscillate around their equilibrium positions.

<p><img src="https://www.minfo.ru/different_imgs/img6.png" width="600"><figcaption>Fig. 1. Model of transverse wave propagation.</figcaption></p>

A transverse wave is a waveform in which the particles of the medium oscillate about their average position, which is perpendicular to the direction of the wave (shown by arrows in Fig. 1). The medium consists of bodies connected only with the neighboring nodes by springs - the elastic objects accumulating mechanical energy. It reflects the fundamental property of wave motions - the existence of a local (short-range) connection between perturbations at neighboring points in space. This model is the first form of harmonic oscillations representation and, for cases with loose ends, is described by the following system (1) of one hundred second-order differential equations:

<p><img src="https://www.minfo.ru/different_imgs/img7.png" width="600"><figcaption></figcaption></p>

Here m is the mass of the corresponding node, k is the coefficient of spring elasticity, and c is the coefficient of resistance.
The third form within the proposed classification is the cytoarchitectural model; it is shown in Fig. 3. The system employs the previously presented block components, which are depicted as the third interpretation in Fig. 3. For greater consistency of perception, each block is associated with a corresponding differential equation simulating a body connected by springs to other neighboring bodies. The upper part shows extra parallel fibers transmitting impulses from one body to another. The entire chain is represented by one hundred equations or a hundred blocks, each connected to the surrounding blocks by two fibers. 

<p><img src="https://www.minfo.ru/different_imgs/img9.png" width="600"><figcaption>Fig. 2.	Fig. 1.	Cerebellum cytoarchitecture and its interpretation as a mechanism for the computational solution of differential equations systems..</figcaption></p>

<p><img src="https://www.minfo.ru/different_imgs/img8.png" width="600"><figcaption>Fig. 2.	Part of the cytoarchitecture of the wave propagation model.</figcaption></p>

For example, below is the code for declaring an array of parallel fibers in conjunction with granular cells:

A phase space with 400 parameters is formed in this program code (according to the perspective of physics) or a neural-commutative network of 400 neurons and parallel fibers (from the point of view of neurobiology).
From a neurobiological perspective, the following code represents 300 Golgi cells that calculate the successive phase space states over time (for PFax, PFvx, and PFx). The specified code does not use the coefficients of damping and elasticity of the spring, which are individual for each body. 


