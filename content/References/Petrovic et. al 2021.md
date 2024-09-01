## Skyrmion-(Anti)Vortex Coupling in a Chiral Magnet-Superconductor Heterostructure

### Abstract
>We report experimental coupling of chiral magnetism and superconductivity in ½IrFeCoPt=Nb heterostructures. The stray field of skyrmions with radius ≈50 nm is sufficient to nucleate antivortices in a 25 nm Nb film, with unique signatures in the magnetization, critical current, and flux dynamics, corroborated via simulations. We also detect a thermally tunable Rashba-Edelstein exchange coupling in the isolated skyrmion phase. This realization of a strongly interacting skyrmion-(anti)vortex system opens a path toward controllable topological hybrid materials, unattainable to date.

### Background
- **Rashba-Edelstein effect** or **Exchange coupling**: Skyrmion exchange field + interfacial SOC induce circulating spin-polarized supercurrents, which interfere with vortex currents. Requires contact between SC and magnet, dependent on sign/magnitude of SOC and exchange field. This effect is most pronounced when Rashba-Edelstein and (anti)vortex currents circulate around the same radii.
- **Stray field coupling**: Allows skyrmion-vortex interaction without electronic contact at distances greater than exchange length. Sign and magnitude of this interaction is determined by *current profile induced in superconductor*, which depends on the **thickness of the magnetic layer, skyrmion chirality, and skyrmion-vortex separation.**
- Postulate - although skyrmions have opposite field to the applied field and thereby would repel vortices, sufficiently large skyrmions could **nucleate antivortices**. 
- Stray field coupling is enhanced by increasing skyrmion size. This makes sense because a larger skyrmion may just provide more flux to penetrate the SC.

### Motivation
- **Novel hybrid behavior**: Skyrmion-vortex pairing in heterostructures is a method of coupling chiral magnetism and superconductivity that can deliver novel hybrid behavior. 
- Before, skyrmions were only stable at low temperatures when the field was above 1 Tesla, which is higher than most $H_{c2}$ in superconductors. But, with IrFeCoPt, the applied field is now low enough to form skyrmions without necessarily inducing vortices in the superconductor.

### Methodology
##### Heterostructure design
- MS (chiral magnet + superconductor): $[\text{Ir}_1\text{Fe}_{0.5}\text{Co}_{0.5}\text{Pt}_1]^{10}$ with Nb deposited on top (thickness of Nb is optimized later). 
- Insulating layer of 5nm MgO optionally inserted to suppress exchange coupling.
##### Magnetic layer
- Field sweep shows skyrmion formation at various fields. Why is there asymmetry?
- Looks like optimal nucleation occurs at around 125mT.
![[Pasted image 20240814112819.png|400]]
##### Superconducting layer
 - $T_c = 6.05 \text{K}$. Choose thickness of $25 \text{nm}$ to get a pearl depth $\Lambda = \cfrac{\lambda^2}{d_s} = 200\text{nm}$. $H_{c1} = 12mT$.
 - Measuring [[Zero-bias conductance]] suggests coherence length $\xi_{\text{eff}}(0.4\text{K}) \approx 36\text{nm}$, which exceeds the theoretically predicted $10\text{nm}$ from GL. Reason because of Pt contact with Nb. 
### Results

##### Antivortices induced by skyrmions
- Isolate the magnetization of the superconductor and track evolution from applied field. The dip in MS is more pronounced than the dip in MIS.
- **Claim** is that the dip indicates ejection of vortices (that have $m>0$) and formation of antivortices ($m<0$) 
![[Pasted image 20240814130146.png|400]]
- Vortex formation via skyrmions is more difficult than typical SC-FM hybrids because $r_{\text{sk}}$ is smaller than magnetic domains. Assuming $m_z \sim tanh[\pi(r-r_{\text{sk}})/r_{\text{sk}}]$, can integrate and show that there is an upper limit of flux from $50\text{nm}$ Neel skyrmions of $4.44 \Phi_0$. 
- Zero-field skyrmions demand a $M_s \geq \Phi_0 \ln(\Lambda/\xi)/(0.86\pi^2d_mr_{\text{sk}})$ for anti-vortex formation. Derivation in [[Dahir 2019]]. Can use Mumax/GL to check this.
- (d) shows the combined simulation they used. (e) and (f) show the antivortices forming. (g)  indicates how the number of antivortices increase as applied field goes down. 
![[Pasted image 20240814153715.png|400]]
- "Raising temperature increases the number of antivortices produced since $H_{c1}$ drops." Does not seem true in the inset diagram.
![[Pasted image 20240814154452.png|400]] 
- Primary evidence for antivortex nucleation is the drop in magnetization? How do they exactly calculate $N_{AVx}$ ? Seems non-trivial, especially without direct imaging techniques.

##### Skyrmion impact on vortex dynamics
- Critical current density $J_c(H)$ is higher in MS and MIS heterostructures compared to a bare Nb film. Can test this in TDGL.
- Vortices are typically repelled by skyrmion screening currents, but the formation of an AV reduces the ?barrier height?, enabling vortices to cross the skyrmion/stripe. See diagram. Really should test this in PyTDGL. 
![[Pasted image 20240814155707.png|400]]
- $J_c$ is actually lower in MS samples compared to MIS samples. But $N_{AVx}$ was higher in MS compared to MIS. So what's up with that?
##### Skyrmion-vortex exchange coupling
- Magnetization of the SC responds to skyrmion formation at $20\text{mT}$ higher field compared to MIS. Similarly observed in critical current.
- Attribute this to the exchange coupling assisting antivortex creation at high fields, by inducing supercurrents rotating in the same sense as antivortex currents.
- This only works at low temperatures when $r_{\text{sk}}$ is comparable to $\xi_\text{eff}$ . 