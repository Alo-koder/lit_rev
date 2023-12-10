

## Relevance

* Orlik 2009 (review): _Self-organization in nonlinear dynamical systems and its relation to the materials science_
* Ma 2017 (review): _A review for dynamics in neuron and neuronal network_
* TODO find a citation for medical research!

## Quasi Theoretical Foundations

* Joule 1844: _XX. On the intermittent character of the voltaic current in certain cases of electrolysis; and on the intensities of various voltaic arrangements_
	* I mean, its 1844, so cool 😎
	* He observed oscillations during oxygen evolution on iron
	* Two iron electrodes connected to the same source would synchronise

* Turing 1952: _The chemical basis of morphogenesis_
	* Predicts/explains that chemical oscillations can only occur when there's a significant difference between concentration timescale for two reagents
	* For our system, potential is the other 'reagent' -- that's why it works
	* Important terminology -- 'reaction-diffusion system'
	* Some kind of auto-catalysis is key; activator-inhibitor system
	* This is more about stationary patterns

* Belousov-Zhabotinsky reaction
	* Hard to point at one particular paper; the originals are not available online
	* Discovered by Belousov in 1959: _A periodic reaction and its mechanism_
	* Theory by Nicolis and Prigogine 1977: _Self-Organization in Nonequilibrium Systems_
		* Due to detailed balance, oscillations only possible far from equilibrium

* Kuramoto & Winfree model
	* TODO find papers!!!

## System basics

* Uhlir 1955:  _Electrolytic Shaping of Germanium and Silicon_
	* First ever paper on the reaction
	* Discovery of electropolishing

* Turner 1958: _Electropolishing Silicon in Hydrofluoric Acid Solutions_
	* _Second_ paper about the process in general
	* Already mentions oscillations

* Gerischer 1988: _Electrolytic Growth and Dissolution of Oxide Layers on Silicon in Aqueous Solutions of Fluorides_
	* Confirms the crucial role of electron holes in the reaction of illuminated n-type silicon

## Oscillation mechanism models

* Aggour 1995: _Interface condition of n-Si(111) during photocurrent oscillations in NH4F solutions_
	* _Claims that oscillations are caused by pores opening and closing

* Carstensen 1999: _A Model for Current-Voltage Oscillations at the Silicon Electrode and Comparison with Experimental Results_

* Lehmann 1996: _On the Origin of Electrochemical Oscillations at Silicon Electrodes_
	* A stress dependent transition occurs; from a flat, dense, isolating layer to a rough structure of a certain thickness. As a result, ionic permeability and the etch rate increase.

* Liu 2013: _Mechanism and dissolution rates of anodic oxide films on silicon_
	* Not about oscillations!!!
	* Rate of oxide dissolution is controlled by removal of dissolved products

* Zensen/Krischer 2014 : _A capacitance mediated positive differential resistance oscillator model for electrochemical systems involving a surface layer_:
	* Builds up on on Liu
	* Proposes a general, more theoretical model
	* Essential variables are capacitance and potential drop across the surface (oxide); variation in potential drop is caused by changing structure of the oxide.
	* Feedback loops discussed -- nice diagram

#TODO Show a CV of the model
Say which type of oxide is forming when
Actually find a citation for it, could be Juliane or sb else but better find the first result like this. Gerischer???

## Coupling mechanism

* Chazalviel 1992: _The p-Si/fluoride interface in the anodic region: damped and/or sustained oscillations_
	* External resistance means more oscillations

* Carstensen 1999: _A Model for Current-Voltage Oscillations at the Silicon Electrode and Comparison with Experimental Results_
	* Also an oscillation model, maybe should be in section above
	* He says stuff about local coupling 🤦‍♂️

* Patzauer 2017: _Autonomous Oscillations and Pattern Formation with Zero External Resistance during Silicon Electrodissolution_
	* Holes as non-local coupling

## Spatio-temporal pattern formation / self organisation

* Decroly 1982: _Birhythmicity, chaos, and other patterns of temporal self-organization in a multiply regulated biochemical system_

* Schönleber 2012: _High-Amplitude versus Low-Amplitude Current Oscillations during the Anodic Oxidation of p-Type Silicon in Fluoride Containing Electrolytes

* Tosolini 2019: _Bichaoticity induced by inherent birhythmicity during the oscillatory electrodissolution of silicon

* Wiehl 2021: _Birhythmicity, intrinsic entrainment, and minimal chimeras in an electrochemical experiment_




## Outlook?

##### Network dynamics
* Norton 2019: _Dynamics of reaction-diffusion oscillators in star and other networks with cyclic symmetries exhibiting multiple clusters_
	* network dynamics in BZ reaction -- a reaction-diffusion system
	* claims that there's no experimental studies on network dynamics

##### Phase Response Curves
* Efimov 2015: _Phase resetting for a network of oscillators via phase response curve approach_
	* It's possible to control a network if we know the PRCs of constituent oscillators


##### Frequency clusters
* when are the holes free to move?
* !!!adaptive coupling!!!; splay states; the holes are basically a hidden variable that influences the visible ones; we can't measure holes, only simulate them; holes are diffusing non-uniformly, for some reason preferring spots with high-amplitude oscillations