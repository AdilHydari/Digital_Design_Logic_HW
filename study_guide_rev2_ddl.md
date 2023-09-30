
# Electronic Components and Electricity Fundamentals

## Section 1: Electronic Components Overview

### 1.1 Introduction to Electronic Components

- **Objective**: Understand the importance of studying electronic components.
- **Content**:
  - Explanation of the significance of electronic components in electrical engineering.
  - Highlighted components: Resistor, Capacitor, Inductor, Electrolytic Capacitor.

### 1.2 Basic Units

- **Objective**: Familiarize with fundamental units and their symbols in electronics.
- **Content**:
  - Definitions and symbols of key units: Voltage (V), Current (Amps), Resistance (Ohms), Capacitance (Farads), Inductance (Henry).

### 1.3 Prefixes for Measurement

- **Objective**: Learn how measurement prefixes apply to electronic units.
- **Content**:
  - Explanation of prefixes such as kilo, mega, micro, nano, and their application in electronic measurements.

### 1.4 Important Equations

- **Objective**: Grasp essential equations related to electronic components.
- **Content**:
  - Formulas for voltage across a resistor and power dissipation in a resistor.

## Key Terms

| Term                       | Definition                                      |
|----------------------------|-------------------------------------------------|
| Voltage (V)                 | Electrical potential difference.                |
| Current (Amps)              | Flow of electric charge per unit time.         |
| Resistance (Ohms)           | Opposition to the flow of electric current.    |
| Capacitance (Farads)        | Ability to store electric charge.              |
| Inductance (Henry)          | Property of an inductor to store energy.       |
| Prefixes (k, M, G, T, m, μ, n, p) | Multipliers for measurement units.        |
| Power Dissipation           | Rate at which energy is converted into heat.   |


## Section 2: Electrical Energy

### 2.1 Understanding Electrical Energy

- **Objective**: Relate electrical energy in mathimatical form.
- **Content**:
  - Equations for Voltage, Impedance, Capacitance, Power, Resistance, and Inductance.
    - Voltage = (Current * Resistance)
    - Voltage = Inductance*(di/dv)
    - Current = Capacitance*(dv/dt)
    - Power = Voltage * Current
    - Impedance = Voltage / Current

## Key Terms

| Term                | Definition                                       |
|---------------------|--------------------------------------------------|
| Electrical Energy   | Energy carried by electrical currents.           |
| Voltage             | Difference in electrical potential.              |
| Current             | Flow of electrical charge.                       |
| Resistance          | Resistance of a circuit.                         |
| Capacitance         | Capacity of a circuit.                           |
| Inductance          | Inductive reactance of a circuit.                |
| Power               | Rate of energy transfer.                         |
| Impedance           | Ratio of voltage to current.                     |
| Current             | Flow of electric charge in a circuit.            |

## Section 3: Logic Elements and Logic Gates

### 3.1 Introduction to Logic Gates

- **Objective**: Gain an understanding of logic gates and their applications.
- **Content**:
  - Overview of logic gates as electronic devices performing logical operations.
  - Introduction to 74LS series chips and their specific functions.

### 3.2 Logic Elements

- **Objective**: Learn about the power requirements for logic gates.
- **Content**:
  - Logic Elements and thier schematics.
  - Logic Elements and their applications. 

### Some Examples of Logic Gates
![74LS32](https://github.com/AdilHydari/Digital_Design_Logic_HW/blob/master/image_source/74ls32.png?raw=true)
*The 74LS32 is a Dual Input OR Gate with a quad 2-input pins. It contains four independent gates each of which performs the logic OR function.*

### All basic/crucial logic elements
![Resistor](https://github.com/AdilHydari/Digital_Design_Logic_HW/blob/master/image_source/Resistor_Kicad.png?raw=true)
*This resistor is the international symbol (IEC 60617). A resistor is an electronic component that limits the flow of electrical current in a circuit. It's measured in ohms (Ω) and is essential for controlling current, voltage division, and various functions in electronics.*

![Capacitor](https://github.com/AdilHydari/Digital_Design_Logic_HW/blob/master/image_source/Capacitor.png?raw=true)
*A capacitor is an electronic component that stores and releases electrical energy. It consists of two conductive plates separated by an insulating material called a dielectric. Capacitors are used in various applications to store charge, filter signals, and control electrical circuits.*

![Diode](https://github.com/AdilHydari/Digital_Design_Logic_HW/blob/master/image_source/Diode.png?raw=true)
*A diode is a semiconductor device that allows electric current to flow in one direction while blocking it in the other. It is used in electronics for tasks like converting AC to DC, voltage regulation, signal clipping, and protection against reverse current or voltage.*

![Op-Amp](https://github.com/AdilHydari/Digital_Design_Logic_HW/blob/master/image_source/op_amp.png?raw=true)
*Op-amps are high-gain DC amplifiers that magnify the voltage difference between their inputs. Their output voltage is significantly larger than the input. Op-amps find extensive use in analog electronics for tasks such as voltage amplification, signal filtering, and performing mathematical operations like addition and subtraction and prove to be fundemental building blocks for digital logic.*

![Transistor](https://github.com/AdilHydari/Digital_Design_Logic_HW/blob/master/image_source/Dual_NMOS_transistor.png?raw=true)
*An NMOS (N-channel Metal-Oxide-Semiconductor) transistor is a semiconductor device that controls the flow of electrical current in electronic circuits. Applying a voltage to the gate terminal allows or blocks the flow of current between the source and drain terminals. It is negatively charged.*

![Transistor](https://github.com/AdilHydari/Digital_Design_Logic_HW/blob/master/image_source/PMOS_transistor.png?raw=true)
*A PMOS (P-channel Metal-Oxide-Semiconductor) transistor is a semiconductor device used in electronics. It controls electrical current flow based on the voltage applied to its gate. It is positively charged.*
<p align="center">
  <img src="https://github.com/AdilHydari/Digital_Design_Logic_HW/blob/master/image_source/PNP_transistor.png?raw=true" />
</p>

*When a positive voltage is applied to its base terminal, it allows current to flow from its emitter to collector terminals. PNP transistors are used in amplifiers, switches, and logic circuits.*

![Transistor](https://github.com/AdilHydari/Digital_Design_Logic_HW/blob/master/image_source/NPN_Transistor.png?raw=true)
*When a small current is applied to the base terminal (usually with a positive voltage relative to the emitter), it allows a larger current to flow from the emitter to the collector. NPN transistors are commonly used in amplifiers, switches, and digital logic circuits.*

![Transistor](https://github.com/AdilHydari/Digital_Design_Logic_HW/blob/master/image_source/BJT_transistor.png?raw=true)
*Another form of a BJT transistor, in its negative form.*

![LED](https://github.com/AdilHydari/Digital_Design_Logic_HW/blob/master/image_source/LED.png?raw=true)
*In logic circuits, LEDs are primarily used for visual indication. They represent logic states (0 or 1), display gate outputs, signal errors, aid in debugging, show timing, and serve as user interface elements or light sources for data communication. In its simplest form, it is often used in homebrewed 8-bit or 4-bit computers to represent register shifts (shifts in logic at a defined memory address).* 
**Check out Ben Eater!** ![Ben Eater](https://www.youtube.com/watch?v=HyznrdDSSGM&list=PLowKtXNTBypGqImE405J2565dvjafglHU)


## Key Terms

| Term                 | Definition                               |
|----------------------|------------------------------------------|
| Logic Gates          | Electronic devices performing logical operations. |
| 74LS Series Chips    | Series of logic chips with specific functions.   |
| Vcc                  | Supply voltage for logic gates.                |
| Ground               | Reference point for voltage in circuits.       |
| Input                | Signal that is sent to a logic gate.            |
| Output               | Signal that is received from a logic gate.      |
| Logic                | The process of performing logical operations.   |

# More Specific logic gates are in the other markdown found here! 
![More Logic!](https://github.com/AdilHydari/Digital_Design_Logic_HW/blob/master/logic_gates_galore.md)
