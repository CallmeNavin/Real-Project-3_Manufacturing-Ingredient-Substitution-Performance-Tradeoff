# Real-Project-3_Manufacturing-Ingredient-Substitution-Performance-Tradeoff

**Executive Snapshot**

- A lower-cost substitute ingredient was introduced during a temporary supply shortage of a critical feed material. This analysis evaluated whether the substitute created real value or simply shifted cost into operational instability.
- The result:
  + Lower input cost was real
  + Larger size output was visible
  + But process stability weakened
  + Real productivity gains were inconsistent after contamination adjustment
- Conclusion: The substitute was not a direct replacement. It was a cheaper but more operationally fragile option that should only be used selectively.
![decision_matrix](https://github.com/CallmeNavin/Real-Project-3_Manufacturing-Ingredient-Substitution-Performance-Tradeoff/blob/main/result.png)

**What This Case Actually Felt Like**

**1. Problem**

- A critical feed ingredient became temporarily constrained due to supply shortage. To avoid production disruption, PD team introduced an alternative substitute material into multiple diet formulations
- The substitute was economically attractive and operationally available, but its real production impact was unknown
- This created a practical business question:
  + Can the substitute ingredient maintain acceptable production performance, or does its lower cost create larger downstream losses?

→ The core business question became: Should production continue using the substitute material, revert to the original ingredient, or apply the substitute only under controlled operating conditions?

**2. Challenges**

- This was not a simple cost comparison. The substitute ingredient affected multiple parts of the production system simultaneously:
  + Feed cost
  + Moisture control stability
  + Contamination rate
  + Growth size
  + Productivity
  + Output quality
- This created a multi-layer trade-off problem:
  + Lower material cost did not automatically mean better operational performance.
  + Several practical challenges made the analysis more difficult:
    -Ingredient substitution was tested across multiple diet pairs, not a single formula
    - Different diet groups had different nutritional baselines
    - Performance outcomes were affected by both ingredient substitution and operating conditions
    - Weather conditions differed across trial periods and could influence moisture outcomes
- The real challenge was not: “Which ingredient is better?”. But the real was: “Under real production constraints, what does substitution improve and what does it quietly damage?”

**3. Approach**

**Key Principles**

To evaluate substitution impact, I structured the analysis across 04 operational layers.

**Details**

- Step 1 — Compare paired diet structures: Instead of comparing all diets globally, diets were evaluated in matched substitution pairs. This controlled for formulation intent and allowed comparison between: original baseline diets & substitute-based diets. Each pair was assessed under the same operational objective.
- Step 2 — Evaluate substitution trade-offs across the process: The comparison was structured across 04 decision layers:
  + Input economics → feed ingredient cost
  + Process stability → output moisture & contamination rate
  + Biological performance → Growth size & productivity
  + Output quality → protein quality in final product
- Step 3 — Separate apparent gains from real gains: Several substitute diets showed strong improvement in visible metrics (especially size and productivity). However, these gains were not accepted at face value. I separated:
  + apparent gains
  + real gains (after contamination-adjusted productivity and output quality)
- Step 4 — Frame substitution as a decision model: The goal was not to identify whether the substitute was universally “better” or “worse”. The goal was to define:
  + Where substitution creates real value
  + Where substitution becomes operationally expensive
  + Which substitute diets are usable
  + Which should be stopped

→ This turned the analysis from material comparison into substitution decision guidance.

**4. Key Insights**

- Lower cost was real, but not free: The substitute ingredient consistently reduced feed ingredient cost across diets. This created a real economic advantage at input level.
- However, this gain came with operational penalties:
  + Harder moisture control
  + Higher contamination rate
  + Less stable productivity (Substitute diets consistently produced larger larvae but bigger larvae did not mean better performance)
  + Lower output quality consistency

→ The substitute was cheaper, but more sensitive and more expensive to control.

→ At first glance, this suggested better biological performance. However, once contamination and process loss were accounted for, the apparent productivity advantage often disappeared — and in several diets reversed.

→ The real conclusion was: The substitute is not a direct replacement material. It is a lower-cost but higher-sensitivity operating option. This means its value depends on operational control quality.

→ The analysis reframed the decision from: “Should we replace the original ingredient?” to “Where is substitution operationally worth the trade-off?”. I think that was the real business decision.

**5. Engineer Diary**

_5.1. First wrong assumption_

- This was not a material comparison problem. It was a substitution risk problem disguised as a cost-saving opportunity
- At first, the substitute looked promising:
  + Lower cost
  + Larger size
  + Acceptable nutritional profile

→ On paper, it looked like an easy replacement.

_5.2. What actually worked_

- Once process losses were included, the picture changed: The substitute did not fail through obvious collapse. It failed through operational fragility
- That was the real risk: not immediate failure, but higher sensitivity, narrower control margin and faster performance erosion when execution drifted

**6. Notes on Confidentiality**

- To respect company confidentiality:
  + Company identity is not disclosed
  + Exact process parameters are omitted
  + Internal dataset structures are not shown
  + Numerical thresholds are generalized → This case focuses on methodology and thinking rather than proprietary information
- The analysis was independently conducted, from data extraction to insight development. However, the problem itself was defined within a real operational context, where:
  + Production teams provided perspective on process constraints
  + QA/QC teams validated quality-related observations

**8. Personal Takeaway**

- In manufacturing, cheaper inputs do not reduce cost by default. They often relocate cost into operational complexity.
- The real job of analysis is not to compare prices. It is to identify whether savings remain real after the system absorbs the trade-off.
- Tools Used:
  + SQL (data extraction and data preparation)
  + Excel / Pivot Tables (pair comparison, metric slicing, operational validation)
  + PowerPoint (decision framing and stakeholder presentation)
