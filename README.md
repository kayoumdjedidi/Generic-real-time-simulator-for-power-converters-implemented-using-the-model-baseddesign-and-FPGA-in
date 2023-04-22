# Generic-real-time-simulator-for-power-converters-implemented-using-the-model-baseddesign-and-FPGA-in

This project describes the development of a digital twin generic FPGA-based real-time simulator for power
electronics converter systems based on an efficient model-baseddesign (MBD) and FPGA-in-the-loop (FIL) workflow. The main
objective is to reproduce their static and dynamic behaviors
over a wide range of the operation frequency. In this model, the
power components such as switches, insulated gate bipolar
transistors in this case (IGBT’s) are modeled using the
associated discrete circuit (ADC) method, with both static and
dynamic behaviors. The network is computed applying the
modified nodal analysis (MNA) method, and the proposed
model is implemented on the field-programmable gate array
(FPGA) using hardware-in-the-loop (HIL) and FIL
technologies. This approach was tested on a DC-DC Boost
converter. The effectiveness and accuracy of the developed
electromagnetic transient program (EMTP) are tested in real
time using a numerical model, and then the simulator is
implemented using FIL technology. The latter is validated by
comparing the real-time simulation results with offline
simulation software. Resultant waveforms can be generated
with nanosecond resolution, across multiple topologies.
Keywords— Associated discrete model (ADC), hardware in
the loop (HIL), electromagnetic transient program (EMTP),
FPGA-in-the-loop (FIL), real-time simulation/simulators (RTS)
