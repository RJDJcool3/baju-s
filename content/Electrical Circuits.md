---
title: Electrical Circuits
---

##### [[../Physics Home - Year 11|← Physics Home]]

### Static Charges
- Charge is a **property of matter**
	- It does not have a strong definition
- An **object of charge** <u>produces</u> an **electric field** around it
	- Properties of the Electric Field:
		- Extends to infinity
		- Other objects of charge experience an electric force when in the field
		- Has an electric force which decreases with distance from the object
			- This force may be <u>attractive or repulsive</u>
- *Static charge* refers to how the electric charge is not moving

#### 3 Charge States
- **2 Types of Charge**: positive and negative
	- Positive
		- e.g. protons, cations, $\alpha$, positrons
	- Negative
		- e.g. electrons, anions
	- The two types of charge behave oppositely
- **No charge/charges are balanced**: *Neutral* 
	- It itself is not a type of charge
	- e.g. neutron, neutrinos, atoms, etc.

> [!important] Law of Charges
> 
> **Opposites attract, likes repel**

### Electric Field Diagrams
- Charge is uniformly distributed around charged object
	- $\therefore$ Field lines are evenly distributed around object
	  ![[ElectricalFieldDiagrams|450]]
- Rules:
	- **Minimum of 4** field lines
		- Don't waste time with extra lines; minimise the amount you draw
		- Number of field lines indicate relative density for different objects
	- Must be an arrow going in correct direction
		- Outward for positive
		- Inward for negative
	- Lines must start/finish <u>at</u> the surface of the object
		- Lines should only touch the object, not pierce through
		- They should always come off the particle at **right angles** even if they will curve later
	- Should start/finish perpendicular to surface

#### Interactions Between 2 (or more) Charged Objects

![[InteractionsBetweenChargedObjects|800]]

- Figure 1. → positively charged object and negatively charged object
	- The electric field flows from the positive object to the negative object
	- *Note: This diagram is incorrect because the lines are not spaced evenly and they do not come off at right angles*
- Figure 2. → two objects with like charge
	- The electric fields repel each other and leave **empty space** between the objects
	- *Note: This diagram has an inaccuracy because it is missing a line from each particle (from the closest end to each other) which would curve up or down sharply*
- Figure 3. → two charged plates with opposite charge
	- The electric field flows from the positive charge plate to the negative charge plate
	- The field is curved on the edges of the plate
- Figure 4. → Charged plate and oppositely charged object
	- Electric field flows from positive object to negative plate (or vice versa)

### Transfer of Charge
- Friction will transfer $e^-$ from one surface to another
	- A **surface** with **greater affinity** for $e^-$ compared to a second surface, will **gain** $e^-$ and vice versa
		- Electron affinity is linked with **electronegativity**
- We cannot tell whether an object has gained positive or negative charge
	- We don't know which object gains/loses electrons

#### Conductors and Insulators
- Electrons are an easy particle to move, however they move in some materials more freely than others
- Materials where the electrons can move easily are called *conductors*
	- e.g. metals, water, earth
		- best conductors → good conductors
	- Conductors are good conductors of electricity
- Materials where the electrons have less free movement are called *insulators*
	- e.g. glass, rubber, plastic, cloth, wood
		- best insulators → good insulators
	- Insulators are poor conductors of electricity
		- Electrons are attracted strongly to atom's nucleus or are involved in the bonding of the substance
	- No matter how insulating a material is, it still will have some electron movement

- *Charging by induction* is where **electrons are redistributed** on an object to produce regions of different charge (i.e. an electric dipole)
	- The separation of charge is temporary and will reverse once the inducing charge is removed
		- This is similar to how temporary dipoles work (from chemistry)
	- This can be observed by using an [electroscope](https://byjus.com/physics/electroscope/)
		- An *electroscope* is a scientific tool that can detect an electric charge on a body
		- It is composed of a pair of metal leaves hanging off a vertical metal rod contained within an insulating box
		  ![[Electroscope]]
- *Charging by conduction* is when electrons are physically transferred causing loss/gain of charge
	- This loss/gain of charge is not temporary

### Coulomb's Law
- Electrostatically charged objects **exert a force** upon one another
	- We can calculate the magnitude of this force using **Coulomb’s Law**
- Coulomb's Law: $F_e = \frac{k\ \times\ q_1q_2}{r^2}$
	- $F_e$ = the **electric force** acting between the two objects of charge
		- $F_e$ is **a vector** → either is an **attractive force** or a **repulsive force**
			- Two opposite charges → attractive force (towards each other)
			- Two like charges → repulsive force (away from each other)
	- $k$ = **constant** of proportionality = $9.00 \times 10^9$
		- Measured in $N\ m^2\ C^{-2}$ → (not important)
	- $q_1$, $q_2$ = the charges on the two charged objects
		- Measured in coulombs ($C$)
	- $r$ = radius/the **distance between** the two **objects**

> [!hint]+ **Charge of Important Particles**:
> 
> - 1 **proton** = +$1.6 \times 10^{−19}\ C$
> - 1 **electron** = -$1.6 \times 10^{−19}\ C$
> - $1\ C$ = $6.2 \times 10^{18}$ protons/electrons

### Electrical Current
- A current is a charged particle/s in motion
	- When current is referred to in physics, it is referring to **conventional current**
- **Conventional current** is the flow of charge from **positive to negative**, however, **electron current** flows from **negative to positive**
	- This does not make any functional difference in electrical circuits

- When charge moves from one position to another, **work is done** on the charge
	- i.e. they have changed in their electric potential energy
	- $W = \Delta{E}$
		- Work done ($W$) measured in joules $-$ $J$
- *Voltage* is the electric force that pushes charged particles over a distance
	- $V = \frac{W}{q}$
		- $q$ = charge ($C$)
	- Voltage is measured in volts $-$ $V$ or $J\ C^{-1}$
	- If a wire connects two points directly, the voltage between those two points must be the same
		- The **last section of a circuit** must have **a voltage of zero**
			- Current adjusts to allow the voltage to always drop to zero at the end of a circuit with fixed resistance
	- A **circuit with no resistance** **will break** since there is no point in the circuit for the voltage to drop

- *Current* is the amount of charge which flows past a given point in a given unit of time (1 second)
	- $I = \frac{q}{\Delta{t}}$
		- $q$ = charge ($C$)
	- Current is measured in amps - $A$
	- Calculating energy from voltage and current → $E = VIt$

### Resistance and Ohm's Law
- *Resistance* is the measure of the difficulty with which charge moves through a medium
	- *Effective resistance* ($R_e$) is equal to total resistance
- **Ohm's Law** → $V = IR$
	- $V$ - Voltage drop over component/circuit
		- This measures the change in voltage from the section before the component to after the component
	- $I$ - Current flowing through component/circuit
	- $R$ - Resistance measured in **Ohms** $(\Omega)$
- **Parallel Circuit** Formula ($R_e$) → $\frac{1}{R_e} = \frac{1}{R_1} + \frac{1}{R_2} + \frac{1}{R_3} +\ ...$
	- For a series circuit, the effective resistance can be found by just adding up all the individual resistances
	- For complex circuits (both parallel and series components), add up all resistances in series and calculated resistance from each individual parallel circuit branch (using parallel circuit formula)
- <u>Ohmic vs Non-Ohmic Devices</u>
	- Ohmic devices have a straight line relationship between increase in voltage and increase in current
	- Non-ohmic devices have a cubic relationship (with one stationary point) between increase in voltage and increase in current
	- Example Graph:
	  ![[OhmicVsNon-Ohmic]]

### Circuits
- Electrical circuits **transform** electrical energy into other forms of <u>useful</u> energy
	- e.g. heat, light, sound
- **Minimum Components for a Circuit**:
	1. Power pack
		- i.e. source of energy/potential
	2. Wire (conducting medium)
		- Made of conductive metals
			- e.g. copper, silver, gold, platinum
	3. Devices/component/resistors
#### Series Circuits
- Series circuits have components attached in a series
- Current is the same in every part of a series circuit
	- If more components (resistors) are added, then the effective current is reduced but will still be the same everywhere
	- $I_{total} = I_1 = I_2 = I_3 = \ {...}$
- For a single component in series with the energy source, $V \propto emf$
	- If more components are added in series, then the sum of all individual voltage drops equal the total voltage drop
	- $V_{total} = V_1 + V_2 + V_3 +\ {...}$
#### Parallel Circuits
- Parallel circuits have branches
- Current is divided among components in different branches
	- $I_{total} = I_1 + I_2 + I_3 +\ {...}$
- Voltage is the same in each branch
	- $V_{total} = V_1 = V_2 = V_3 =\ {...}$
#### Circuit Components
- Circuit Diagram Symbols:
  ![[CircuitComponents|600]]
- Resistor
	- Resistors convert electrical energy to heat energy
		- Voltage falls because work is being done
	- All components in a circuit provide resistance
- Battery
	- Stores chemical energy and converts it to electrical energy
		- The chemical reactions in a battery involve the flow of electrons from one electrode to another
- Voltmeter - measures **voltage drop**/potential drop/electro motor force
	- Unit ($V$)
- Ammeter - measures current ($I$)
	- Unit ($A$) amperes
- Galvanometer - v. sensitive ammeter