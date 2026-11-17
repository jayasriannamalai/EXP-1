## EXPERIMENT NO. 1 – VERIFICATION OF KIRCHHOFF'S LAWS

| Jayasri A | | 26014582 | |
|---|---|---|---|
| 17.11.2026 | | 26ODJO84 | |

---

## AIM

a. To verify Kirchhoff's Voltage Law (KVL) for the given circuit.

b. To verify Kirchhoff's Current Law (KCL) for the given circuit.

## APPARATUS REQUIRED

| S. No. | Component | Range / Rating | Quantity |
|:---:|:---:|:---:|:---:|
| 1 | Resistor | 1 kΩ | 3 |
| 2 | DC Voltmeter | 0–30 V | 3 |
| 3 | DC Ammeter | 0–0.2 A | 3 |
| 4 | Breadboard | — | 1 |
| 5 | Regulated Power Supply (RPS) | 0–30 V | 1 |
| 6 | Connecting wires | As required | As required |
| 7 | Simulation software | Proteus Design Suite | 1 |

## THEORY

**Kirchhoff's Voltage Law (KVL):** The algebraic sum of all voltage rises and voltage drops around any closed loop in an electrical circuit is zero.

**Kirchhoff's Current Law (KCL):** The algebraic sum of currents at any node is zero. In other words, the total current entering a node is equal to the total current leaving the node.

## PROCEDURE

### A. Verification of KVL

1. Connect the circuit as shown in the KVL circuit diagram.
2. Ensure that the RPS output is set to zero volts before switching it on.
3. Check that all meters are correctly connected and set to their zero positions.
4. Switch on the RPS and gradually set the required input voltage within the specified range.
5. Measure and record the voltage across each resistor using the voltmeters.
6. Repeat the measurements for different input-voltage values and tabulate the readings.

### B. Verification of KCL

7. Connect the circuit as shown in the KCL circuit diagram.
8. Ensure that the RPS output is set to zero volts before switching it on.
9. Check that all meters are correctly connected and set to their zero positions.
10. Switch on the RPS and gradually set the required input voltage within the specified range.
11. Measure and record the current in each branch using the ammeters.
12. Repeat the measurements for different input-voltage values and tabulate the readings.

## CIRCUIT DIAGRAMS

### A. KVL circuit diagram
<img width="1487" height="1302" alt="be1" src="https://github.com/user-attachments/assets/1ead128b-fb5c-41e1-a85b-8b32ca8a39d2" />

*[ Insert the KVL circuit diagram here ]*

**Figure 1:** KVL verification circuit

### B. KCL circuit diagram
<img width="1280" height="995" alt="BE7" src="https://github.com/user-attachments/assets/5b92a9dc-146b-4443-bf15-5940a6f510a8" />

*[ Insert the KCL circuit diagram here ]*

**Figure 2:** KCL verification circuit

## SIMULATION USING PROTEUS

Build the KVL and KCL circuits in Proteus using the same resistor values and supply voltage as the hardware circuit. Place DC voltmeters and DC ammeters from the Virtual Instruments mode, run the simulation, and paste a screenshot showing the meter readings for each circuit.

### A. KVL simulation
<img width="863" height="594" alt="Screenshot (22)" src="https://github.com/user-attachments/assets/ec7da156-40fa-4337-a1ac-2075f44736e3" />


*[ Paste the Proteus KVL simulation screenshot here ]*

**Figure 3:** Proteus simulation of KVL circuit

### B. KCL simulation
<img width="856" height="376" alt="Screenshot (24)" src="https://github.com/user-attachments/assets/d8b9c36f-5ebf-486f-916b-1a82dd7d8218" />


*[ Paste the Proteus KCL simulation screenshot here ]*

**Figure 4:** Proteus simulation of KCL circuit

## OBSERVATION AND TABULATION

### A. KVL – Voltage measurements

| S. No. | Supply voltage Vs (V) | VR1 (V) | VR2 (V) | VR3 (V) | VR1 + VR2 + VR3 (V) |
|:---:|:---:|:---:|:---:|:---:|:---:|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

### B. KCL – Current measurements

| S. No. | Supply voltage Vs (V) | Total current It (A) | Branch current I1 (A) | Branch current I2 (A) | Branch current I3 (A) | I1 + I2 + I3 (A) |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 1 | | | | | | |
| 2 | | | | | | |
| 3 | | | | | | |
| 4 | | | | | | |
| 5 | | | | | | |

## CALCULATIONS

### A. KVL

According to KVL, **Vs = VR1 + VR2 + VR3**.

Substitute the observed values and verify that the algebraic sum of the voltage drops is approximately equal to the supply voltage.
<img width="1335" height="960" alt="be3" src="https://github.com/user-attachments/assets/bf9a0001-73ad-4cf5-ab16-eacaf7e67f0e" />
<img width="1463" height="1047" alt="be4" src="https://github.com/user-attachments/assets/aaabb94a-719e-4627-bf89-8c2ea43e64de" />

*[ Paste the KVL calculation screenshot here ]*

**Figure 5:** KVL calculation

### B. KCL

According to KCL, **It = I1 + I2 + I3**.

Substitute the observed values and verify that the total current entering the node is approximately equal to the sum of the branch currents.
<img width="1600" height="1128" alt="be5" src="https://github.com/user-attachments/assets/e5273c42-2ff3-4650-bf45-55845304b0bb" />
<img width="1160" height="1600" alt="be6" src="https://github.com/user-attachments/assets/42554ea3-449b-49b9-b3b1-879c1d851d51" />

*[ Paste the KCL calculation screenshot here ]*

**Figure 6:** KCL calculation

## RESULT

Thus, Kirchhoff's Voltage Law (KVL) and Kirchhoff's Current Law (KCL) were verified experimentally and through Proteus simulation for the given circuits.
