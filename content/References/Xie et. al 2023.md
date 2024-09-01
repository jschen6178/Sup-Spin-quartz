# Visualization of skyrmion-superconducting vortex pairs in a chiral magnet-superconductor heterostructure

### Abstract
>Magnetic skyrmions, the topological states possessing chiral magnetic structure with non-trivial topology, have been widely investigated as a promising candidate for spintronic devices. They can also couple with superconducting vortices to form skyrmion-vortex pairs, hosting Majorana zero mode which is a potential candidate for topological quantum computing. A lot of theoretical proposals have been put forward on constructing skyrmion-vortex pairs in heterostructures of chiral magnet and superconductor. Nevertheless, how to generate skyrmion-vortex pairs in a controllable way experimentally remains a significant challenge. We have designed a heterostructure of chiral magnet and superconductor $[CoFeB/Ir/Ta]7/Nb$ in which zero field Neel-type 1skyrmions can be stabilized and the superconducting vortices can couple with the skyrmions when Nb is in the superconducting state. We have directly observed the formation of skyrmion-superconducting vortex pairs which is dependent on the direction of the applied magnetic field. Our results provide an effective method to manipulate the quantum states of skyrmions with the help of superconducting vortices, which can be used to explore the possible existence of Majorana zero mode for future quantum computation.

### Background
- Skyrmions in the past are stabilized at relatively high fields, vortex-vortex interaction is therefore non-negligible and the existence of *individual* SVPs is still dubious. 
### Methodology
##### MIS heterostructure
- $[\text{CoFeB(1.1)/Ir(2)/Ta(1)}]_7/\text{Nb(60)}$ on $\text{Si}$ substrate. Neel skyrmions stable at zero field. Separated by $2\text{nm}$ $\text{MgO}$. $T_c \sim 8.98 \text{K}$. 

##### Zero-field skyrmions
- Sweep magnetic field from zero to $1750 \text{Oe}$, then back to zero. Image below of MFM.
![[Pasted image 20240814170026.png|400]]
- Typical skyrmion radius $r_{\text{sk}} = 95 \pm 6 \text{nm}$ at $T = 10\text{K}$. 
##### Direct visualization of SVPs
- After zero-field skyrmions are stable at $10\text{K}$, the sample is field cooled to $5\text{K}$. 
- Fields applied: $-3\ \text{Oe}, 2\ \text{Oe}, 0\ \text{Oe}$.
### Results
- Formation of SVP "directly" observed via MFM.
- When negative H field is applied, vortices prefer to be at center of skyrmions, forming SVPs with enlarged radius. 
- In positive field, vortices are expelled away from skyrmions. 
- Main claim is that the enlargement of the SVP in MFM indicates a vortex was pinned at the center of a skyrmion.
![[Pasted image 20240814171057.png|400]]
- Green squares (red circles) indicate vortices induced by skyrmions at center-to-center distance $a=0$ ($a >0). 

### Numerical simulation
- Used boundary-restrained Maxwell-London equation to calculate the interaction force between skyrmion and superconducting vortex. 
- Noted again that SVPs tend to be formed on skyrmions with larger radius. 
- Mathematically, can describe the domain wall as $\theta(a) = 2\arctan(w)/\sinh(ar_{\text{sk}}/w)$ where $\theta$ denotes the skyrmion angle, and $w$ is the ratio of the size of the skyrmion to the domain wall itself. 
- For large $w = 12$, the interaction force keeps attractive over a long range, and interaction energy increases monotonically with center-to-center distance $a$. So, interaction energy reaches minimum at $a=0$. 
- However, when $w=1$, the interaction force is repulsive close to 0, and then becomes attractive after a specified distance (calculated to be about $3$ times the actual skyrmion radius!)
- Caveat: large winding number skyrmions are not realistic in a chiral magnet.