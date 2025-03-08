# Buck Converter Simulation

This repository contains a **Buck Converter Simulink Model** designed for DC-DC step-down conversion. The model demonstrates open-loop PWM switching and can be extended with closed-loop control for voltage regulation.

## Model Description
The **Buck Converter** operates by switching an ideal transistor to step down the input voltage to a desired lower voltage. 

### Components Used:
- **Pulse Generator**: Generates PWM signals.
- **Ideal Switch**: Acts as a transistor (MOSFET or similar).
- **Inductor (L)**: Stores and releases energy.
- **Diode**: Provides a path for current when the switch is off.
- **Capacitor (C)**: Smoothens output voltage.
- **Resistor (R)**: Represents the load.
- **Scope**: Monitors the voltage and current waveforms.
- **Powergui**: Required for Simulink power simulations. It allows switching between **Continuous Mode** and **Discrete Mode** for different simulation approaches.

## Simulation
1. Open `BUCK.slx` in Simulink.
2. Run the simulation.
3. Observe the output voltage and inductor current on the scope.

## Future Enhancements
- **Closed-loop control**: Implement PID control for regulated output voltage.
- **MOSFET-based switching**: Replace the ideal switch with a real MOSFET model.
- **Efficiency analysis**: Evaluate power loss and optimize the design.

## How to Contribute
Feel free to fork this repository, modify the model, and submit pull requests with improvements.

## License
This project is licensed under the MIT License.

