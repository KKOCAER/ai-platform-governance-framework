# AI Risk Scoring Matrix – Example

## Scoring Dimensions

- Impact (1–5)
- Exploitability (1–5)
- Detectability (1–5, reverse scale)
- Autonomy Level (1–5)
- Data Sensitivity Multiplier (1–3)
- Regulatory Exposure Multiplier (1–3)

---

## Formula

Risk Score = 
(Impact + Exploitability + Detectability + Autonomy Level)
× Data Sensitivity Multiplier
× Regulatory Exposure Multiplier

---

## Example Threat Cases

| Threat Scenario                         | Impact | Exploit | Detect | Auto | Data Mult | Reg Mult | Score |
|-----------------------------------------|--------|---------|--------|------|----------|----------|-------|
| Prompt Injection (Policy Bypass)       | 4      | 4       | 3      | 3    | 2        | 2        | 56    |
| RAG Data Poisoning                     | 5      | 3       | 4      | 2    | 3        | 3        | 126   |
| Tool Invocation Privilege Escalation   | 5      | 4       | 3      | 4    | 3        | 3        | 144   |
| Output Data Exfiltration               | 4      | 3       | 2      | 2    | 3        | 3        | 81    |

---

## Interpretation

- 0–50 → Moderate Risk
- 50–100 → High Risk
- 100+ → Critical Governance Exposure

This model enables comparative prioritization and board-level communication.
