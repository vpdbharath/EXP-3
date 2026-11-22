## EXPERIMENT NO. 3 – STAIRCASE WIRING

| BHARATH D | | 26018983 | |
|---|---|---|---|
| 22.11.2026 | | 26ODJ102 | |

---

## AIM

To control the status of the given lamp by using two-way switches.

## APPARATUS REQUIRED

| S. No. | Name of the apparatus | Range / Type | Quantity |
|:---:|:---:|:---:|:---:|
| 1 | Incandescent lamp | 60 W | 1 No. |
| 2 | Lamp holder | Pendant type | 1 No. |
| 3 | SPDT switch | 230 V, 5 A | 2 Nos. |
| 4 | Wires | 1/18" | As required |
| 5 | PVC pipe | 1/4" | As required |
| 6 | Wooden board | — | 1 No. |
| 7 | Round block | — | 1 No. |
| 8 | Simulation software | Proteus Design Suite | 1 |

## THEORY

- A two-way switch is installed near the first step of the stairs. The other two-way switch is installed at the upper part where the stairs end.
- The light point is provided between the first and last stair at an adequate location and height. If the light is switched on by the lower switch, it can be switched off by the switch at the top, or vice versa.
- The circuit can also be used in places like a bedroom, where the person need not walk back to the place from where the light was switched on in order to switch it off.
- Two numbers of two-way switches are used for this purpose. The supply is given to the switch at the short-circuited (common) terminal.
- The connection to the light point is taken from the similar short-circuited (common) terminal of the second switch. The other two independent terminals of each switch are connected through cables.

## PROCEDURE

1. Place the accessories on the wiring board as per the circuit diagram.
2. Place the PVC pipe and insert two wires into the PVC pipe.
3. Take one wire; connect one end to the phase side and the other end to the middle (common) point of SPDT switch 1.
4. The upper point of SPDT switch 1 is connected to the lower point of SPDT switch 2.
5. The lower point of SPDT switch 1 is connected to the upper point of SPDT switch 2.
6. Another wire is taken through the PVC pipe, and the middle (common) point of SPDT switch 2 is connected to one end of the lamp holder.
7. The other end of the lamp holder is connected to the neutral line.
8. Screw the accessories on the board and switch on the supply.
9. Test the circuit for all possible combinations of switch positions.

## A. DIRECT CONNECTION

### Circuit diagram
<img width="1280" height="798" alt="image" src="https://github.com/user-attachments/assets/18fce77d-0eb0-4852-95bb-b0e8cc9435c0" />

*[ Insert the direct connection circuit diagram here ]*

**Figure 1:** Staircase wiring – direct connection

### Tabulation 1: Truth table – direct connection
<img width="1280" height="905" alt="image" src="https://github.com/user-attachments/assets/195d890f-7d26-476b-9952-0db551e425b2" />

*Enter the switch position as UP / DOWN (or 1 / 0) and the lamp status as ON / OFF for each combination.*


## B. CROSS CONNECTION

### Circuit diagram
<img width="1280" height="740" alt="image" src="https://github.com/user-attachments/assets/42d6ea5b-4fe5-4b18-9d7b-132ecd31452f" />

*[ Insert the cross connection circuit diagram here ]*

**Figure 2:** Staircase wiring – cross connection

### Tabulation 2: Truth table – cross connection

*Enter the switch position as UP / DOWN (or 1 / 0) and the lamp status as ON / OFF for each combination.*
<img width="1280" height="1072" alt="image" src="https://github.com/user-attachments/assets/a2b25c0f-49de-49f8-9641-52f3fc26fe2a" />


## SIMULATION USING PROTEUS

Build both the direct and cross connection circuits in Proteus using an AC source, two SPDT switches and a lamp. Run the simulation for each switch combination and paste screenshots showing the lamp ON and OFF states.

### A. Direct connection – simulation
<img width="1253" height="739" alt="image" src="https://github.com/user-attachments/assets/4b272fa4-5d36-4c66-a782-e169d606c961" />

*[ Paste the Proteus direct connection simulation screenshot here ]*

**Figure 3:** Proteus simulation – direct connection

### B. Cross connection – simulation
<img width="1199" height="713" alt="image" src="https://github.com/user-attachments/assets/3841d0b7-0c2e-400c-b886-1bf904788c03" />

*[ Paste the Proteus cross connection simulation screenshot here ]*

**Figure 4:** Proteus simulation – cross connection

## RESULT

Thus, the staircase wiring was connected and tested for both direct and cross connections, and the lamp was controlled from two different places using two-way switches.
