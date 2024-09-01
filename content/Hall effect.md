### Hall effect

- **Definition**: The generation of a transverse voltage in a conductor through which an electric current is flowing when it is placed in a perpendicular magnetic field.

- **Key concepts**:
	- **Lorentz force**: $F = q(\textbf{v} \times \textbf{B})$ describes the transverse force charge carriers in the current experience under a perpendicular magnetic field. 
	  
	- **Hall voltage**: Charge carriers are pushed via the Lorentz force until an equilibrium is established in which the electric field balances out the magnetic force. This field can be described by the Hall voltage $V_H$ across the width of the conductor.
	  
	- **Hall resistivity**: Expressed as $R_H$$, it expresses the transverse electric field per unit current density and magnetic field and provides a way to understand the Hall effect in terms of material properties.

#### Mathematical Description

1. **Hall electric field** $E_H$: At equilibrium, the electric force $qE_H$ balances the Lorentz force $qvB$. Thus, $E_H = vB.$

2. **Hall voltage** $V_H$: The voltage across the width $w$ of the conductor is $$V_H = E_Hw = vBw.$$Since the current $I$ is related to the current density $J$ and the carrier density $n$ by $I = nqvA$ where $A$ is the cross sectional area, we can write $$v = \cfrac{I}{nqA}.$$
3. **Hall resistivity** $R_H$: The Hall resistivity is defined as $$R_H = \cfrac{E_H}{JB}$$Substituting $J = \cfrac{I}{wt}$ where $t$ is the thickness of the conductor, we get $$R_H = \cfrac{E_H}{JB} = \cfrac{V_H/w}{IB/wt} = \cfrac{V_Ht}{IB} = \cfrac{(vBw)t}{(vnqwt)B} = \cfrac{1}{nq}.$$
#### Intuition

1. **Charge Carrier Density**: The Hall resistivity is inversely proportional to the charge carrier density $n$. A higher carrier density means more charges are available to balance the Lorentz force (and the charges are traveling slower for a given $I$), resulting in a smaller Hall voltage for a given current and magnetic field. 

2. **Material Properties**: Hall resistivity encapsulates how a material responds to an applied magnetic field in terms of it electronic structure. Different materials will have different Hall resistivities based on their in