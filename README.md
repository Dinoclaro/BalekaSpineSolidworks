# Baleka Spine CAD Model

This repository contains the SolidWorks CAD model for the **Baleka Spine**.  
It is based on a modified version of the **Baleka 2.5 CAD** model, adapted for compatibility with both the new **three-degree-of-freedom (DoF) spine** and the existing **AeroDima tail**.

The Baleka Spine was developed to create a half-cheetah robotic model for studying the effect of the tail on the hindquarters during specific motions such as rapid turns. The spine integrates **three Steadywin GIM8115-6 motors** using MIT control to provide independent **roll**, **pitch**, and **yaw** actuation.  

The system is operated via **MATLAB Simulink Real-Time** on a **SpeedGoat** target computer.  

The design was created using **SolidWorks 2024 Student Edition**.  
All design calculations and resources are stored in the **BalekaSpine** folder within the NAS file system.

*Updated by Dino Claro ([clarodino@icloud.com](mailto:clarodino@icloud.com))*



## Manufacturing

- **Sheet metal parts**: Can be manufactured at Vulcan or Fabrinox. Specify required surface finishes and critical dimensions. The latest Baleka Spine assembly was manufactured at Vulcan.
- **Machined parts**: Can be produced at the Mechanical Engineering workshop.
- Refer to the **BOM** for a complete list of parts to be manufactured, 3D printed, or ordered.



## Assembly

- Refer to the **assembly instructions** doc.



## Shopping List

### 3-DOF Spine

| Part Number                                | Description                                                    | QTY | Supplier            |
|--------------------------------------------|----------------------------------------------------------------|-----|---------------------|
| BLKS-S001                                  | Heim Rod Turnbuckle                                            | 2   | Experimental Space  |
| Coiled Spring Pin Metric HD-4x35-St        | Coiled Spring Pin, Heavy Duty, 4 mm × 35 mm, Steel             | 3   | Topfast             |
| skf_bearing_6002-2rsh_2_01                 | SKF 6002-2RSH Deep Groove Ball Bearing                         | 3   | BMG                 |
| a_15_unstressed                            | 15 mm External Circlip                                         | 2   | BMG                 |
| skf_bearing_6001-2rsh_2_01                 | SKF 6001-2RSH Deep Groove Ball Bearing                         | 2   | BMG                 |
| B18.3.1M - 4 x 0.7 x 12 Hex SHCS -- 12NHX   | M4 × 12 mm Hex Socket Head Cap Screw                           | 24  | Topfast             |
| B18.3.4M - 4 x 0.7 x 8 SBHCS --N            | M4 × 8 mm Socket Button Head Cap Screw                         | 24  | Topfast             |
| AM-M4-N                                    | M4 Nyloc Nut                                                   | 38  | Topfast             |
| SHS4-8                                     | Socket Head Shoulder Screw                                     | 6   | Topfast             |
| Coiled Spring Pin Metric HD-3x28-St        | Coiled Spring Pin, Heavy Duty, 3 mm × 28 mm, Steel             | 1   | Topfast             |
| B18.3.1M - 4 x 0.7 x 30 Hex SHCS -- 20NHX   | M4 × 30 mm Hex Socket Head Cap Screw                           | 6   | Topfast             |
| skf_bearing_6003-2rsh_2_01                 | SKF 6003-2RSH Deep Groove Ball Bearing                         | 1   | BMG                 |
| B18.3.4M - 4 x 0.7 x 16 SBHCS --N           | M4 × 16 mm Socket Button Head Cap Screw                        | 3   | Topfast             |
| B18.3.1M - 4 x 0.7 x 35 Hex SHCS -- 20NHX   | M4 × 35 mm Hex Socket Head Cap Screw                           | 8   | Topfast             |
| a_17_unstressed                            | 17 mm External Circlip                                         | 1   | BMG                 |
| skf_bearing_6000-2rsh_2_01                 | SKF 6000-2RSH Deep Groove Ball Bearing                         | 2   | BMG                 |
| a_10_unstressed                            | 10 mm External Circlip                                         | 2   | BMG                 |
| B18.3.1M - 4 x 0.7 x 20 Hex SHCS -- 20NHX   | M4 × 20 mm Hex Socket Head Cap Screw                           | 3   | Topfast             |
| PHS 5 Body                                 | PHS5 Female Rod End Bearing Body                               | 4   | BMG                 |
| B18.3.1M - 5 x 0.8 x 20 Hex SHCS -- 20NHX   | M5 × 20 mm Hex Socket Head Cap Screw                           | 4   | Topfast             |
| 2020 V-Slot 3mtr Black                     | 20 × 20 mm Aluminium V-Slot Extrusion, 3 m, Black Anodised     | 4   | Moduasm             |
| T NUT PG15 PG20                            | T-Nut for 20 × 20 mm Extrusion Profile                         | 2   | Moduasm             |

---

## References

1. D. Bright, S. Shield, and A. Patel, "AeroDima: Cheetah-Inspired Aerodynamic Tail Design for Rapid Maneuverability," *2024 IEEE International Conference on Robotics and Automation (ICRA)*, Yokohama, Japan, 2024, pp. 1451–1456. [doi:10.1109/ICRA57147.2024.10610202](https://ieeexplore.ieee.org/document/10610202)  
2. C. Fischer, A. Blom, and A. Patel, “Baleka: A Bipedal Robot for Studying Rapid Maneuverability,” *Frontiers in Mechanical Engineering*, 2020. [doi:10.3389/fmech.2020.00054](https://www.frontiersin.org/articles/10.3389/fmech.2020.00054/full)  
