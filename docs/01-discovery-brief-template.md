# Discovery Brief Template

Use this file to create your one-page discovery brief for Legacy-Trust Bank.

## 1. Problem summary

Write 80-120 words answering:
- What is happening now?
- Why is it failing at scale?
- Why does it matter financially and operationally?
 

S: Legacy Trust Bank has been growing gradually over the years in personal loans, credit cards, and auto finance, but its collections tools never evolved as one joined-up system. Teams adapted around the gaps by building spreadsheet trackers, email templates, and local workarounds on top of the legacy collections database.

C: Despite Legacy Trust Bank spending years modernising their customer-facing banking journeys, more than 50 representatives are still working across spreadsheets, email trails, and a 20-year-old collections database to manage over 100,000 delinquent accounts. This is resulting in missed follow-ups, duplicated activity, and inconsistent status updates which are now directly affecting recoveries, operational capacity, and leadership confidence.

These workarounds are failing at scale because they rely heavily on individual memory, manual reconciliation, and duplicated effort, so as delinquent account volumes increased, those workarounds stopped scaling.

This matters financially and operationally because it means that Legacy Trust is wasting time repeating processes that have already been done, therefore delaying the customers from receiving their services. This could result in customers moving to a different back which would be detrimental to Legacy Trust financially as they rely on customers using their services to remain operational.

Q: What is the main factor causing all of these issues and what can be done to keep Legacy Trust Bank operating smoothly?

## 2. Stakeholder overview

Complete a short table like the one below.

| Stakeholder group | What they care about | How success is measured | Main worry | Evidence they will trust |
|---|---|---|---|---|

| Operations leadership | Eliminating operational strain, duplicate outreach, and manual status checks across 50+ reps. | Reduction in average handling time and elimination of duplicate follow-ups across 100k delinquent accounts. | Straightforward and complex cases remain tangled together, wasting human judgment on routine admin. | Clear As-Is process breakdown, quantified time savings per activity, and a practical future-state workflow. |

| Team leaders and representatives | Operational honesty, realistic workflows, and seamless hand-offs between system and staff. | Match between actual ground-level workflows and official process maps; zero orphaned tasks. | Recommendations make the portal look successful on paper while difficult cases and messy hand-offs still land back on representatives. | Future-state workflow showing where representative work begins and ends. |

| Finance | Eliminating revenue leakage, ensuring regulatory compliance, and defensible ROI. | Measurable cost reduction, recovery rate uplift, and a clear 12-month payback period. | The project relies on unverified assumptions or "hoped-for" revenue rather than hard operational savings. | Fully audited Excel model with transparent assumptions, sensitivity testing, and P&L impact breakdown. |

| Product and delivery | High-quality discovery documentation that seamlessly converts into a buildable backlog. | Full end-to-end requirement traceability from discovery data to prototype specifications. | Discovery output summaries are too vague to shape realistic Phase 1 user stories and backlog items that software developers can actually build from. | Line-item traceability linking every pain point -> JTBD -> process step -> automation candidate. |

| Customers | Fast resolution, clear debt visibility, and simple, non-repetitive self-service options. | Reduced contact friction, and clear options to confirm or settle balances. | Being subjected to delayed, repetitive communications or forced through slow, manual contact paths. | Real-time balance visibility, instant confirmation of payments/promises, and clear digital next steps. |

## 3. Discovery questions

Write 5-7 questions that point toward evidence.

Starter examples:
- Which steps in debt recovery are high-volume and rules-driven enough for self-service?
- Where do spreadsheets and manual handoffs create duplicate work?
- Which baseline metrics best show operational waste and revenue leakage?

- Which steps depend on which system?
- Which specific stages in the debt resolution journey cause the highest customer drop-off or prompt repetitive contact calls to representatives?
- What operational changes are needed to ensure team leaders and representatives trust that the portal will reduce, rather than re-route, their workload?

## 4. Traceability starter

Create a first-pass table.

| Stakeholder concern | Likely process area affected | Possible metric or evidence source | Likely deliverable |
|---|---|---|---|

| Straightforward and complex cases remain tangled together, wasting human judgment on routine admin. | Work Queue Allocation | We do not have a way to identify which cases are straightforward versus which require specialist handling. SN-039 | As-Is Process Map |

| Difficult cases and messy hand-offs still land back on representatives. | Escalation & Exception Handoff Management | We lose at least 20% of follow-ups because they fall between shifts and no one owns the handoff. SN-040 | To-Be Process View |

| The project relies on unverified assumptions or "hoped-for" revenue rather than hard operational savings. | Financial Modeling & Value Realisation | The spreadsheet workaround cost us five hundred thousand pounds in lost recovery last year. | Excel ROI Model |

| Discovery output summaries are too vague to shape realistic Phase 1 user stories and backlog items that software developers can actually build from. | Discovery-to-Delivery Backlog Pipeline | Full stakeholder_interview_notes.csv pack | Prioritised JTBD List & Full Traceability Matrix |

| Subjected to delayed, repetitive communications or forced through slow, manual contact paths. | Inbound Customer Verification & Resolution | Customers call back three times because they do not remember what they were told on the first call. SN-002 | Customer JTBD Statements & Phase 1 Portal |

## 5. Final problem statement

End with a concise problem statement in your own words.

> Tip: if your statement still sounds like 'the bank needs digital transformation,' it is too broad.

Legacy Trust Bank’s debt recovery relies on a 20-year-old database and a 200-sheet Excel workbook to manage over 100,000 delinquent accounts across 50+ representatives. Because routine early-stage cases (~60% of total volume) and complex hardship cases are mixed in the same manual queues, staff waste up to 1.5 hours daily cross-checking spreadsheets, while at least 20% of follow-ups are lost between shift hand-offs. This operational breakdown causes £500,000 in direct annual losses from spreadsheet workarounds, a 15% drop in recovery revenue, and severe data degradation. To resolve this, the bank requires an evidence-backed discovery package for a Phase 1 Self-Service Portal that resolves straightforward cases, establishes clear hand-off boundaries for complex cases, and achieves a defensible 12-month payback period.
