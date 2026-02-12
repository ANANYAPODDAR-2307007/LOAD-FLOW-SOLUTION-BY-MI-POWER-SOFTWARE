# LOAD-FLOW-SOLUTION-BY-MI-POWER-SOFTWARE
OBJECTIVE: To compute the voltage and phase angle (phasors) at all the busses in the system, when the terminal conditions are specified.

THEORY:
The starting point of any analysis of power system will be the computation of complex voltages at all the busses. Once the complex voltages have been computed the power coming out of a bus and the power flowing in all the transmission lines can be calculated. Load flow analysis is a computational tool for this purpose. Load flow is normally used in planning studies when a power network is being laid or when a power network is undergoing expansion.

Before we start doing load flow analysis, we need to model the entire network with all the generators, loads and transmission lines. A power network is composed of transmission lines (cables), transformers, reactors, loads and generators. A transmission line is represented by an equivalent π circuit with a series impedance (R + jX) from node i to node j.

PROCEDURE:
1. Double click on Mi power icon → power system network editor → database → configure → browse → file name → connect → ok.
2. Click on bus → choose voltage level → draw bus similarly draw required number of buses.
3. Click on transmission line → click in between two buses → draw transmission line “from bus” to “to bus”, similarly draw all required transmission line put random structure reference number → open transmission line library → give impedance value (half line charging admittance, if given).
4. Click on generator → connect with slack bus & generator bus. Give random manufacture reference number → open generator library → give MW & MVA (calculated) value.
5. Click on load → connect with load bus. Give the MW & MVA (calculated) value.
6. Solve → load flow analysis → study info (choose method) → execute → report
