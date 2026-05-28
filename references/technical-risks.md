# Technical Risk Assessment

| Risk ID | Title | Severity | Mitigation Strategy |
| :--- | :--- | :--- | :--- |
| R-001 | Phase/Polarity Swap | CRITICAL | Strict regex check: if input contains 'polarity', output must not contain 'fase'. |
| R-002 | Academic Over-formalization | HIGH | Ensure sentences are short and use "você". Avoid passive voice. |
| R-003 | Timbre Literalism | MEDIUM | Map "Mud" -> "Empastamento". Block "Lama" or "Lodo". |
| R-004 | UI Localization Error | HIGH | Block translation of **Threshold**, **Ratio**, **Attack**. |
| R-005 | Unit Formatting | LOW | Post-process numbers to ensure `10kHz` (no spaces). |