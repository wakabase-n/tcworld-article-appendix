## **Appendix B:** Knowledge Graph for Atomic Data v1.2


Based on the nature of each entity, we assign the predicates as follows: `iirds:relates-to-product-variant` (Product Variant), `iirds:has-tool` (Tool), `iirds:has-supply` (Supply/Equipment), and `iirds:has-component` (Component).


```
- [Maintenance Overview and Recommended Replacement Intervals] --(iirds:relates-to-product-variant)--> [ex:SP-X100]
    
- [Maintenance Overview and Recommended Replacement Intervals] --(iirds:relates-to-product-variant)--> [ex:SP-X200]
    
- [Maintenance Overview and Recommended Replacement Intervals] --(iirds:has-component)--> [Filter Element]
    
- [Maintenance Overview and Recommended Replacement Intervals] --(iirds:has-component)--> [Motor]
    
- [Maintenance Overview and Recommended Replacement Intervals] --(iirds:has-component)--> [Differential Pressure Gauge]
    
- [Safety Precautions (Common: Risk of Electric Shock and Residual Pressure)] --(iirds:relates-to-product-variant)--> [ex:SP-X100]
    
- [Safety Precautions (Common: Risk of Electric Shock and Residual Pressure)] --(iirds:relates-to-product-variant)--> [ex:SP-X200]
    
- [Safety Precautions (Common: Risk of Electric Shock and Residual Pressure)] --(iirds:has-component)--> [Main Power Supply]
    
- [Safety Precautions (Common: Risk of Electric Shock and Residual Pressure)] --(iirds:has-component)--> [Power Plug]
    
- [Safety Precautions (Common: Risk of Electric Shock and Residual Pressure)] --(iirds:has-component)--> [Drain Valve]
    
- [Safety Precautions: Risk of Chemical Burns (SP-X200 Only)] --(iirds:relates-to-product-variant)--> [ex:SP-X200]
    
- [Safety Precautions: Risk of Chemical Burns (SP-X200 Only)] --(iirds:has-supply)--> [Chemical-Resistant Gloves]
    
- [Safety Precautions: Risk of Chemical Burns (SP-X200 Only)] --(iirds:has-supply)--> [Safety Glasses]
    
- [Safety Precautions: Risk of Chemical Burns (SP-X200 Only)] --(iirds:has-supply)--> [Chemical Liquid]
    
- [Items to Prepare: Tools and Components Required for Replacement (Common)] --(iirds:relates-to-product-variant)--> [ex:SP-X100]
    
- [Items to Prepare: Tools and Components Required for Replacement (Common)] --(iirds:relates-to-product-variant)--> [ex:SP-X200]
    
- [Items to Prepare: Tools and Components Required for Replacement (Common)] --(iirds:has-supply)--> [O-ring (OR-S25)]
    
- [Items to Prepare: Tools and Components Required for Replacement (Common)] --(iirds:has-tool)--> [Hex Wrench]
    
- [Items to Prepare: Tools and Components Required for Replacement (Common)] --(iirds:has-tool)--> [Torque Wrench]
    
- [Items to Prepare: Replacement Filter (SP-X100 Only)] --(iirds:relates-to-product-variant)--> [ex:SP-X100]
    
- [Items to Prepare: Replacement Filter (SP-X100 Only)] --(iirds:has-supply)--> [Replacement Filter (FLT-X100)]
    
- [Items to Prepare: Replacement Filter and Dedicated Tool (SP-X200 Only)] --(iirds:relates-to-product-variant)--> [ex:SP-X200]
    
- [Items to Prepare: Replacement Filter and Dedicated Tool (SP-X200 Only)] --(iirds:has-supply)--> [Replacement Filter (FLT-X200)]
    
- [Items to Prepare: Replacement Filter and Dedicated Tool (SP-X200 Only)] --(iirds:has-tool)--> [Ceramic Spanner (SP-TOOL-01)]
    
- [Replacement Procedure: 1. Removing the Housing] --(iirds:relates-to-product-variant)--> [ex:SP-X100]
    
- [Replacement Procedure: 1. Removing the Housing] --(iirds:relates-to-product-variant)--> [ex:SP-X200]
    
- [Replacement Procedure: 1. Removing the Housing] --(iirds:has-tool)--> [Hex Wrench]
    
- [Replacement Procedure: 1. Removing the Housing] --(iirds:has-component)--> [Filter Housing]
    
- [Replacement Procedure: 1. Removing the Housing] --(iirds:has-component)--> [Bolt]
    
- [Replacement Procedure: 1. Removing the Housing] --(iirds:has-supply)--> [Drip Pan]
    
- [Replacement Procedure: 2. Removing the Old Filter (SP-X100 Only)] --(iirds:relates-to-product-variant)--> [ex:SP-X100]
    
- [Replacement Procedure: 2. Removing the Old Filter (SP-X100 Only)] --(iirds:has-component)--> [Filter Element]
    
- [Replacement Procedure: 2. Removing the Old Filter (SP-X200 Only)] --(iirds:relates-to-product-variant)--> [ex:SP-X200]
    
- [Replacement Procedure: 2. Removing the Old Filter (SP-X200 Only)] --(iirds:has-component)--> [Filter Element]
    
- [Replacement Procedure: 2. Removing the Old Filter (SP-X200 Only)] --(iirds:has-tool)--> [Ceramic Spanner (SP-TOOL-01)]
    
- [Replacement Procedure: 3. Cleaning and O-ring Replacement] --(iirds:relates-to-product-variant)--> [ex:SP-X100]
    
- [Replacement Procedure: 3. Cleaning and O-ring Replacement] --(iirds:relates-to-product-variant)--> [ex:SP-X200]
    
- [Replacement Procedure: 3. Cleaning and O-ring Replacement] --(iirds:has-component)--> [Housing]
    
- [Replacement Procedure: 3. Cleaning and O-ring Replacement] --(iirds:has-supply)--> [Industrial Wipe]
    
- [Replacement Procedure: 3. Cleaning and O-ring Replacement] --(iirds:has-supply)--> [O-ring (OR-S25)]
    
- [Replacement Procedure: 3. Cleaning and O-ring Replacement] --(iirds:has-supply)--> [Silicone Grease]
    
- [Replacement Procedure: 4. Installing the New Filter] --(iirds:relates-to-product-variant)--> [ex:SP-X100]
    
- [Replacement Procedure: 4. Installing the New Filter] --(iirds:relates-to-product-variant)--> [ex:SP-X200]
    
- [Replacement Procedure: 4. Installing the New Filter] --(iirds:has-component)--> [Filter Element]
    
- [Replacement Procedure: 5. Reassembly and Tightening] --(iirds:relates-to-product-variant)--> [ex:SP-X100]
    
- [Replacement Procedure: 5. Reassembly and Tightening] --(iirds:relates-to-product-variant)--> [ex:SP-X200]
    
- [Replacement Procedure: 5. Reassembly and Tightening] --(iirds:has-component)--> [Housing]
    
- [Replacement Procedure: 5. Reassembly and Tightening] --(iirds:has-component)--> [Bolt]
    
- [Replacement Procedure: 5. Reassembly and Tightening] --(iirds:has-tool)--> [Torque Wrench]
    
- [Disposal (Common)] --(iirds:relates-to-product-variant)--> [ex:SP-X100]
    
- [Disposal (Common)] --(iirds:relates-to-product-variant)--> [ex:SP-X200]
    
- [Disposal (Common)] --(iirds:has-component)--> [Filter]
    
- [Disposal (Common)] --(iirds:has-supply)--> [O-ring]
    
- [Disposal: Handling as Specially Controlled Industrial Waste (SP-X200 Only)] --(iirds:relates-to-product-variant)--> [ex:SP-X200]
    
- [Disposal: Handling as Specially Controlled Industrial Waste (SP-X200 Only)] --(iirds:has-component)--> [Filter]
    
- [Disposal: Handling as Specially Controlled Industrial Waste (SP-X200 Only)] --(iirds:has-supply)--> [Sealed Bag]
    
- [Main Specifications (SP-X100)] --(iirds:relates-to-product-variant)--> [ex:SP-X100]
    
- [Main Specifications (SP-X200)] --(iirds:relates-to-product-variant)--> [ex:SP-X200]

```



© 2026 Natsuki Wakabayashi/ISE. Some rights reserved. This work is licensed under CC BY-NC 4.0. Based on iiRDS specifications.
