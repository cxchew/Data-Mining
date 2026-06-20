# Assignment 2: Discovering Hidden Patterns via Association Rule Mining 🛒

## 1. Assignment Summary
This assignment explored unsupervised pattern recognition frameworks, focusing on the mathematical principles behind association rule mining. Working as a group, the objective was to understand how corporations extract hidden relationships from large transaction registries. The project examined the internal mechanics of the **Apriori Algorithm**, demonstrating how it filters out rare combinations using a minimum support constraint to find frequent itemsets. 

We mapped out how these itemsets are converted into conditional if-then rules by calculating three core evaluation metrics: **Support** (the absolute frequency of an itemset), **Confidence** (the directional probability of a co-purchase), and **Lift** (the strength of a rule over random chance). Finally, the assignment analyzed real-world applications, showing how these algorithms fuel market basket analysis in retail stores to optimize shelf placements, and assist healthcare systems in identifying co-occurring symptoms for early disease diagnoses.

---

## 2. Evidence and Explanation

* **Apriori Frequency Filtering:** Evaluated multi-item transaction tables by applying a structural support threshold ($\ge 0.6$) to eliminate rare item combinations and isolate frequent itemsets (e.g., `{Milk}`, `{Diaper}`, `{Beer}`).
* **Rule Generation Metrics:** Computed exact conditional probability indicators to extract strong rules from data logs. For instance, an item relationship statement like $A \rightarrow B$ was validated by verifying its confidence ratios against baseline rules:
$$Support(A \rightarrow B) = \frac{\text{Transactions with both A and B}}{\text{Total transactions}}$$
$$Confidence(A \rightarrow B) = \frac{Support(A \cup B)}{Support(A)}$$
* **Lift Strength Verification:** Applied independent lift formulas to distinguish true causal item pairings from coincidental overlaps, verifying rules where $Lift > 1.0$ to ensure strong logical relationships.
* **Cross-Industry Deployment Mapping:** Outlined explicit operational blueprints applying association rule mining to commercial retail setups (market basket placements) and clinical diagnostic programs (tracking symptom clusters like fever, cough, and fatigue).

---

## 3. Reflection

### What I Learned
* Working with association rules changed how I think about pattern recognition. I learned that high confidence metrics alone do not guarantee a valuable relationship, highlighting why calculating lift is essential to filter out common items that distort buying patterns.
* Tracing the pruning steps of the Apriori algorithm showed me how to manage computational complexity. Limiting checks to frequent itemsets prevents systems from wasting resources on rare combinations, ensuring efficient processing even on large data logs.
* Mapping algorithm concepts onto diverse fields like retail layout design and healthcare symptom tracking proved the versatility of data mining. It showed me how the exact same math can solve completely different optimization challenges.
