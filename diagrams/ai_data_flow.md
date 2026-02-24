+--------------------+
|  User / API Input  |
+--------------------+
          |
          v
+-----------------------------+
| Input Guardrail Engine      |
| - Prompt classification     |
| - Intent scoring            |
+-----------------------------+
          |
          v
+-----------------------------+
| Context Aggregation Layer   |
| - RAG retrieval             |
| - API ingestion             |
| - Vector store lookup       |
+-----------------------------+
          |
          v
+-----------------------------+
| Policy Injection Layer      |
| - Constraint enforcement    |
| - Risk tagging              |
+-----------------------------+
          |
          v
+-----------------------------+
| LLM Inference Engine        |
| - Model execution           |
| - Drift evaluation          |
+-----------------------------+
          |
          v
+-----------------------------+
| Tool Invocation Gateway     |
| - Permission gating         |
| - Just-in-time authorization|
+-----------------------------+
          |
          v
+-----------------------------+
| Output Sanitization         |
| - DLP scan                  |
| - Sensitivity classification|
+-----------------------------+
          |
          v
+-----------------------------+
| Telemetry & Logging         |
| - Risk aggregation          |
| - Audit trail               |
+-----------------------------+
          |
          v
+-----------------------------+
| Human Review / Feedback     |
+-----------------------------+
