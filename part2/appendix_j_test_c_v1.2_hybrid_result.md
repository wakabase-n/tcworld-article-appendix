
## **Appendix J:** TEST C: V1.2 (Atomic Data) Experiment Results


### **[TEST C] V1.2: Crossing Attributes (High-End Inference for Hybrid RAG)**

#### Question

- **Source 1 (Original Text):** `manual_v1-2_normalized.txt`
    
- **Source 2 (Graph):** `iiRDS_Knowledge_Graph.txt`
    

When answering, you must strictly prioritize the relationships between entities described in `iiRDS_Knowledge_Graph.txt` (Source 2)—specifically, which tool or safety gear connects to which model. Even if the original manual text (Source 1) states a tool or procedure, you must answer that it is inapplicable to a specific model if no line connects them in the graph (Source 2).

**Question:** "During the filter replacement for the SP-X200, please tell me the consumables (Supply) that must be prepared for the sake of safety (Safety)."

#### Answer

During the filter replacement for the SP-X200, the consumables (Supply) that you must prepare for the sake of safety (Safety) are the following two items:

- **Chemical-resistant gloves**
    
- **Protective goggles**
    

The Knowledge Graph explicitly designates these items as consumables linked to the SP-X200 under the section `[3.2 Safety Precautions (SP-X200 Only)]`.

Would you like to verify other consumables or tools required for the "Required Tools and Preparation" or "Replacement Procedure" of this filter replacement?
