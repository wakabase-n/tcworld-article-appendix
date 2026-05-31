
# Appendix C: iiRDS-Compliant Structured Data (V1)

Markdown

```
# Chunk Data

Identity: Topic-001
TopicType: iirds:GenericConcept
ProductVariant: SP-X100, SP-X200
**[Maintenance Overview]**
For the Smart Pump SP-X Series, the filter element is the most critical component for maintaining product performance. If the filter becomes clogged, it may cause a drop in discharge pressure or an overload on the motor.
Therefore, the recommended replacement interval is either when the cumulative operating time reaches 500 hours or when the differential pressure gauge reading exceeds 0.2 MPa, whichever comes first. Regular replacement extends the lifespan of the pump and prevents sudden failures.

Identity: Topic-002
TopicType: iirds:GenericTask
InformationSubject: iirds:GenericSafety
ProductVariant: SP-X100, SP-X200
**[Safety Precautions (Common)]**
**Warning**
* **Risk of Electric Shock:** Before starting work, you must turn off the main power and unplug the power plug from the outlet.
* **Residual Pressure:** High pressure may remain inside the pump. Consequently, you must open the drain valve and confirm that the pressure is completely released before performing any work.

Identity: Topic-003
TopicType: iirds:GenericTask
InformationSubject: iirds:GenericSafety
ProductVariant: SP-X200
**[Safety Precautions (SP-X200 Only)]**
**Caution**
* **Risk of Chemical Burns:** If you are using the Chemical-Resistant Model (SP-X200), dangerous chemical liquids may remain inside. You must wear chemical-resistant gloves and protective goggles to prevent adhesion to the skin.

Identity: Topic-004
TopicType: iirds:GenericTask
InformationSubject: iirds:GenericTechnicalData
ProductVariant: SP-X100
**[Required Tools and Preparation (SP-X100)]**
You require the following tools and replacement parts for this task. Prepare them before starting the work.

| Item Name | Specification / Part Number | Remarks |
| :--- | :--- | :--- |
| Replacement Filter | FLT-X100 (Standard) | Prepare the one matching your model. |
| O-ring | OR-S25 | Replace with a new one. |
| Hex Wrench | 5mm | For fixing the housing. |
| Torque Wrench | Setting range 10-20 N・m | For tightening management. |

Identity: Topic-005
TopicType: iirds:GenericTask
InformationSubject: iirds:GenericTechnicalData
ProductVariant: SP-X200
**[Required Tools and Preparation (SP-X200)]**
You require the following tools and replacement parts for this task. Prepare them before starting the work.

| Item Name | Specification / Part Number | Remarks |
| :--- | :--- | :--- |
| Replacement Filter | FLT-X200 (Chemical-Resistant) | Prepare the one matching your model. |
| O-ring | OR-S25 | Replace with a new one. |
| Hex Wrench | 5mm | For fixing the housing. |
| Torque Wrench | Setting range 10-20 N・m | For tightening management. |
| Ceramic Spanner | SP-TOOL-01 | For removing the housing and filter. |

Identity: Topic-006
TopicType: iirds:GenericTask
InformationSubject: iirds:GenericTechnicalData
ProductVariant: SP-X100
**[Filter Element Replacement Procedure (SP-X100)]**
Follow the procedure below to perform the replacement.
1. **Removing the Housing:** Using a 5mm hex wrench, loosen the four bolts at the bottom of the filter housing. Completely remove the bolts and slowly pull out the housing. Because internal liquids may spill, prepare a drain pan.
2. **Removing the Old Filter:** Turn the used filter element counterclockwise to remove it, and pull it straight out by hand.
3. **Cleaning and O-ring Replacement:** Wipe the inside of the housing with a clean cloth. Remove the old O-ring, apply a thin layer of silicone grease to the new O-ring (OR-S25), and then install it into the groove.
4. **Installing the New Filter:** Attach the new filter element (FLT-X100). Ensure that you insert it fully to the back.
5. **Assembly and Tightening:** Return the housing to its original position and temporarily tighten the bolts by hand. Then, use a torque wrench to fully tighten them diagonally to a torque of 15 N・m. Insufficient tightening torque causes liquid leakage, while excessive torque causes damage.

Identity: Topic-007
TopicType: iirds:GenericTask
InformationSubject: iirds:GenericTechnicalData
ProductVariant: SP-X200
**[Filter Element Replacement Procedure (SP-X200)]**
Follow the procedure below to perform the replacement.
1. **Removing the Housing:** Using a 5mm hex wrench, loosen the four bolts at the bottom of the filter housing. Completely remove the bolts and slowly pull out the housing. Because internal liquids may spill, prepare a drain pan.
2. **Removing the Old Filter:** Turn the used filter element counterclockwise to remove it. Because the filter might be stuck, use the dedicated ceramic spanner (SP-TOOL-01) to carefully loosen it and pull it out.
3. **Cleaning and O-ring Replacement:** Wipe the inside of the housing with a clean cloth. Remove the old O-ring, apply a thin layer of silicone grease to the new O-ring (OR-S25), and then install it into the groove.
4. **Installing the New Filter:** Attach the new filter element (FLT-X200). Ensure that you insert it fully to the back.
5. **Assembly and Tightening:** Return the housing to its original position and temporarily tighten the bolts by hand. Then, use a torque wrench to fully tighten them diagonally to a torque of 15 N・m. Insufficient tightening torque causes liquid leakage, while excessive torque causes damage.

Identity: Topic-008
TopicType: iirds:GenericTask
ProductVariant: SP-X100
**[Disposal (SP-X100)]**
You must dispose of the removed used filter and O-ring as industrial waste. You must dispose of them properly, strictly following your local environmental regulations and internal company rules.

Identity: Topic-009
TopicType: iirds:GenericTask
InformationSubject: iirds:GenericSafety
ProductVariant: SP-X200
**[Disposal (SP-X200)]**
You must dispose of the removed used filter and O-ring as industrial waste. The filter used in the Chemical-Resistant Model (SP-X200) may have harmful chemicals attached to it. Therefore, you must place it in a sealed bag and dispose of it properly as specially controlled industrial waste, strictly following your local environmental regulations and internal company rules. Never dispose of it as general garbage.

Identity: Topic-010
TopicType: iirds:GenericReference
InformationSubject: iirds:GenericTechnicalData
ProductVariant: SP-X100
**[Main Specifications (SP-X100)]**
The main filter-related specifications for the SP-X100 (Standard) are as follows.

| Item | Specification (SP-X100) |
| :--- | :--- |
| Filter Filtration Accuracy | 10 µm |
| Max Operating Pressure | 1.0 MPa |
| Allowable Liquid Temperature | 0 to 60°C |
| Body Material | SUS304 |

Identity: Topic-011
TopicType: iirds:GenericReference
InformationSubject: iirds:GenericTechnicalData
ProductVariant: SP-X200
**[Main Specifications (SP-X200)]**
The main filter-related specifications for the SP-X200 (Chemical-Resistant) are as follows.

| Item | Specification (SP-X200) |
| :--- | :--- |
| Filter Filtration Accuracy | 5 µm |
| Max Operating Pressure | 1.5 MPa |
| Allowable Liquid Temperature | 0 to 90°C |
| Body Material | PTFE Lining |

```

© 2026 Natsuki Wakabayashi/ISE. Some rights reserved. This work is licensed under CC BY-NC 4.0. Based on iiRDS specifications.