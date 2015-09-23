# From Kuramoto model to power grids

###Kuramoto history and motivation (Benjamin)
short history: He started it as a toy model (in 1975) and because multiplicative coupling is more complicated to deal with than sine coupling.
It turned out to be a good description for many real world synchronization processes (neuroscience, chemical oscillators, and many more with modified Kuramoto models)
http://i.ytimg.com/vi/lac4TxWyBOg/hqdefault.jpg
http://jasss.soc.surrey.ac.uk/10/4/6/Dekker.fig4.gif
http://link.springer.com/chapter/10.1007%2FBFb0013365?LI=true#page-1

###Mathematical achievments on Kuramoto system (Deb)
- Kuramoto(1975):  Scaling of order parameter with K, formula for $K_c$
- Kuramoto & NishiKawa: Finite N fluctuations O(N^-1/2)
- Mirollo & Strogatz: Continuous model, continuity equation
- Mirollo & Strogatz: Linear stability of solutions. 
- Wiley, Strogatz & Givran: Basin volume
(emphasize that most results are obtained for all-to-all coupling instead of complex networks)

###Power grid models (Benjamin)
There are many different ways to model power grids:
- very realistic models in special packages (many engineers)
see e.g. http://a.fsdn.com/con/app/proj/gridlab-d/screenshots/312837.jpg
https://ciip.files.wordpress.com/2010/03/screen-shot-2010-03-28-at-9-03-09-am.png
- static load flow models
- super simplified models (e.g. Europe=copper plate，DC flow model)
- Minimal dynamical model: Swing equation

###Derivation of swing equation (Xiaozhu)
Energy conservation leads to swing equation

###Fixed points and synchonous state (Deb)
The power grid operates stably at 50Hz in the model this relates to \omega =0 in the swing equation.
The fixed point then is given by \omega=0  and certain angles \theta which depend on the power and the coupling in the network
Example: Two nodes \theta_1-\theta_2=arcsin(\frac{P}{K})
Define the critical coupling as the minimal K so that there exists a fixed point
(2 node diagram)
(2 node phase plot)

###Effect of network topology on power grid dynamics (Benjamin)
Most Kuramoto results use all-to-all coupling but power grids are not all-to-all
Example: Four node system a) all-to-all
b) line: +-+- c) line: ++--
The critical coupling and hence synchronization depends crucially on the network structure

###Results obtained so far (For everybody)
- New lines can cause the power grid to lose synchrony (Braess paradox)
- Dead ends are unfavorable for basin stability (Peter Menck)
- Redundant capacity determines the line criticality (tbp)
- Effect of decentralization (martin Rohden)

###Open questions
- Number of fixed points (Deb)
- Spreading of perturbations (Xiaozhu)
- Remote responses in chains/rains (Xiaozhu)
- Adding control to the self-organized grid (Benjamin)
- ...
