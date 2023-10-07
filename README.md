# A multi-component wave propagation model in a system of 100 linked bodies

<p><img src="https://www.minfo.ru/different_imgs/gif10a.gif" width="600"></p>

Moving from a one-dimensional model to a two-dimensional model, i.e., an elastic system in which waves propagate on a plane, is the next step in demonstrating the capabilities of the new neural architecture. From a physical standpoint, it is based on the construction seen in Fig. 1.

<p><img src="https://www.minfo.ru/different_imgs/img6a.png" width="600"><figcaption>Fig. 1. Model of transverse wave propagation.</figcaption></p>

Parallel to it, the same chain of connected bodies is attached with similar spring connections several times. The elastic plane Fig. 2 is generated, which can recreate more sophisticated wave dynamics and is much more obvious.

<p><img src="https://www.minfo.ru/different_imgs/img7a.png" width="600"><figcaption>Fig. 2. 3D model of an elastic flat medium of vibration propagation.</figcaption></p>

Eight springs connect each body on the plane to its neighbors. The following differential equation describes the motions of a body that is not on the plane's edge: 

<p><img src="https://www.minfo.ru/different_imgs/img8a.png" width="600"></p>

For an elastic plane composed of 100x100 bodies, there will be 10 000 differential equations of second order. The spring coefficient of elasticity is defined as $k_{i,j,1-8}$, and each value can be adjusted individually. In this case, given mi and $c_{i,j}$, we will have 100000 network settings. The cytoarchitectural model will be composed of several columns that will calculate a single equation. Two fibers will be used to connect each column to the adjacent columns. The diagonal columns are included. Ten other parallel fibers will be responsible for parametric segment tuning.

In this section we present a Python code (pyglet library is required) that allows to create inhomogeneous environments in the editor mode and generate oscillation propagation centers in them. An example of the program operation is shown below in Fig.3

[![IMAGE ALT TEXT HERE](https://www.minfo.ru/different_imgs/gif10c.gif)](https://www.youtube.com/watch?v=3UCwfXHrOro)

<p><img src="https://www.minfo.ru/different_imgs/gif10c.gif" width="600"><figcaption>Fig. 1. Model of transverse wave propagation.</figcaption></p>

<p><img src="https://www.minfo.ru/different_imgs/gif10c.gif" width="600"><figcaption>Fig. 3. Demonstration of the work of the program for modeling the propagation of oscillations in inhomogeneous media.</figcaption></p>

https://youtu.be/3UCwfXHrOro


