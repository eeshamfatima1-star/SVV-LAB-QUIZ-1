# Defect Classification (V&V Task)

This document identifies defect types in given requirements and provides reasons.

---

## 1. “System should be fast”

### Defect Type: Non-verifiable

### Reason:
The term "fast" is vague and does not define any measurable performance metric (e.g., response time, throughput). Therefore, it cannot be tested or verified.

---

## 2. “User login must be secure and quick”

### Defect Type: Ambiguity + Inconsistency

### Reason:
- "Secure" is not clearly defined (no security standard mentioned).
- "Quick" is also undefined and subjective.
- Combining two unclear requirements introduces ambiguity and potential inconsistency in interpretation.

---

## 3. “System shall respond in less than 2 seconds”

### Defect Type: Valid Requirement (No Defect)

### Reason:
This requirement is clear, measurable, and testable. It defines an exact performance threshold (2 seconds), making it verifiable.

---

# End of Document
