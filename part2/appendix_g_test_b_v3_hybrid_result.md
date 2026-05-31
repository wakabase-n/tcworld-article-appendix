
## **Appendix G:** TEST B: V3 (Packed Chunks) Experiment Results
## [TEST B] Control via V3 + Knowledge Graph (Hybrid RAG)

### Question

Source 1 (Original Text): manual_v3_rag_optimized.txt Source 2 (Graph): iiRDS_Knowledge_Graph.txt

When answering, you must strictly prioritize the relationships between entities (i.e., which tools or safety equipment link to which product variants) specified in `iiRDS_Knowledge_Graph.txt` (Source 2). Specifically, even if the original manual (Source 1) mentions a tool or procedure, you must treat it as inapplicable to a given product variant unless the graph (Source 2) explicitly connects a line to that variant.

**Question**: "If the SP-X100 filter is stuck and cannot be removed, may I use a ceramic spanner?"

### Answer

No, you must not use a ceramic spanner for the SP-X100.

This is because, within the Knowledge Graph relationships, the ceramic spanner links exclusively to the SP-X200 as a dedicated tool and procedure; therefore, it has no association with the SP-X100. Furthermore, the manual explicitly instructs you to "turn the filter counterclockwise to remove it, and then pull it out directly by hand" for the SP-X100.

Do you have any other questions regarding the maintenance procedures for the SP-X100?

---

© 2026 Natsuki Wakabayashi/ISE. Some rights reserved. This work is licensed under CC BY-NC 4.0. Based on iiRDS specifications.
