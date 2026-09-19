# exp_5_study_characteriztion_of_e_plane

# Experiment 5 — Study and Characterization of E-Plane Tee

---

## Aim

To study and measure the characteristics of an E-plane tee.

## Apparatus Used

Klystron power supply, klystron mount with tube, isolator, variable attenuator, frequency meter, slotted line section, E-plane tee, detector mount / crystal detector, matched terminations, VSWR meter, waveguide stands.

## Experimental Setup

<img width="744" height="484" alt="image" src="https://github.com/user-attachments/assets/ea65ce6c-aced-4c5f-9f66-a6fcb5daff1b" />



---

## Theory

In an E-plane tee an auxiliary waveguide arm is fastened to the **broader wall** of the main guide. It is a three-port device in which the axis of the auxiliary arm is parallel to the plane of the electric field of the main guide, and the coupling from the main guide to the auxiliary guide is by means of **electric fields** — hence the name E-plane tee.

The junction causes the loads connected to its branches to appear **in series**, so it is often referred to as a **series tee**.

The two main-guide arms are symmetrical with respect to the auxiliary arm. If power is fed from the auxiliary arm it is distributed equally into arms 1 and 2 when they are terminated in equal loads. However, from the field configuration, the power flowing out of arm 1 is **180° out of phase** with that in arm 2. The E-plane tee therefore acts as a **subtractor (differencer)**.

### Summary of behaviour

| Feed point | Result |
|---|---|
| Auxiliary (E) arm | Equal split into arms 1 and 2, 180° out of phase |
| Arms 1 and 2 (equal, in phase) | Signals subtract at the E-arm |
| Function | Subtractor / differencer, series tee |

---

## Procedure

1. Set up the microwave bench: klystron power supply → klystron mount → isolator → variable attenuator → frequency meter → slotted section → component under test (E-plane tee) → detector mount → VSWR meter.
2. Keep the control knobs of the klystron power supply at their initial settings (mode switch: AM; beam voltage knob: fully anti-clockwise; repeller voltage knob: fully clockwise; meter switch: beam current) and switch on the supply, the VSWR meter and the cooling fan.
3. Energise the klystron for maximum output at the desired frequency by adjusting the beam and repeller voltages; measure the operating frequency with the frequency meter and then detune it.
4. **Reference reading:** without the E-plane tee in the line, set the variable attenuator to obtain a convenient full-scale reference reading on the VSWR meter. Note the attenuator setting **A₁** dB.
5. **Insert the component:** connect the E-plane tee in the line, feeding the arm under test and terminating the remaining arms in matched loads.
6. Reduce the attenuation until the VSWR meter reads the same reference value. Note the attenuator setting **A₂** dB. The difference (A₁ − A₂) dB gives the coupling/isolation for that pair of ports.
7. **Power division:** feed the E-arm, terminate one collinear arm in a matched load and measure the power at the other collinear arm; repeat with the arms interchanged. The measured coupling should be about **3 dB** for each collinear arm.
8. **Isolation:** feed the E-arm and measure the power coupled to the isolated port, with all other ports match-terminated.
9. **VSWR of each port:** feed the port under test, terminate the remaining ports in matched loads, and measure the VSWR using the slotted line.
10. Repeat the measurements for each of the three ports.

---

## Observation

<img width="900" height="1600" alt="image" src="https://github.com/user-attachments/assets/f0b5295e-333a-4e8c-93f7-86369cab3906" />




---

## Precautions

* Check all connections before switching on the kit.
* Keep all knobs at minimum before switching on the power supplies; the HT must be OFF while switching on the mains.
* Do not exceed a beam current of 30 mA, and keep the repeller voltage within the specified range.
* Terminate all unused ports in matched loads while taking readings.
* Do not look directly into an open waveguide.

## Result

The characteristics of the E-plane tee were studied.
