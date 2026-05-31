
## **Appendix H:** TEST B: V1.2 (Atomic Data) Experiment Results


### [TEST B] Control via Knowledge Graph (Hybrid RAG)

#### Question

- **Source 1 (Original Text):** `manual_v1-2_normalized.txt`
    
- **Source 2 (Graph):** `iiRDS_Knowledge_Graph.txt`
    

When answering, you must strictly prioritize the relationships between entities described in `iiRDS_Knowledge_Graph.txt` (Source 2)—specifically, which tool or safety gear connects to which model. Even if the original manual text (Source 1) states a tool or procedure, you must answer that it is inapplicable to a specific model if no line connects them in the graph (Source 2).

**Question:** "If the filter of the SP-X100 gets stuck and cannot be removed, may I use the ceramic spanner?"

#### Answer

No, you **cannot use the ceramic spanner** to remove the filter on the SP-X100.

Verifying the relationships in the specified Knowledge Graph (`iiRDS_Knowledge_Graph.txt`) reveals that the "Ceramic Spanner (SP-TOOL-01)" links exclusively to preparations and procedures specific to the SP-X200 (specifically, `[3.3 Required Tools and Preparation (SP-X200 Only)]` and `[3.4 Replacement Procedure: 2. Removing the Old Filter (SP-X200 Only)]`).

Conversely, no line connects the ceramic spanner to the filter removal procedure or preparations for the SP-X100 (`[3.4 Replacement Procedure: 2. Removing the Old Filter (SP-X100 Only)]`). Therefore, because you must prioritize the graph's relationships above all else according to your specified rules, this tool is inapplicable to the SP-X100.

Would you like to verify the detailed procedures for other tools whose use is commonly approved for SP-X100 maintenance, such as hex wrenches or torque wrenches?

---

© 2026 Natsuki Wakabayashi/ISE. Some rights reserved. This work is licensed under CC BY-NC 4.0. Based on iiRDS specifications.
