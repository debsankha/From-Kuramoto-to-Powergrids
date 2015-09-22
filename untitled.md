# From Kuramoto model to power grids

###ToDo (I list stuff that needs to be done, please do it and then delte the entry in this list):
- Add nice Kuramoto picture for first slide
- add derivation of swing equation
- different ideas for "Effect of network topology on power grid dynamics"?
- Add more research by other people (both in results and open questions)- 

###Kuramoto history and motivation
short history: He started it as a toy model (in 1975) and because multiplicative coupling is more complicated to deal with than sine coupling.
It turned out to be a good description for many real world synchronization processes (neuroscience, chemical oscillators, and many more with modified Kuramoto models)
http://i.ytimg.com/vi/lac4TxWyBOg/hqdefault.jpg

###Mathematical achievments on Kuramoto system
(emphasize that most results are obtained for all-to-all coupling instead of complex networks)

###Power grid models
There are many different ways to model power grids:
- very realistic models in special packages (many engineers)
see e.g. http://a.fsdn.com/con/app/proj/gridlab-d/screenshots/312837.jpg
https://ciip.files.wordpress.com/2010/03/screen-shot-2010-03-28-at-9-03-09-am.png
- static load flow models
- super simplified models (e.g. Europe=copper plate)
- Minimal dynamical model: Swing equation

###Derivation of swing equation
Energy conservation leads to swing equation

###Fixed points and synchonous state
The power grid operates stabely at 50Hz in the model this relates to \omega =0 in the swing equation.
The fixed point then is given by \omega=0  and certain angles \theta which depend on the power and the coupling in the network
Example: Two nodes \theta_1-\theta_2=arcsin(\frac{P}{K})
Define the critical coupling as the minimal K so that there exists a fixed point

###Effect of network topology on power grid dynamics
Most Kuramoto results use all-to-all coupling but power grids are not all-to-all
Example: Four node system a) all-to-all
b) line: +-+- c) line: ++--
The critical coupling and hence synchronization depends crucially on the network structure

###Results obtained so far
- New lines can cause the power grid to lose synchrony (Braess paradox)
- Dead ends are unfavorable for basin stability (Peter Menck)
- ...

###Open questions
- Number of fixed points (Deb)
- Spread of perturbations (Xiaozhu)
- Adding control to the self-organized grid (Benjamin)
- ...